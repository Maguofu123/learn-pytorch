## day5
输出层的激活函数用σ() 表示，不同于隐藏层的激活函数h()（σ读作sigma）。
![image](https://user-images.githubusercontent.com/91414286/189105253-45c8c934-d057-4423-842e-e8ab594bca35.png)


恒等函数
![image](https://user-images.githubusercontent.com/91414286/189105371-10195ec6-b9f0-4f3f-9bb3-57ed7951bbe7.png)



softmax函数
![image](https://user-images.githubusercontent.com/91414286/189105345-a922d6fb-87b3-421c-8c6a-4bd8a5e6f418.png)


一般而言，神经网络只把输出值最大的神经元所对应的类别作为识别结果。
并且，即便使用softmax 函数，输出值最大的神经元的位置也不会变。因此，
神经网络在进行分类时，输出层的softmax 函数可以省略。在实际的问题中，
由于指数函数的运算需要一定的计算机运算量，因此输出层的softmax 函数
一般会被省略
