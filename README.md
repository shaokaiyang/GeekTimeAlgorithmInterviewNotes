# GeekTimeAlgorithmInterviewNotes
**记录在《极客时间》平台上《算法面试通关40讲》专栏的学习笔记**  
**作者信息：覃超 前Facebook工程师，卡内基梅隆大学计算机硕士**  
**课程海报如下：欢迎扫描右下方二维码订阅（有优惠哦）**  

![课程海报](./picture/algorithminterview.jpg ) 

# 目录
* [第1讲 合格程序员第一步：算法与数据结构](#1)
* [第2讲 如何事半功倍的学习算法与数据结构](#2)
* [第3讲 如何计算算法复杂度](#3)
* [第4讲 如何通过LeetCode来进行算法题目练习](#4)
* [第5讲 理论讲解：数组&链表](#5)
* [第6讲 面试题：翻转一个单链表&判断链表是否有环](#6)
* [第7讲 理论讲解：堆栈&队列](#7)
* [第8讲 面试题：判断括号字符串是否有效](#8)
* [第9讲 面试题：用队列实现栈&用栈实现队列](#9)
* [第10讲 理论讲解：优先队列](#10)
* [第11讲 面试题：返回数据流中的第K大元素](#11)
* [第12讲 面试题：返回滑动窗口中的最大值](#12)
* [第13讲 理论讲解：哈希表](#13)
* [第14讲 面试题：有效的字母异位词](#14)
* [第15讲 面试题：两数之和](#15)
* [第16讲 面试题：三数之和](#16)
* [第17讲 理论讲解：树&二叉树&二叉搜索树](#17)
* [第18讲 面试题：验证二叉搜索树](#18)
* [第19讲 面试题：二叉树&二叉搜索树的最近公共祖先](#19)
* [第20讲 理论讲解：二叉树遍历](#20)
* [第21讲 理论讲解：递归&分治](#21)
* [第22讲 面试题：Pow（x,n）](#22)
* [第23讲 面试题：求众数](#23)
* [第24讲 理论讲解：贪心算法](#24)
* [第25讲 面试题：买卖股票的最佳时机](#25)
* [第26讲 理论讲解：广度优先搜索](#26)
* [第27讲 理论讲解：深度优先搜索](#27)
* [第28讲 面试题：二叉树层次遍历](#28)
* [第29讲 面试题：二叉树的最大和最小深度](#29)
* [第30讲 面试题：生成有效括号组合](#30)
* [第31讲 理论讲解：剪枝](#31)
* [第32讲 面试题：N皇后问题](#32)
* [第33讲 面试题：数独问题](#33)
* [第34讲 理论讲解：二分查找](#34)
* [第35讲 面试题：实现一个求解平方根的函数](#35)
* [第36讲 理论讲解：字典树](#36)
* [第37讲 面试题：实现一个字典树](#37)
* [第38讲 面试题：二维网格中的单词搜索问题](#38)
* [第39讲 理论讲解：位运算](#39)
* [第40讲 最后一些经验分享](#40)
* [第41讲 面试题：2的幂次方问题&比特位计数问题](#41)
* [第42讲 面试题：N皇后问题的另一种解法](#42)
* [第43讲 理论理解：动态规划（上）](#43)
* [第44讲 理论理解：动态规划（下）](#44)
* [第45讲 面试题：爬楼梯](#45)
* [第46讲 面试题：三角形的最小路径和](#46)
* [第47讲 面试题：乘积最大子序列](#47)
* [第48讲 面试题：股票买卖系列](#48)
* [第49讲 面试题：最长上升子序列](#49)
* [第50讲 面试题：零钱兑换](#50)
* [第51讲 面试题：编辑距离](#51)
* [第52讲 理论讲解：并查集](#52)
* [第53讲 面试题：岛屿的个数&朋友圈（上）](#53)
* [第54讲 面试题：岛屿的个数&朋友圈（下）](#54)
* [第55讲 理论讲解：LRU Cache](#55)
* [第56讲 面试题：设计和实现一个LRU Cache缓存机制](#56)
* [第57讲 理论讲解：布隆过滤器](#57)
* [第58讲 课程重点回顾](#58)
* [第59讲 FAQ答疑&面试中切题四件套](#59)
* [第60讲 回到起点：斐波拉契数列](#60)
* [第61讲 白板实战番外篇：斐波拉契数列](#61)
* [第62讲 最后一些经验分享](#62)
* [完结](#99)

# 正文
<h2 id="1">第1讲 合格程序员第一步：算法与数据结构</h2>

每天的工作计划使用优先级队列的方式进行计划；  
加密货币中有大量的算法和数据结构，区块使用LinkedList，区块内使用二叉树来表示交易信息；  
编程是内功的修炼；  
算法与数据结构有趣且实用；  

<h2 id="2">第2讲 如何事半功倍的学习算法与数据结构</h2>

推荐书籍：《异类不一样的成功启示录》切碎知识点；刻意练习；获得反馈  
明确题目意识；找到所有可能的解法；编码实现；进行测试；  

<h2 id="3">第3讲 如何计算算法复杂度</h2>

时间复杂度：常数，对数，线性，平方，立方，指数，阶乘  
斐波那契数列的时间复杂度为O（2^n）  
Master Theorem  二分查找O(logn),二叉树遍历O(n),二维矩阵查找O(n)  

<h2 id="4">第4讲 如何通过LeetCode来进行算法题目练习</h2>

坚持刻意练习；练习缺陷弱点地方；不舒服，不爽和枯燥；  

<h2 id="5">第5讲 理论讲解：数组&链表</h2>

数组：内存中连续的存储区域，根据索引O(1)查找，插入和删除操作O（n）  
链表：很多的插入和删除操作，不知道有多少个元素，查找是O(n)，单链表和双链表  

<h2 id="6">第6讲 面试题：翻转一个单链表&判断链表是否有环</h2>

题目列表:  
206翻转一个链表  
```python
def reverseList(self, head):
    cur, prev = head, None
    while cur:
        # 一次性赋值，先计算好右边一次性赋值
        cur.next, prev, cur = prev, cur, cur.next
    return prev
```
24 对一个链表进行两两翻转
```python
def swapPairs(self, head)
    pre, pre.next = self, head
    while pre.next and pre.next.next:
        a = pre.next
        b = a.next
        pre.next, b.next, a.next = b, a, b.next
        pre = a
    return self.next
```
141 判断链表是否有环  
```
def hasCycle(self, head)
    fast = slow = head
    while slow and fast and fast.next:
        slow = slow.next
        fast = fast.next.next
        if slow if fast:
            return Ture
    return False
```
<h2 id="7">第7讲 理论讲解：堆栈&队列</h2>

栈：先进后出；查找O(n),插入删除O（1）  
队列：先进先出；查找O(n),插入删除O（1）  
20 判断括号是否合法  栈空O(n)
```
def isValid(self, s):
    stach = []
    paren_map = {')':'(',']':'[','}':'{'}
    for c in s:
        if c not in paren_map:
            stack.append(c)
            //新进入一个符号栈是空的或者与栈顶元素不匹配则false
        elif not stack or paren_map[c] != stack.pop():
            return False
    return not stack
    
public boolean isValid(String s){
    int length;
    do{
        length = s.length();
        s = s.replace("()", "").replace("[]","").replace("{}","");
    }while(length != s.length());
    return s.length() == 0;
}
```

<h2 id="8">第8讲 面试题：判断括号字符串是否有效</h2>

1.左括号直接压进栈；   
2.右括号如果栈不为空与栈顶匹配则出栈；  
3.栈空则说明合法  

<h2 id="9">第9讲 面试题：用队列实现栈&用栈实现队列</h2>

栈实现队列：使用两个栈，输入栈进行数据输入，输出栈输出数据；  
进行输出时判断输出栈是否有元素，如果没有就将输入栈全部放入输出栈；  
队列实现栈：两个队列，一个入队列一个临时队列，在进行数据输出时将除了队列底部最后一个数据留下外，
其他数据放入临时队列，数据读取完之后再将临时队列的元素放入原队列。  

<h2 id="10">第10讲 理论讲解：优先队列</h2>

优先队列的实现方式：
1. heap（二叉树，多项式堆，斐波那契堆）  
2. 二叉搜索树
二叉堆（最小最大的数据在最上面）合并O（n），删除O（logn）  

<h2 id="11">第11讲 面试题：返回数据流中的第K大元素</h2>

703 实时返回第K大元素
1.每次保存K个最大值，每次进行更新，需要排序O(nklogn)  
2.维护一个size为k的小顶堆  O（nlogk）  
```python 
class KthLargest{
final PriorityQueue<Integer> q;
final int k ;
public KthLargest(int k , int[] a){
    this.k =k;
    q = new PriorityQueue<>(k);
    for(int n : a){
        add(n);
    }
    public int add(int k ){
        if(q.size() < k){
            q.offer(n);
        }else if(q.peek < n){
            q.poll();
            q.offer(n);
        }
        return q.peek;
    }
}
```

<h2 id="12">第12讲 面试题：返回滑动窗口中的最大值</h2>

239 滑动窗口最大值   
1. 维护一个大顶堆，每次最大值就是堆顶元素；O(nlogk)   
2. 双端队列， k个元素进入队列，进入队列时如果前面数都比该数小就出队列，保证区间
最左端是最大值；  

```python
def maxSlidingWindow1(self, nums, k){
    if not nums : return []
    window, res = [],[]
    for i, x in enumerate(nums):
        if i>= k and window[0] <= i-k:
            window.pop(0)
        while window and nums[window[-1]] <= x:
            window.pop()
        window.append(i)
        if(i >= k-1):
            res.append(nums[window[0]])
    return res
}
```

<h2 id="13">第13讲 理论讲解：哈希表</h2>

1.哈希表，哈希函数，哈希冲突（拉链法）  
2.map表示映射关系【HashMap vs TreeMap】  
3.set里面的元素不重复<哈希表或者二叉树>HashSet(O(1)) vs TreeSet(二叉树（O（logn））)  
4.list可以重复

<h2 id="14">第14讲 面试题：有效的字母异位词</h2>

242 有效的字母异位词 “rat”  "art"  
1. sort 然后进行比较  O（nlogn）  
2. map 计数{letter:count}  O(n)  

```
def isAnagram3(self, s, t)
    return sorted(s)  == sorted(t)
    
def isAnagram2(self, s, t)
    dic1, dic2 = {}, {}
    for item in s :
        dic1[item] = dic1.get(item, 0) +1;
    for item in s :
            dic2[item] = dic2.get(item, 0) +1;
    return dic1 == dic2
    
def isAnagram1(self, s, t)
    dic1, dic2 = [0]*26, [0]*26
    for item in s :
        dic1[ord(item) - ord('a')] += 1 
        
    for item in s :
            dic2[ord(item) - ord('a')] += 1
    return dic1 == dic2    
```

<h2 id="15">第15讲 面试题：两数之和</h2>

1.暴力搜索  O（n^2）  
2.构建hashmap，可以一次性先放进去也可以走着放着。  

<h2 id="16">第16讲 面试题：三数之和</h2>

15 三数和
18. 四数和
1. 暴力循环 O（n^3）  
2. SET集合，枚举a,b，在set里面查找（-a-b）  
3. 先排序再找，枚举a,在剩下的数组中维护两个指针（left,right），
不断从两边向中间夹, sum(a,b,c)>0 right--;sum(a,b,c)<0 left++;  

```
def thressSum(self, nums):
    if len(nums) < 3:
        return []
    nums.sort()
    res = set()
    for i,v in enumerate(nums[:2]):
        if i>=1 and v == nums[i-1]:
            continue
        d = {}
        for x in nums[i+1:]:
            if x not in d:
                d[-v-x] = 1
            else:
                res.add((v, -v-x, x))
    return map(list, res)
```

<h2 id="17">第17讲 理论讲解：树&二叉树&二叉搜索树</h2>

1.树：特殊的链表  
2. 二叉树：只有两个孩子  
3. 二叉搜索树：左子树<根，根> 右子树  O（logn）

<h2 id="18">第18讲 面试题：验证二叉搜索树</h2>

98 验证二叉搜索树  
1. 中序遍历  左子树  根  右子树，是升序的 O（n）  
2. 递归方式，max<-node.left;min<-node.right;max<root;min>root; O(N)  

```
def isValidBST(self, root):
    inorder = self.inorder(root)
    return inorder == list(sorted(set(inorder)))
def inorder (self, root):
    if root is none:
        return []
    return self.inorder(root.left) + [root.val] + self.inorder(root.right)  
    
def isValidBST(self, root):
    self.prev = None
    return self.helper(root)
def helper(self,root):
    if root is None:
        return True
    if not self.helper(root.left):
        return False
    if self.prev and self.prev.val >= root.val
        return False
     self.prev = root
     return self.helper(root.right)
     
public boolean isValid(TreeNode root, Integer min , Integer max){
    if(root ==  null) return ture;
    if(min  != null && root.val <= min ) return false;
    if(max != null && root.val >- max)  return false;
    return isValid(root.left,min,root.val) && isValid(root.right,root.val,max);
```

<h2 id="19">第19讲 面试题：二叉树&二叉搜索树的最近公共祖先</h2>
<h2 id="20">第20讲 理论讲解：二叉树遍历</h2>
<h2 id="21">第21讲 理论讲解：递归&分治</h2>
<h2 id="22">第22讲 面试题：Pow（x,n）</h2>
<h2 id="23">第23讲 面试题：求众数</h2>
<h2 id="24">第24讲 理论讲解：贪心算法</h2>
<h2 id="25">第25讲 面试题：买卖股票的最佳时机</h2>
<h2 id="26">第26讲 理论讲解：广度优先搜索</h2>
<h2 id="27">第27讲 理论讲解：深度优先搜索</h2>
<h2 id="28">第28讲 面试题：二叉树层次遍历</h2>
<h2 id="29">第29讲 面试题：二叉树的最大和最小深度</h2>
<h2 id="30">第30讲 面试题：生成有效括号组合</h2>
<h2 id="31">第31讲 理论讲解：剪枝</h2>
<h2 id="32">第32讲 面试题：N皇后问题</h2>
<h2 id="33">第33讲 面试题：数独问题</h2>
<h2 id="34">第34讲 理论讲解：二分查找</h2>
<h2 id="35">第35讲 面试题：实现一个求解平方根的函数</h2>
<h2 id="36">第36讲 理论讲解：字典树</h2>
<h2 id="37">第37讲 面试题：实现一个字典树</h2>
<h2 id="38">第38讲 面试题：二维网格中的单词搜索问题</h2>
<h2 id="39">第39讲 理论讲解：位运算</h2>
<h2 id="40">第40讲 面试题：统计位1的个数</h2>
<h2 id="41">第41讲 面试题：2的幂次方问题&比特位计数问题</h2>
<h2 id="42">第42讲 面试题：N皇后问题的另一种解法</h2>
<h2 id="43">第43讲 理论理解：动态规划（上）</h2>
<h2 id="44">第44讲 理论理解：动态规划（下）</h2>
<h2 id="45">第45讲 面试题：爬楼梯</h2>
<h2 id="46">第46讲 面试题：三角形的最小路径和</h2>
<h2 id="47">第47讲 面试题：乘积最大子序列</h2>
<h2 id="48">第48讲 面试题：股票买卖系列</h2>
<h2 id="49">第49讲 面试题：最长上升子序列</h2>
<h2 id="50">第50讲 面试题：零钱兑换</h2>
<h2 id="51">第51讲 面试题：编辑距离</h2>
<h2 id="52">第52讲 理论讲解：并查集</h2>
<h2 id="53">第53讲 面试题：岛屿的个数&朋友圈（上）</h2>
<h2 id="54">第54讲 面试题：岛屿的个数&朋友圈（下）</h2>
<h2 id="55">第55讲 理论讲解：LRU Cache</h2>
<h2 id="56">第56讲 面试题：设计和实现一个LRU Cache缓存机制</h2>
<h2 id="57">第57讲 理论讲解：布隆过滤器</h2>
<h2 id="58">第58讲 课程重点回顾</h2>
<h2 id="59">第59讲 FAQ答疑&面试中切题四件套</h2>
<h2 id="60">第60讲 回到起点：斐波拉契数列</h2>
<h2 id="61">第61讲 白板实战番外篇：斐波拉契数列</h2>
<h2 id="62">第62讲 最后一些经验分享</h2>
<h2 id="99">完结</h2>
   
## 觉得有价值 感谢支持
![赞赏码](./picture/AppreciationCode.jpg ) 
