1.AtomoVideo
Title:《AtomoVideo: High Fidelity Image-to-Video Generation  》
ArXiv:2403.01800
 
![image (3)](https://github.com/user-attachments/assets/c0566210-98c1-4821-8f3f-d1be19023a85)

简介：模型整体结构采用AnimateDiff架构，使用视频段中的单帧作为条件输入。训练时将单帧条件、帧mask、和加噪噪声直接在channel维度进行拼接(c=9)，然后通过conv模块降维，丢到AnimateDiff中进行学习。训练的时候采用zero-terminal SNR和v-prediction，有助于视频训练的稳定。
2. Cinemo
Title:《 Cinemo: Consistent and Controllable Image Animation with Motion Diffusion Models》
ArXiv:2407.15642
![image (2)](https://github.com/user-attachments/assets/03c23af4-0ee3-41c2-a767-f904247cd581)

简介：模型整体结构采用LaVie的结构，但与其他方法直接预测连续多帧图片不同，该方法预测的是多帧与第一帧的运动差motion residual。在训练时将视频中的其他帧与第一帧做差得到motion residual，然后第一帧不做处理，加噪后丢到去噪网络中学习。除此之外，用中间间隔b帧跟第一帧求PSNR值，将该PSNR值作为一个运动感知条件通过位置编码，跟时间条件t相加后注入到网络中。
在测试时，使用单帧图latent的离散余弦变换（DCT）之后的低频部分进行加噪，然后输入到网络中输出。这里所有后续帧都用该低频部分进行加噪作为初始化。可以比较好地提高生成帧之间的连续性。（并且可以通过参数b来控制帧之间运动的幅度）
3. FreeInit
Title:《  FreeInit: Bridging Initialization Gap in Video Diffusion Models》
ArXiv: 2312.07537
![image](https://github.com/user-attachments/assets/75aaa424-4899-482a-90bd-e660450a3884)

简介：文章分析了img2vid任务中对于连续帧的噪声初始化问题，由上图可知，（a）全频带解码图（b）低频解码图（c）高频解码图。可以看到在加噪过程中低频带被腐蚀的程度较小，而高频被腐蚀很多，所以可以通过保持低频的一致来加强视频生成的一致性。，使用同一个低频噪声来做初始化。这种思想在FreeU和FreeNoise中都有提到。通过保持初始化噪声的低频一致性可以约束最终连续帧的一致性。
![image (1)](https://github.com/user-attachments/assets/16e97007-6710-436a-b329-f9a17a06b789)
