* 参考资料
  *  马尔可夫过程的概念 https://zhuanlan.zhihu.com/p/31926943 
  *  第三章 马尔可夫链  http://www.math.zju.edu.cn/attachments/2018-05/01-1525966614-37031.pdf
  *  理解Markov假设
 https://blog.csdn.net/ybdesire/article/details/79294268
  * https://www.slideserve.com/karen-lucas/5
  * https://wenku.baidu.com/view/0b32f4f04693daef5ef73d9e.html
  * 
* 定义：
  * 随机过程$\{X(t), \enspace t \in T \}$，如果对于任意取定参数 $t_1 \lt t_2 \lt t_3 \lt ... \lt t_n$，有
  $$
    \begin{aligned}
    P\{X(t_n) \le x_n  | X(t_1)=x_1,X(t_2)=x_2,...,X(t_{n-1})  \} \\
    = P\{X(t_n) \le x_n | X(t_{n-1})=x_{n-1} \} \\
    \end{aligned}
  $$

