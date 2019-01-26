# 2019LeetcodeFB

> [1. Two Sum (HashMap，注意要返回的是索引)] 
> 
> [2. Add Two Numbers (用链表表示两个数字，然后依次相加，最后的结果也是用链表来表示，注意长短不一致的情况就行了，还有最后的进位)] 
> 
> [3. Longest Substring Without Repeating Characters (最长的没有重复字符的substring，On，用字典记录当前符合条件子串中每个字符的位置，然后如果碰到重复的就更新result和子串的长度)] 
> 
> [6. ZigZag Conversion](https://github.com/AlexQianYi/2019LeetcodeFB/blob/master/6.%20ZigZag%20Conversion.md) 把string转换成Z字型
> 
> [7. Reverse Integer (把一个32位的int翻转，不过要注意溢出的情况，直接转换成字符串就行了)] 
> 
> [8. String to Integer (要求贼多，刚开始空格不考虑，-或者+或者数字开始转换，遇到空格或者其他非数字的停止，溢出返回最大或者最小)] 
> 
> [9. Palindrome Number (看一个数字是不是对称的，转换成字符串就行了)] 
> 
> [11. Container With Most Water (看容器的最大的容量，左右两个指针，从最左边和最右边开始往中间移动，移动高度较小的那一个)] 
> 
> [13. Roman to Integer (罗马数字转换成整数，HashMap，从右向左遍历，如果是从小到大的字母顺序那么相加就行了，如果有大到小那么减一下小的)] 
> 
> [14. Longest Common Prefix (一个数组里面都是string，然后求最长的公共前缀，直接对数组排序，然后比较第一个元素和最后一个元素的最长公共前缀就行了)] 
> 
> [15. 3Sum (一个从前往后，另外两个同时从左从右)] 
> 
> [17. Letter Combinations of a Phone Number (典型的DFS问题，一眼看穿！)] 
> 
> [18. 4Sum (和3Sum基本一样的)] 
> 
> [20. Valid Parentheses (括号匹配问题，就是栈，维护一个list，按顺序保存左括号就行了，pop)] 
> 
> [21. Merge Two Sorted Lists (链表合并问题，没啥好说的)] 
> 
> [23. Merge K Sorted Lists (可以用分治，一半一半的合并，最基础的还是21)] 
> 
> [26. Remove Duplicates from Sorted Array (把重复的数字移到数组的最后面然后返回修改后的没有重复数字的数组的长度，两个指针就行了)] 
> 
> [28. Implement strStr() (返回子串的位置)] 