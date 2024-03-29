# 1.6-常见时间复杂度

| 执行次数函数举例 | 阶 | 非正式术语 |
| :--- | :--- | :--- |
| 12 | O\(1\) | 常数阶 |
| 2n+3 | O\(n\) | 线性阶 |
| $$3n^2+2n+1$$  | O\(n2\) | 平方阶 |
| 5log2n+20 | O\(logn\) | 对数阶 |
| 2n+3nlog2n+19 | O\(nlogn\) | nlogn阶 |
| 6n3+2n2+3n+4 | O\(n3\) | 立方阶 |
| 2n | O\(2n\) | 指数阶 |

**注意，经常将log2n（以2为底的对数）简写成logn**

### 常见时间复杂度之间的关系 <a id="&#x5E38;&#x89C1;&#x65F6;&#x95F4;&#x590D;&#x6742;&#x5EA6;&#x4E4B;&#x95F4;&#x7684;&#x5173;&#x7CFB;"></a>

![&#x7B97;&#x6CD5;&#x6548;&#x7387;&#x5173;&#x7CFB;](https://jackkuo666.github.io/Data_Structure_with_Python_book/images/%E7%AE%97%E6%B3%95%E6%95%88%E7%8E%87%E5%85%B3%E7%B3%BB.bmp)

所消耗的时间从小到大

**O\(1\) &lt; O\(logn\) &lt; O\(n\) &lt; O\(nlogn\) &lt; O\(n2\) &lt; O\(n3\) &lt; O\(2n\) &lt; O\(n!\) &lt; O\(** $$n^n$$ **\)**

> 练习： 时间复杂度练习\( 参考算法的效率规则判断 \)  
> O\(5\)  
> O\(2n + 1\)  
> O\(n²+ n + 1\)  
> O\(3n³+1\)

