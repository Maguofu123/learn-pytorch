## day 7
**构建层**
*nn.Module*

`nn.Sequential()
nn.ReLU()
nn.Linear()`

*函数 F*

`F.relu`

**访问参数**
`net.state_dict()
net.bias.data
net.weight`

**初始化**
`nn.init.normal_(m.weight)
nn.init.zeros_()
nn.init.constant_()
nn.init.xavier_uniform_()`

`net.apply()`

**参数绑定**
通过初始化一个层实例
例如`shared = nn.Linear(2, 3)`

**读写保存**
`torch.load`
`torch.save`
