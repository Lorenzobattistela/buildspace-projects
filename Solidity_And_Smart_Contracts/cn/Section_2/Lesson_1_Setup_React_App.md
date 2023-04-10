💻 设置客户端
------------------

现在是时候开始在我们的网站上工作了! 我们的合约非常简单，但还是让我们尽快了解我们的前端如何与合约进行交互吧！

所以，可以有100种不同的方法来设置并部署一个基础的react项目。我将在这里向你展示如何在10分钟内完成这个工作，事成之后你将拥有一个完全部署的react应用并拥有自己的域名等其他一切功能。

🤯 Replit
---------

**注意: 你不需要使用replit来建立+部署你的网站。 如果你想使用create-react-app + Vercel/Heroku/AWS -- 那也完全可以。 [这里](https://github.com/buildspace/waveportal-starter-project) 是一个指向基本 repo 的链接，你可以克隆并在本地工作。**

我们将使用 [Replit](https://replit.com/~)! 它是一个基于浏览器的集成开发环境，可以让我们轻松地从浏览器构建并部署网络应用，它简直太合适了！你不需要建立一个完整的本地环境，也不需要写命令进行部署，而是直接把它交给我们。

在继续之前，先在Replit上建立一个账户。

我已经创建了一个基本的react项目，你可以在Replit **fork** 它. **直接点击 [这里](https://replit.com/@adilanchian/waveportal-starter-project?v=1)，然后在页面右侧你可以看见"Fork" 按钮.** 请确保你已经登录了之后再点击它。 你会神奇地在浏览器里克隆我的repo和完整IDE来处理代码。一旦它停止加载并向你显示一些代码，点击顶部的 "运行 "按钮。这在第一次可能需要2-3分钟。基本上，Replit正在启动你的项目并将其部署到一个实际的域名中。

**请注意: 当你浏览这个项目时，你可能会注意到，我们正在引用`.js`文件， 你将需要使用`.jsx`扩展名来代替! Replit有一些性能上的缺陷，需要你使用`.jsx`文件扩展名:).**。 

我做了一个快速上手视频，介绍了如何在Replit上编辑代码，部署并开启dark模式。请看：
[Loom](https://www.loom.com/share/8e8f47eacf6d448eb5d25b6908021035)

🦊 Metamask
-----------

太棒了，我们有了一个**部署的**React项目，现在可以轻松地工作。这很简单:)。

接下来我们需要一个Ethereum钱包。有一堆这样的钱包，但是，对于这个项目，我们将使用Metamask。下载浏览器扩展并设置你的钱包 [这里](https://metamask.io/download.html). 即使你已经有了另一个钱包供应商，现在就使用Metamask吧。

为什么我们需要Metamask？嗯……我们需要能够在我们的智能合约上调用住在区块链上的函数。而且，为了做到这一点，我们需要有一个钱包里面有我们的以太坊地址和私钥。

**但是，我们需要一些东西来连接我们的网站和钱包，这样就可以安全地将钱包凭证传递给网站，然后使用这些凭证来调用我们的智能合约。你需要有有效的凭证来访问智能合约上的功能。**

这几乎就像授权认证。我们需要一些东西来 "登录 "区块链，然后使用这些登录凭证从我们的网站发出API请求。

因此，请继续设置这一切吧! 他们的设置流程是相当不言自明的:)。

🚨 在你点击 "下一课 "之前
-------------------------------------------

*注意：如果你不这样做，法尔扎会很伤心的:(。*

分享一个你的网站链接，并在#progress中发布它。把CSS和文本改成你想要的样子。也许你想让它变得更有色彩？也许你不关心潮流，你想做一个去中心化的Twitter克隆？做任何你想做的事，这是你的应用程序:)。