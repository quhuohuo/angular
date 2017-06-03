# angular
## ng-app 指令
#### ng-app 指令定义了 AngularJS 应用程序的 根元素。
#### ng-app 指令在网页加载完毕时会自动引导（自动初始化）应用程序。
#### 稍后您将学习到 ng-app 如何通过一个值（比如 ng-app="myModule"）连接到代码模块。

## ng-init 指令
#### ng-init 指令为 AngularJS 应用程序定义了 初始值。
#### 通常情况下，不使用 ng-init。您将使用一个控制器或模块来代替它。

## ng-model 指令
#### ng-model 指令 绑定 HTML 元素 到应用程序数据。
#### ng-model 指令也可以：
* 为应用程序数据提供类型验证（number、email、required）。
* 为应用程序数据提供状态（invalid、dirty、touched、error）。
* 为 HTML 元素提供 CSS 类。
* 绑定 HTML 元素到 HTML 表单。

## ng-repeat 指令
#### ng-repeat 指令对于集合中（数组中）的每个项会 克隆一次 HTML 元素

## 创建自定义的指令
#### 
     除了 AngularJS 内置的指令外，我们还可以创建自定义指令。你可以使用 .directive 函数来添加自定义的指令。  
     要调用自定义指令，HTML 元素上需要添加自定义指令名。  
     使用驼峰法来命名一个指令， runoobDirective, 但在使用它时需要以 - 分割, runoob-directive:

## restrict 值可以是以下几种
* E 作为元素名使用
* A 作为属性使用
* C 作为类名使用
* M 作为注释使用
