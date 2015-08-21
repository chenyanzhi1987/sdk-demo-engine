## sdk-demo-engine

此项目用来展示云引擎和 SDK 的交互。需要结合 [LeanStorageDemo](https://github.com/leancloud/LeanStorage-Demo) 里的云引擎示例来学习。可以学习到：

* 如何撘一个简单的 LeanEngine 框架？
* 如何定义云函数？
* 如何处理云函数错误回调？
* 如何把 AVObject 对象传递给客户端？
* 如何用 beforeSave Hook？

核心代码为 [cloud.js](https://github.com/leancloud/sdk-demo-engine/blob/master/cloud.js) 。


云引擎介绍：

为了在服务端执行一些业务逻辑操作，你可以使用我们提供的 LeanEngine，编写 JavaScript 或者 Python 代码，并部署到我们的平台上。通过 LeanEngine，你可以拦截save请求，在 save object 之前或之后做一些事情；你也可以自定义业务函数，并通过 SDK 调用；你还可以调用部分第三方库来实现你的业务逻辑；甚至，你可以将整个网站架设在 LeanEngine 之上，我们提供了web hosting 服务。

## 文档

[LeanEngine 指南](https://leancloud.cn/docs/leanengine_guide-node.html)

[更多示例](https://github.com/leancloud/leancloud-demos#javascript])