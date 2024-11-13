# jiumaojiu-Stash
Stash 快捷配置教程（九毛九集团）
Stash 使用了一段时间后，发现默认的空白配置模板无法满足日常需求，因此我自定义了一个日常使用的配置模版，帮助更好地管理节点和订阅。接下来分享一下这个配置的使用方法和注意事项。

🌟 特色亮点
分区明确：按地区、服务分类，界面整洁，分流规则更加准确。
灵活配置：采用远程代理集方式，支持多个订阅，轻松实现多节点并行工作。
内存占用低：启动时仅需约22～25M的内存，可以高效运行。
🚀 使用步骤
1. 导入配置文件
首先你需要将 九毛九集团.yaml 配置文件导入 Stash。

方式一：通过手机浏览器下载 九毛九集团.yaml 文件，然后选择用 Stash 打开，即可自动导入。

方式二：如果是通过电脑下载，可以把该文件传输至手机，再进入 Stash > 设置 > 配置文件 > 从文件中导入 来完成导入。

方式三：如果开启了 iCloud 同步功能，可以直接将 九毛九集团.yaml 文件放入 iCloud/Stash目录 中，从而同步到应用。

2. 添加节点订阅链接
在 Stash 中打开 配置列表，选择刚才导入的配置文件。

进入 可视化编辑 > 远程代理集，填写你的订阅链接信息。你可以使用机场提供的订阅链接或者 SubStore 链接。

3. 连接检查
成功填写订阅信息后，返回主界面进行连接。如果一直无法连接，请查看日志，一般问题是某些订阅链接没有包含特定区域的节点。建议自行删除无效的代理组，并确保链接有效。
⚠️ 注意事项
OpenAI策略组

OpenAI 这个策略组已涵盖大部分知名的 AI 服务规则。⚠️ 请不要使用香港节点，因为很多 AI 服务无法通过香港 IP 访问。推荐使用 新加坡 和 日本 节点，或根据 AI 服务适用地区自行调整。
其他地区节点

为了兼容 SubStore 的订阅，同类地区进行了合并。非热门节点自动归类在 其他地区 策略组中。如果有特殊需求，可以自行添加新的策略组。
社交媒体策略

像 Twitter 和 Facebook 这样的社交平台，都已被归类到其他外网策略组里。无需单独处理。
规则集优化

如果自行修改规则集，建议避免使用 classical 类型的规则集。在手机设备上，效率至关重要，选用高效规则集能提升整体体验。
DNS 设置

当前配置仅使用了普通的 DNS IP 地址，没有过多复杂配置。同样，效率优先。
正版购买支持

Stash 是一款功能强大的工具，为了长期稳定体验，建议购买正版，支持开发者！💪
📝 总结
希望这套配置能帮你提升 Stash 的使用体验。不管是多节点管理还是自动分流，它都可以方便快捷地解决你日常遇到的问题。如果你对 Stash 感兴趣，赶紧试试看吧！🎉
![image](https://gist.github.com/user-attachments/assets/024c0353-409f-45b8-aa00-34660313a603)
