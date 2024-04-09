---
prev: true
next: true
description: 致命公司模组社区使用的开源方法的基本概述。
---

# 开源与道德

## 什么是开源？

开源意味着代码是公开可用的，可供任何人使用、编辑和分发。 它促进了软件开发的协作和公共方法。 然而，在开发开源软件时，有许多重要的事情需要考虑。

### 许可

_没有_许可的 GitHub 仓库**不是**开源的：

> 如果没有许可，就会默认实施版权法，因此你会保留对你的源代码的所有权利，任何人都不能复制、分发你的工作或创建其派生作品。
>
> _来源：https\://docs.github.com/zh/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository#choosing-the-right-license_

这意味着，如果你真的想正确地开源你的模组，就必须选择一个开源许可。
这可能听上去很吓人，但实际上不一定如此。 GitHub 创建了一个非常简易且美观的网站来查找适合你项目的许可：https\://choosealicense.com/

:::warning
**义不容辞，“我们不是法律家”。 我们对这些许可的解释主要基于 `choosealicense`
网站，以及个人经验。**
:::

我们建议为模组使用以下两个许可之一：

- [GNU General Public License v3.0](https://choosealicense.com/licenses/gpl-3.0/) -- 该许可的主要好处是，任何使用你的模组代码的人（无论是衍生版本、更新版本，还是在其他游戏中使用）都_必须_使用该许可。 这意味着你的作品和任何衍生作品都将保持开源。 也意味着人们无法攫取你的作品并创建一个不公开代码的版本，也意味着即使你对它失去了兴趣，社区也将永远能够在你的作品基础上继续发展，并让你的模组保持活力。
- [MIT License](https://choosealicense.com/licenses/mit/) -- 这是 GNU 通用公共许可的一个更为宽松的版本。 它_还_允许用户创建你模组的_闭源_版本。 这意味着用户无需公开共享其更新的代码。 但是，他们必须保留原始许可的版权声明，并随时提供。

### 健康合作

在用户互相帮助下，模组社区就会蓬勃发展。 将你的模组开源意味着目前（和未来）的模组制作者可以从你当前的作品中学习，甚至在你离开社区后继续更新你的模组。

不过，在这方面必须遵守道德规范。 我们知道模组社区可能会竞争激烈。 请勿盗用代码并将其视为自己的代码 - 请务必正确注明出处。

同样，当其他用户帮你修复漏洞，并希望提交拉取请求时，请接受拉取请求，而非独自去修复和落实 - 这样做会给他们带来一定的荣誉，同时也能培养一个互帮互助的社区。