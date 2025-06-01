# Claude 现在可以连接到你的世界

今天我们宣布推出集成功能（Integrations），这是一种将你的应用程序和工具连接到 Claude 的新方式。我们还在扩展 Claude 的[研究](https://www.anthropic.com/news/research)功能，推出了一个高级模式，可以搜索网络、你的 Google Workspace，以及现在的集成功能。Claude 可以在提供带有引用的综合报告之前进行长达 45 分钟的研究。除了这些更新，我们还为所有付费计划的 Claude 用户在全球范围内提供网络搜索功能。

## 集成功能

去年 11 月，我们推出了[模型上下文协议](https://www.anthropic.com/news/model-context-protocol)（MCP）——一个连接 AI 应用程序与工具和数据的开放标准。到目前为止，MCP 的支持仅限于通过本地服务器的 Claude Desktop。今天，我们推出了集成功能，允许 Claude 与网络和桌面应用程序中的远程 MCP 服务器无缝协作。开发者可以构建和托管增强 Claude 功能的服务器，而用户可以发现并连接任意数量的这些服务器到 Claude。

当你将工具连接到 Claude 时，它会获得关于你工作的深层上下文——理解项目历史、任务状态和组织知识——并且可以在每个界面上采取行动。Claude 成为一个更有见识的协作者，帮助你在一个地方执行复杂项目，并在每一步都提供专家协助。

首先，你可以从 10 个热门服务的集成中进行选择，包括 [Atlassian 的 Jira 和 Confluence](https://www.atlassian.com/platform/remote-mcp-server)、[Zapier](https://zapier.com/mcp)、[Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare/tree/main)、Intercom（[MCP 服务器](https://mcp.intercom.com/sse)）、[Asana](https://developers.asana.com/docs/using-asanas-model-control-protocol-mcp-server)、Square（[MCP 服务器](https://mcp.squareup.com/sse)）、[Sentry](https://docs.sentry.io/product/sentry-mcp/)、[PayPal](https://www.paypal.ai/)、[Linear](https://linear.app/changelog/2025-05-01-mcp) 和 [Plaid](https://api.dashboard.plaid.com/mcp/sse)——未来还会有更多来自 Stripe 和 GitLab 等公司的集成。开发者也可以使用我们的文档或像 [Cloudflare](https://blog.cloudflare.com/remote-model-context-protocol-servers-mcp/) 这样提供内置 OAuth 认证、传输处理和集成部署的解决方案，在短短 30 分钟内创建自己的集成。

每个集成都大大扩展了 Claude 的能力。例如，Zapier 通过预构建的工作流连接数千个应用程序，自动化整个软件堆栈的流程。通过 [Zapier 集成](https://zapier.com/blog/zapier-mcp-guide/)，Claude 可以通过对话访问这些应用程序和你的自定义工作流——甚至可以自动从 HubSpot 提取销售数据并基于你的日历准备会议简报。

通过访问 Atlassian 的 Jira 和 Confluence，Claude 可以与你协作构建新产品，更有效地管理任务，并通过同时总结和创建多个 Confluence 页面和 Jira 工作项来扩展你的工作。

连接 Intercom 以更快地响应用户反馈。Intercom 的 AI 代理 Fin 现在是一个 MCP 客户端，可以在用户报告问题时采取诸如在 Linear 中提交错误等行动。与 Claude 聊天以识别模式并使用 Intercom 的对话历史和用户属性进行调试——在一次对话中管理从用户反馈到错误解决的整个工作流。

## 高级研究

我们正在推出几个新的更新，以在我们最近发布的[研究](https://www.anthropic.com/news/research)功能基础上进行构建。Claude 现在可以在数百个内部和外部来源中进行更深入的调查，在 5 到 45 分钟内提供更全面的报告。

通过切换研究按钮时可用的新复杂研究能力，Claude 将你的请求分解为更小的部分，深入调查每个部分，然后编制一份综合报告。虽然大多数报告在 5 到 15 分钟内完成，但对于更复杂的调查，Claude 可能需要多达 45 分钟——这通常需要数小时的手动研究工作。

我们还扩展了 Claude 的数据访问。我们推出了支持网络搜索和 Google Workspace 的研究功能，但现在通过集成功能，Claude 还可以搜索你连接的任何应用程序。当使用 Mac 或 Windows 的 Claude Desktop 应用程序时，这包括 MCP 连接的本地系统。

当 Claude 从来源整合信息时，它提供直接链接到原始材料的清晰引用。这种透明性确保你可以放心地使用 Claude 的研究发现，确切知道每个洞察的来源。

## 开始使用

集成功能和高级研究现在在 Max、Team 和 Enterprise 计划中以测试版形式提供，很快也将在 Pro 计划中提供。网络搜索现在已向所有 [Claude.ai](http://claude.ai) 付费计划全球提供。有关开始使用集成功能、MCP 服务器以及连接数据源到 Claude 时的安全和隐私实践的更多信息，请访问我们的[帮助中心](https://support.anthropic.com/en/articles/11175166-about-integrations-using-remote-mcp)。

---

## 关于 MCP（模型上下文协议）

MCP 是 Anthropic 创建的开放协议，旨在为 AI 应用程序连接工具和数据源提供标准化方法。它解决了当前 AI 集成中的复杂性和碎片化问题，通过提供通用的开放标准来连接 AI 系统与数据源，用单一协议替代了碎片化的集成。

### 主要特点：
- **开放标准**：为 AI 应用程序和外部工具/数据源之间的连接提供统一协议
- **客户端-服务器架构**：AI 应用程序作为客户端，通过 MCP 连接到各种服务器
- **本地和远程支持**：支持本地运行的服务器和通过互联网访问的远程服务器
- **工具和资源**：提供工具（函数调用）和资源（数据访问）两种交互方式
- **安全性**：通过 OAuth 等标准认证方式确保安全连接

### 生态系统：
目前已有众多公司和开源项目支持 MCP，包括但不限于：
- **企业合作伙伴**：Block、Apollo、Zapier、Atlassian、Asana 等
- **开发工具**：Zed、Replit、Codeium、Sourcegraph 等
- **预构建服务器**：Google Drive、Slack、GitHub、Git、Postgres、Puppeteer 等

MCP 正在快速发展为 AI 集成的事实标准，为开发者提供了一个更简单、更可靠的方式来为 AI 系统提供所需的数据访问能力。