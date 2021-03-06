# 小白学JS 第一课总结 20170811

### 1.银行开户类比JS代码执行流程

银行开户流程
* 填写申请单
* 审核
* 发卡

具体开户业务

1.开户环境：提供一组服务，该服务包含接受申请、检验申请单信息和核对资格。提供内置服务和核心服务。
* 内置服务：为满足用户填写订单时提供的一组内部服务。
* 核心服务：涵盖预预处理和执行的服务，是银行的核心业务。预处理：在真正执行开户前进行信息检查的处理过程，以保证执行处理的效率。执行：执行开户操作的过程，操作完成后并返回想要的开户结果。

2.第三方服务：围绕开户服务，会有一系列银行之外的第三方服务供用户使用，以满足开户需求。

*JS运行环境框架*

* JS运行环境对应银行开户环境。
* JS代码对应用户。
* 第三方服务对应JS第三方库，来满足JS代码更多的需求。

***

### 2.运行环境

JS的运行环境由内置库、V8引擎组成

JS有两大类运行环境：
* 浏览器环境和Nodejs环境：两者最大的区别在于内置库和第三方库的不同。

***

### 3.V8引擎

在JS中，V8引擎是把开发人员写的 JS 代码转换成高效、优化的代码的解释/编译器，负责预处理和执行，具体处理过程处于“黑箱”阶段。

***

### 4.编译器/解释（执行）器

* 编译型语言：代码需要一个专门的编译过程，将代码翻译成机器语言，其优点是运行效率高，缺点是开发效率低。
* 解释性语言：代码边执行边翻译，优点是开发效率高，缺点是运行效率低。

*JS属于解释性语言，代码输入后，由编译器/解释器进行分析语法、分析词法、分析语义、优化代码、解释代码、执行代码。*

***

### 5.内置库

JS内置的一系列打包好的工具，其类型众多、功能丰富，帮助开发者简化和优化开发过程。

***

### 6.第三方库

和内置库的功能一样，帮助开发者简化开发过程，优化产品，但并不属于JS内置，需要额外下载。

### 7.学习JS的正确姿势

* 掌握编程语言，用编程方式调用服务来解决问题
* 了解和掌握重要的服务能力，使其能服务我们的需求
* 比较服务/技术之间的差异性,用最好的方式实现你的业务

***

*撸起袖子就是干，紧跟老师步伐，记录错误，有报错问google！*

