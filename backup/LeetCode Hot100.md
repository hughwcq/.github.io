# 1 手撕快排

![](https://secure2.wostatic.cn/static/9oXUFGjLT8PNKD1RtxTpp/image.png?auth_key=1711379579-5RuXdG9MZqetRiqfTC32Wb-0-983764c7141f0cb657f3c847b6b4e228)

# 2 字母异位词分组

![](https://secure2.wostatic.cn/static/dSvEuTRLgEpoty8JjjbXwF/image.png?auth_key=1711379579-ez9vB55bZYBHwTxLs9QsjL-0-b2faf0efbb2441416e1a01185fb898d0)

![](https://secure2.wostatic.cn/static/3YvFdqFeQEiNvuSrzgLHFq/image.png?auth_key=1711379579-9GrLemvNyXNBusjH7SMagz-0-976aadfb38b7fbfa71f2cb69971e33b2)

# 3 最长连续序列

![](https://secure2.wostatic.cn/static/3n7yBPaofBRModwTaH9rYm/image.png?auth_key=1711379579-aZHjdYSn8pbzX22pNn58qz-0-99673477d04dd3d187ab535ed0035de7)

**解题思路：**先用set()去重，然后遍历，当上一个值num-1不存在但当前值存在时就继续找下一个。

**代码：**

![](https://secure2.wostatic.cn/static/vV2M9s2J7J4QA9sZ5kUjWL/image.png?auth_key=1711379580-FyZo2niQspu9U2yzwYrqi-0-c576618d52b7d3ca38748fc154e6685a)

# 4 移动零

![](https://secure2.wostatic.cn/static/fbzbBQihEibFXoAZ4eiMzJ/image.png?auth_key=1711379579-iMZgYNc7h6RnqVyKxDrLHh-0-7b555b0ffd244e96bd3a9e6b4203c415)

**解题思路**：快慢双指针，当快指针值不等于0时，传到慢指针值，让慢指针加1，快指针一直加一

![](https://secure2.wostatic.cn/static/h3bgi4Y25YBsstRqhY6hbC/image.png?auth_key=1711379579-k9CEpPhCkXZV1aWdBFnnx2-0-737bed52b25e33dbef61f6aa58b82880)

# 5 盛最多水的容器

![](https://secure2.wostatic.cn/static/g5xzVPjfQQpUSNQhaaEibz/image.png?auth_key=1711379579-joMDbmQXaETgYdQtQeTMh2-0-47385283eb365b1cc76c229803dc0563)

**解题思路**：左右双指针往中间靠，选左or右的最短高度来求

![](https://secure2.wostatic.cn/static/nEQdUP5gMEKkYvy8igLzdn/image.png?auth_key=1711379579-aJqtpUyvB9u4HDaxDA9iW8-0-a27beb7b76beff028c9fefb68deea9d1)

# 6 三数之和

![](https://secure2.wostatic.cn/static/6xTzzzZRv3pDqwdDcyiRZN/image.png?auth_key=1711379579-nRdGgJLE3KM7DaU1nuKKwZ-0-0cefa31ca273fe838e4ff366b943b8e7)

**解题思路**：先排序去重，然后用左右双指针来来优化效率

![](https://secure2.wostatic.cn/static/62ZUbrExZedHuZnfjpTqFt/image.png?auth_key=1711379579-vfuc66km8opfMdXNupc2L2-0-66989dd9a021f932c0897de8442bba6d)

# 7 接雨水

![](https://secure2.wostatic.cn/static/ive8JRqQNtqtrzkHV2e8SA/image.png?auth_key=1711379579-vWE7WcPKgh4aAEHRkr2Ezm-0-8ac9573189b4fb4c50a79132e7cdb4b1)

**解题思路**：用左右双指针往中间靠

![](https://secure2.wostatic.cn/static/3shfUDuxka3J2dzKeTgHii/image.png?auth_key=1711379579-4Mo8p8QVLjTbUV93nfEiAn-0-371bfa9375c9dcb0ae1b3dcc309dc884)

# 8 无重复字符的最长子串

![](https://secure2.wostatic.cn/static/ndhiEzy2fLd1ssbKXnWPVP/image.png?auth_key=1711379579-k2U8M8aoMyDypfHymU9zSU-0-52892685b2f6de0c0aad922d8797c680)

**解题思路**：用滑动窗口，dic记录上一个字符出现的位置

![](https://secure2.wostatic.cn/static/tZTyddVehn4hAc1UwBXwEc/image.png?auth_key=1711379580-eeh9SyF1sfW54WYGAQATjV-0-052b7f4ab6df02b18f90151ec93dd841)

# 9 找到字符串中所有字母异位词

![](https://secure2.wostatic.cn/static/ptNSX4iPQ4AwDzb9TG3D2r/image.png?auth_key=1711379579-cZWLChoHCKoHjTFq5jEiC2-0-da06828fa39cf8d8a2bde3629a1aae1e)

**解题思路**：用滑动窗口，sorted()可以让子串重新排列一下，或者弄一个26字母的字典记录子串字符的个数进行统计，sorted()代码为： 

![](https://secure2.wostatic.cn/static/spbrbcNgybxXGPtDEQ9dwD/image.png?auth_key=1711379579-be5ME4sSd5iSSe21TXU4oP-0-50a6703b34122918015d18fcec09c0d7)

# 10 和为K的子数组

![](https://secure2.wostatic.cn/static/tkdHS78dwtNf7wYp7LMCMb/image.png?auth_key=1711379579-pczhoXv5peAcvsinzR67Th-0-8da092cdb1934459fd3cda65d6c1b203)

**解题思路**：用前缀和（一个数组的某下标之前的所有数组元素的和）

简单解法：

![](https://secure2.wostatic.cn/static/3rCN5UtnYmMFBxSgX5rHmA/image.png?auth_key=1711379579-9Pbz69wSi6HQeM9qaXwPmQ-0-7c5f47f805a77b9bb32976fca605d29f)



# 11 滑动窗口的最大值

![](https://secure2.wostatic.cn/static/kg454Zp5cCvKUkY6gBtAzM/image.png?auth_key=1711379580-gShhnF5me36amRG2MqSus7-0-cb822e4605e13acf44ecc7b9ac5db2e1)



![](https://secure2.wostatic.cn/static/59EFZJUa5TVTDZyNr7qmYx/image.png?auth_key=1711379579-9UEULAPfRHWReSUmKFCLtc-0-20f84803fd0b776ecdc2024abe513b81)

# 12 最小覆盖子串

![](https://secure2.wostatic.cn/static/n1F46NbDv5H5oWkm6sxhYM/image.png?auth_key=1711379579-vpdGJUdXZ4vdFKs5eEbzRm-0-e0e5ffc80fa26a7be4cbf0ab03a35246)

**解题思路**：

![](https://secure2.wostatic.cn/static/iytRhCWxBK7uifG7nfq9uf/image.png?auth_key=1711379579-u96REhUiUx8yZ5LwrgCd74-0-3454d91f25a7dce32d0463d97b88a506)

![](https://secure2.wostatic.cn/static/8VWNLPkAyRAf3iGyrXYy5L/image.png?auth_key=1711379579-jNbEUhkztPefptC8sj4N4E-0-8dc5f75e5ff994cc6318ddc27464d895)

# 13 最大子数组和

![](https://secure2.wostatic.cn/static/fRq9tQWgJti7RhBd71VLUD/image.png?auth_key=1711379579-pyYHxFZcncJfAafaaqPDvK-0-3e07da2a146f4f13bf9eea145829471f)

解题思路：动态规划

![](https://secure2.wostatic.cn/static/btHZtCYYWFKGLLMPjcZWpo/image.png?auth_key=1711379579-sP6TLpQ266ZuQJ66g32uap-0-beb011ad048c6e1066e13310d252e6f6)

# 14 合并区间

![](https://secure2.wostatic.cn/static/gHbZdViQoPFyCfUtngNPS6/image.png?auth_key=1711379579-wK4f4NAZxwfah7zGKVoVvc-0-fe3a72b02638f1ffb5c39a9e4cf802d0)

![](https://secure2.wostatic.cn/static/8wCioLiSnhnFxy4i4HMpqn/image.png?auth_key=1711379579-h76SQiLkd8BEYudzWrQspk-0-eb0d93708db1c0aee3fa2b7b00e5a7c2)

# 15 除自身以外数组的乘积

![](https://secure2.wostatic.cn/static/gKzNiqQLygRVcsQPDygAD7/image.png?auth_key=1711379579-xfNw2moXrJEAL23Gkgdf4L-0-ba5620089c4e424699f03100d15f83ff)



![](https://secure2.wostatic.cn/static/qhha4G3e3W97U3atZCvB8F/image.png?auth_key=1711379579-otUWtWjWhpbQxFiAYh1rDS-0-cbd56d8bc16ac3fda5a0a3fea1a9c51b)

# 16 缺失的第一个正数

![](https://secure2.wostatic.cn/static/o9uunenkVw2BHitHZ4zM6b/image.png?auth_key=1711379579-7eEKnJhFND47q9WgcpK3DY-0-2690b699f7c5c709112a629cc7497147)

**解题思路**：简单方法：这个正整数的范围为[1，n+1]，直接在这个范围遍历nums即可。先通过set()去重，减小数组长度

![](https://secure2.wostatic.cn/static/uCdUPq7WAjnv5fJ4pnBo5H/image.png?auth_key=1711379579-h8UVeb2KtGshUYQQfgth2a-0-410088eed73ccd2a227c140b16616f94)

# 17 螺旋矩阵

![](https://secure2.wostatic.cn/static/wjCDkZJP2NAB1wf8shMMwb/image.png?auth_key=1711379579-ridRfiUiwod9Zqhmsguy64-0-10f61bd150a1062460aeaec83290162f)

**解题思路**：直接上下左右遍历,注意边界取值

![](https://secure2.wostatic.cn/static/g5SCtgnKdPXNeKFnCoPK6J/image.png?auth_key=1711379579-682NbPYA3KFsxPNj1KuH7E-0-9d8745df23ff1163e9a13ede5dc439ca)

# 18 搜索二维矩阵

![](https://secure2.wostatic.cn/static/o18kthJz8SqucpBANZoHwX/image.png?auth_key=1711379579-61cEzjeWc9AqHPKjV75mom-0-4482667167c6c6a8e761fa06e0c6aefc)

**解题思路**：从右上角15这个值开始遍历，在左边的都比15小，在下面的都比15大（也可以从左下角18开始）

![](https://secure2.wostatic.cn/static/6xeDvbo9dAgHvsM6HFcDxv/image.png?auth_key=1711379579-dTWuqUUNnerjnfaZQqM5mz-0-f690f1e141180a7015de97e8baff1cbb)

# 19 搜索旋转排序数组

![](https://secure2.wostatic.cn/static/o2XfYeiKf7QCydaNtFPDjE/image.png?auth_key=1711379579-8f7PfngWKJqMHefWp4BvDx-0-73fb54a3c19d940b46080615107363cb)

![](https://secure2.wostatic.cn/static/8FMmPp6BRm3VsEB1X4Toz2/image.png?auth_key=1711379579-2w9s67e8BFWF8FV4Ys3nWM-0-67c520be712510cc6acd088b7ebc7ada)

# 20 求x的平方根

![](https://secure2.wostatic.cn/static/bVtyqgkZs9wLVkXEsdbYX8/image.png?auth_key=1711379579-vYYGNAPo1pGwwyZqmi9jWZ-0-592e2e101a40b5778895628b556137e7)

**解题思路**：直接用二分查找，查找的值为mid**2跟x比较

![](https://secure2.wostatic.cn/static/qV5xd9UujFGmkMpSzYqDpv/image.png?auth_key=1711379579-iafuM4RcRQQPLowmNWhKzr-0-a96774a17062fe7b287ccfa24379486d)

# 21 反转链表

![](https://secure2.wostatic.cn/static/tq2fEQgXXCG5iADDivk5JQ/image.png?auth_key=1711379589-pQiLS46Zt1srAqHKt3tHLi-0-181d9b3553b6d7aac998dad84dc83b82)

# 22 k个一组翻转链表

![](https://secure2.wostatic.cn/static/67kiYMwDHxjLRS8Agw9RRq/image.png?auth_key=1711379589-jMuJuARZJRnt789pontaxE-0-1684205af1a696d5ae27425f8fb38118)

**解题思路**：先统计节点个数，然后每k个翻转一次

![](https://secure2.wostatic.cn/static/bkXzNe5JE71dDFSYQg48fr/image.png?auth_key=1711379589-dqCNLyHWMK3VUrsx7hYu4D-0-d5cee85de372cc36c93a01075581ab5b)

# 23 回文链表

遍历链表，用一个栈存储，然后再次遍历链表，判断出栈的值是否相等

![](https://secure2.wostatic.cn/static/pCETWV25phn8Dg4t5J3g7y/image.png?auth_key=1711379589-4igFNASrG9j8bq2VAKsGHa-0-e2af8865392d70f7f9fe276e738a45e5)

# 24 合并有序链表

合并两个有序链表：

![](https://secure2.wostatic.cn/static/wBRJf3X6rwV9YsV67UwiuK/image.png?auth_key=1711379589-qiVYSDXn6KWrUdmVjpGfhd-0-4caf08ac1a5ed7dbd8100507515168e8)

合并k个链表：

解法1：可以使用最小堆，把所有元素进堆，然后依次出堆

解法2：先写合并两个链表的，然后依次合并

# 25 LRU缓存

![](https://secure2.wostatic.cn/static/7V9rXACUze98m9TqKtC9vv/image.png?auth_key=1711379589-mKhDa4PHzqnh7Qs5vHiupx-0-1b7b33f259b42041e385a5b7c51a62aa)

![](https://secure2.wostatic.cn/static/gu2TyYHQ1DTog7D6Zq85FV/image.png?auth_key=1711379589-dh9wKUDaqkZtnoTCDdxb7m-0-e5370abe4ff37df0c7e20894781c7d3b)

# 26 二叉树：遍历，最大深度，翻转，对称，层序遍历

**遍历**：用dfs()进行递归，中序遍历：

![](https://secure2.wostatic.cn/static/nD3BmDCQNq61ShsVsrPQV3/image.png?auth_key=1711379589-4qXzBeKWwcdaFcmx4Zr5be-0-e6cb628b7c5fa2b8395f51f294fafcc5)

**最大深度**：

![](https://secure2.wostatic.cn/static/aADfqMB7KbuPpp8j7wvkML/image.png?auth_key=1711379589-kwiuhxD2JLFFNXqEv18j4Z-0-e509cb8d6a98f65078f6da74e893ccd2)

**翻转**：

![](https://secure2.wostatic.cn/static/tQkdNRxQb3gTv8V3upqEuv/image.png?auth_key=1711379589-kdnmPQEwYztupUynsCwAJB-0-62e223212bab955d82c90c75dbb1b0cb)

**是否为轴对称二叉树**：

![](https://secure2.wostatic.cn/static/4UCE8Dm4d7eMx9ZYgiRQnJ/image.png?auth_key=1711379589-krunno24rHukhiqyHBZV8p-0-a3590977efd01e3d2c20980752a48d32)

**层序遍历**：二叉树的bfs()做法，在队列中用一个tmp记录每一层的值

![](https://secure2.wostatic.cn/static/jy5A4VSRtmqTgcwGTTzQjG/image.png?auth_key=1711379589-wMXDLgitxSDExrq7czwmqu-0-75f209d4397468f7a2a14ade58d2fae5)

# 27 二叉树的右视图

![](https://secure2.wostatic.cn/static/iHMn31i8bscQQR3gMCWuCa/image.png?auth_key=1711379589-pKkZFtEyR6EcZCvbUVz5AB-0-031a4ddfd17b53ea57ac2917db16a0d2)

解题思路：相当于取二叉树每层最后一个值，直接用bfs()做层序遍历

![](https://secure2.wostatic.cn/static/6WAKwMLmYzbSYdTRGT8BA5/image.png?auth_key=1711379589-aswS3AKTdmRjGjPU3hFE4c-0-7fd6dddcc555fd666130908733f6b667)

# 28 验证二叉搜索树

![](https://secure2.wostatic.cn/static/pXQhNyoYPZAphkjMRxMTdy/image.png?auth_key=1711379589-uq8RV8fMAdHLcJtQvsr2Ev-0-ee5d1889ae75a59762a2c90bb8b7b53b)

![](https://secure2.wostatic.cn/static/7XiNgfBNsRpo11UbzKbYrP/image.png?auth_key=1711379589-jotuwvhz5TywQfa6fY9Xue-0-bcd0b840e6bd89fcc58876fa8bb36f83)

# 29 二叉搜索树中第k个最小元素

![](https://secure2.wostatic.cn/static/6ZSK2bfsAoYWaszRrkfzsW/image.png?auth_key=1711379589-m71ZP4FnwXY8tqgesfFWUA-0-70af3044165379065b3f5935f877cdc8)

**解题思路**：二叉搜索树的中序遍历即为递增序列，直接用中序遍历找第k个元素

![](https://secure2.wostatic.cn/static/p1gckzkNH8zZ6zn76TwS6A/image.png?auth_key=1711379590-fT7EmrpS7oPoXQ3DvDRid5-0-58329384ea5d17e96986b516d19b53c3)

# 30 二叉树变成链表

![](https://secure2.wostatic.cn/static/4QUXq92n1BRQQa7tTHhukp/image.png?auth_key=1711379590-8mpX6RT1tRQyvFuLBJ9nYt-0-a4af9066c131c323979cd2f9c9d7f323)



![](https://secure2.wostatic.cn/static/9qwEaa5CQLvEvd4jQL87f5/image.png?auth_key=1711379590-vWZbQ7JnEETyhig6N4uF3z-0-cbafdf2b62f420b64050202d25bd18e7)

# 31 从前序和中序构造二叉树

![](https://secure2.wostatic.cn/static/oWb3VKCjc9FrTvd22LEoAw/image.png?auth_key=1711379590-hR98Bupnu8KkhFDi9RRHL5-0-3f48b9f1e94e8ad8f84dc878e010002a)

**解题思路**：前序遍历是‘根左右’，因此pretorder第一个元素一定整个树的根。由于题目说明了没有重复元素，因此我们可以通过val去inorder找到根在inorder中的索引i。
而由于中序遍历是‘左根右’，我们容易找到i左边的都是左子树，i右边都是右子树。

![](https://secure2.wostatic.cn/static/ffZGJtyd2iCfE7rBXWSr6H/image.png?auth_key=1711379590-evyrhzMr1RqNufs4kvQp9i-0-7aa7f5a5246d50da7b4d50efc8044d8e)

# 32 二叉树的最近公共祖先

![](https://secure2.wostatic.cn/static/cecCTPkmgNU3TprqH4FnqR/image.png?auth_key=1711379590-kGY1bMuCLzecy5yj9Emz11-0-5580f7ee25ff49b5198b0ec63c5ba8d7)

![](https://secure2.wostatic.cn/static/3cEu1ZyndCdWG4vnEVuZQd/image.png?auth_key=1711379590-5z7fPhxTusTn7J4VPcRc2a-0-84121bb34eeb7695e7f9cf32291ee6f1)

# 33 二叉树中的最大路径和

![](https://secure2.wostatic.cn/static/bjyNxyJzYsTeg1fRHygNQ9/image.png?auth_key=1711379591-jywanuSB7LfMWk9Bhreba9-0-40fe50a68095ce7ffa2bf235525695de)

![](https://secure2.wostatic.cn/static/uHTNh9Kb1rozQvqTkc4dvp/image.png?auth_key=1711379591-rAQ7LAuP6WK5E3LVdFiTKf-0-62d08aef224f1745fa5f54032fda4dde)

# 34 岛屿数量

![](https://secure2.wostatic.cn/static/fxMrG2adejpjHpQJnfoVT7/image.png?auth_key=1711379591-hcnBcqoYK3Sq3g52pwiQ27-0-9565f32f2e7e773da8b6aabef12c492f)

**解题思路**：用dfs()

![](https://secure2.wostatic.cn/static/ngEdymKuC12jnZiK51TeNw/image.png?auth_key=1711379591-vWL4ny3rLKA49hNVRuG4p5-0-08173e75eefcaa752f2232244d189088)

# 35 单词搜索

![](https://secure2.wostatic.cn/static/idWcd1aUkdL718iXrhpkhy/image.png?auth_key=1711379591-rotKecGhwscVpeaqEitiaT-0-198e829fe19c76fd3762d86028da033a)

**解题思路**：回溯算法一般用dfs()，用k来记录当前word中的字符，检查过矩阵过后将看过的值改成' ',然后检查上下左右位置。

![](https://secure2.wostatic.cn/static/jwgYWNPsicZ5T2qHhezfa9/image.png?auth_key=1711379591-eJdLrq4qxJC6LdFZqPmHwE-0-6b8a5fa8b61795926c952bde7df22e1a)

# 36 全排列

![](https://secure2.wostatic.cn/static/hTcHoQ4QRLibcM88V4svQa/image.png?auth_key=1711379591-qf7M4NrDhp3wf2DrQVTow7-0-6b0154b27417782c2a995e354726d346)

![](https://secure2.wostatic.cn/static/2ZYz87GWo3F3taXfd5KCpM/image.png?auth_key=1711379591-4BPssL5UW6E4Mt8cL8nH9J-0-b8485c2d9dc1c5f05b46c8d60ce60397)

# 37 括号生成

![](https://secure2.wostatic.cn/static/f2tNTCiKaxv6LRxUPbHyYs/image.png?auth_key=1711379591-xgDfdzxoNUmDTNKaJw87sg-0-3b21039cdd116141d01dd96236c804c3)

![](https://secure2.wostatic.cn/static/8MP8kg1oyxFKZTsiGteBLJ/image.png?auth_key=1711379591-gMbitKfQFv3KFpDG1neokb-0-7e4b7a5b39b9b4335b65154420fac908)

# 38 分割回文串

![](https://secure2.wostatic.cn/static/pKZnYi3zzodm7DS2nxKScb/image.png?auth_key=1711379592-8HdVkXuY4LtJajEAhEXFCE-0-211b07d8bb0a430b1b3259096366682b)

**解题思路**：回文子串的特点是str=str[::-1]：前后翻转后相等。可以把第一个字母当初单独回文串，然后通过回溯dfs往后找

![](https://secure2.wostatic.cn/static/3RQdUVWx4bVjZ7SFbKdNzN/image.png?auth_key=1711379592-soqeWu6d8ymtFtUjDjg65J-0-0e7b8a25a4b1bf509a56325ee89e98b7)

# 39 寻找两个正序数组的中位数



![](https://secure2.wostatic.cn/static/BcGvBvt3x5TCa8JhiUfg/image.png?auth_key=1711379592-qVV9WREhhyRbss1NAZkWo6-0-c37cd28b732aa093430dff043bb681b8)

# 40 字符串解码

![](https://secure2.wostatic.cn/static/gdxRH1hgfrow5xiaYfVuVW/image.png?auth_key=1711379592-e1yrtNg4UyVkJmfTorbVYw-0-7ab74a023bc35211e8689d887a4535ab)

解题思路：



# 41 数组中第k个最大元素

![](https://secure2.wostatic.cn/static/2NqzN79BxoJQLuNZwSJGia/image.png?auth_key=1711379592-28R6BKURsQWPScbWPxNLe2-0-843ad6a32d181a05b6640634c210605a)

**解题思路**：可以用最小堆进行排序然后取第k大的值, 或者快速排序取第k大的值

![](https://secure2.wostatic.cn/static/viqTG77hYZyfzXNFMdtryR/image.png?auth_key=1711379592-bm9UtdG3VBJhv9Wa695DYW-0-45633541517911969e100b57dff0b0cb)

# 42 前k个高频元素

![](https://secure2.wostatic.cn/static/9ewBbNYqxRUG86GYwfxCRf/image.png?auth_key=1711379592-jeokmKVhaZ9x1i26pxW9rt-0-b55f002b16d4a964177b450f996357cf)

**解题思路**：先用dict记录每个值出现的频率，然后按照频率值输入堆中，输出前k个高频的值

![](https://secure2.wostatic.cn/static/43FdoifhwvVaJiTwgMUFuf/image.png?auth_key=1711379592-253JmQAdGvKBoS1CDWZQvv-0-f3718dcefc1669d340db2f74a0cd6803)

# 43 买卖股票的最佳时机

![](https://secure2.wostatic.cn/static/i8vebk7FzSAk8CfHzJmjoJ/image.png?auth_key=1711379593-mccbN5az79o4xYJvZoGHxv-0-81dfc01089a6efe05959d59c81722c4c)

![](https://secure2.wostatic.cn/static/3UqRt4aTMUNaTWy4Z4fqGB/image.png?auth_key=1711379593-kAc52o3SjpZExFyvitNVXV-0-cd80301c05654a37fb9999398d26ab54)

# 44 跳跃游戏

![](https://secure2.wostatic.cn/static/pz2JCLfYKgVq9kkuURVLaP/image.png?auth_key=1711379593-dDjDSZqiXi1zMNnDoNKH9m-0-0305f7d875c41d30755e82171f18b31a)

**解题思路**：尽可能到达最远位置（贪心）。  如果能到达某个位置，那一定能到达它前面的所有位置。

![](https://secure2.wostatic.cn/static/bte5g8a7NTaBgQZ9WDccMY/image.png?auth_key=1711379593-3xbLBkAe2gjXSrrHtVFKb6-0-86eda5fd508cd8ea74d6f1f3d05bcb04)

# 45 最长递增子序列

![](https://secure2.wostatic.cn/static/8zPdP4KhMdTWuR62d9dy8D/image.png?auth_key=1711379593-rFER4oafhQy9CMro9RiYpn-0-2d241bae03cf1ff4212ac943dc5c501f)

![](https://secure2.wostatic.cn/static/capfwR41SW6AgCZVZRCmWi/image.png?auth_key=1711379593-igFqQFJW17fkyE4Nc1AShF-0-004d0609bde76586496aab5d472e53d3)

# 46 最长回文子串

![](https://secure2.wostatic.cn/static/koCecKxRXst8x2XM4GrPxC/image.png?auth_key=1711379593-kyMbfjd7PEPoXyKB7WJweP-0-00b78d15fbb79abe61d4c826a4bd4a2d)

**解题思路**：使用2维dp记录true和false，同时还需要记录回文串最长时的左端和最长长度

![](https://secure2.wostatic.cn/static/nwCGJEGPKJKSREHasvbcw/image.png?auth_key=1711379593-4E2wbkHuu4Lv3FiuANyBE8-0-44034ddcd0a90f7b2c852a09e7d7f133)

# 47 最长公共子序列

![](https://secure2.wostatic.cn/static/pgdrNqkWSusQLgE6RfdC73/image.png?auth_key=1711379594-janBmyrmTfwLqksRBWam8w-0-a59ffff87e2d088f65054d6c625ca258)

![](https://secure2.wostatic.cn/static/64si7D2GSSSBXPgpkudbdE/image.png?auth_key=1711379594-sq6aNtTr6ov42FfLNMAq9K-0-6f7774a8f6b364cf3999af411b1fccea)

# 48 编辑距离

![](https://secure2.wostatic.cn/static/t3sDQgddgF9k9MJgJsFFZr/image.png?auth_key=1711379594-euGubPG9Yo2GD6TQRZ3o5r-0-11fb5db702fb19d5edffb8334a345f6e)

**解题思路**：2维DP，`dp[i][j]` 代表 `word1` 到 `i` 位置转换成 `word2` 到 `j` 位置需要最少步数。其中，`dp[i-1][j-1]` 表示替换操作，`dp[i-1][j]` 表示删除操作，`dp[i][j-1]` 表示插入操作。

![](https://secure2.wostatic.cn/static/hXXndsQKcYph9abR7aiDc7/image.png?auth_key=1711379594-5JoCTNrWzRsfik8EVsxk6g-0-c08c77a1a6ac641a6b13d2aa00cca619)

# 49 正则表达式匹配

![](https://secure2.wostatic.cn/static/nryzcyytnnPK34SgY6X4GF/image.png?auth_key=1711379594-ej1HeLvQYCsSMPe8WEZPxL-0-93a4832474cf3d77fa48c6bc9b9343ee)

![](https://secure2.wostatic.cn/static/2QKyoxvsLVFUhx5mPRbNpM/image.png?auth_key=1711379594-b6gjnTGecvwVdwsY3rs234-0-666c29aef9b50b67515656f223a610b1)