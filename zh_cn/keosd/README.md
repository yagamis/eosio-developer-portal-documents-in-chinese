eosio developer portal documents in Chinese
=============================================

eos官网开发文档中文版

[英文原版在线版](https://developers.eos.io/)


# 在线阅读

使用 Gitbook 制作，可以直接[在线阅读，尚在翻译](http://)。

# 当前阶段

eos 1.3 翻译中，请到 issue 中，或加我微信：yunbog 认领章节。

- 第一次翻译。 2018-10-4

# 1.3 译者记录

Start Here:
- Development Environment: [yagamis](https://github.com/yagamis)
- Smart Contract Development: [待认领](https://github.com/)

Nodes：
- Overview: [待认领](https://github.com/)
- Docker Quickstart: [待认领](https://github.com/)

Cleos：
- Cleos Overview: [待认领](https://github.com/)
- Connect to Non-Default Host/Port: [待认领](https://github.com/)

Keosd：
- Keosd Overview: [待认领](https://github.com/)

Smart Contracts:
- Overview: [待认领](https://github.com/)
- Tutorials: [待认领](https://github.com/)
- Workflow Tips: [待认领](https://github.com/)

Building EOSIO:
- Getting the code: [待认领](https://github.com/)
- Build Options: [待认领](https://github.com/)
- Build Validation: [待认领](https://github.com/)

Setup Nodes:
- Configuration: [待认领](https://github.com/)
- Development Envionment: [待认领](https://github.com/)
- Troubleshooting: [待认领](https://github.com/)
- Testnets: [待认领](https://github.com/)
- Read Modes: [待认领](https://github.com/)

Advanced Guides:
- Full Scale Network: [待认领](https://github.com/)
- BIOS Boot Sequence: [待认领](https://github.com/)
- Benchmarking: [待认领](https://github.com/)
- Manually Install Dependencies: [待认领](https://github.com/)


EOSIO Plugins:
- bnet_plugin: [待认领](https://github.com/)
- chain_plugin: [待认领](https://github.com/)
- chain_api_plugin: [待认领](https://github.com/)
- faucet_testnet_plugin: [待认领](https://github.com/)
- http_plugin: [待认领](https://github.com/)
- net_api_plugin: [待认领](https://github.com/)
- net_plugin: [待认领](https://github.com/)
- producer_plugin: [待认领](https://github.com/)
- txn_test_gen_plugin: [待认领](https://github.com/)
- wallet_plugin: [待认领](https://github.com/)
- mongo_db_plugin: [待认领](https://github.com/)

C/C++ API:
- C API: [待认领](https://github.com/)
- C++ API: [待认领](https://github.com/)
- Types: [待认领](https://github.com/)

RPC API:
- Chain: [待认领](https://github.com/)
- History: [待认领](https://github.com/)
- Net: [待认领](https://github.com/)
- Producer: [待认领](https://github.com/)
- DBSize: [待认领](https://github.com/)

# 贡献力量

如果想做出贡献的话，你可以：

- 帮忙校对，挑错别字、病句等等
- 提出修改建议
- 提出术语翻译建议

# 翻译建议

如果你愿意一起校对的话，请仔细阅读：

- 使用markdown进行翻译，文件名必须使用英文，因为中文的话gitbook编译的时候会出问题
- 翻译后的文档请放到zh_cn文件夹下的对应目录中，然后pull request即可，我会用gitbook编译成网页
- fork过去之后新建一个分支进行翻译，完成后pull request这个分支，没问题的话我会合并到master分支中
- 有其他任何问题都欢迎发issue，看到了会尽快回复。我的微信：yunbog

谢谢！

# 关于术语

翻译术语的时候请参考这个流程：

- 尽量保证和已翻译的内容一致
- 尽量先搜索，一般来说编程语言的大部分术语是一样的，可以参考[微软官方术语搜索](http://www.microsoft.com/Language/zh-cn/Search.aspx)
- 如果以上两条都没有找到合适的结果，请自己决定一个合适的翻译或者直接使用英文原文，后期校对的时候会进行统一

# 参考流程

有些朋友可能不太清楚如何帮忙翻译，这里一个简单的流程，大家可以参考：

一、命令行版：

1. 首先fork项目
2. clone到你的本地
3. 运行 `git branch develop` 来创建一个新分支
4. 运行 `git checkout develop` 来切换到新分支
5. 运行 `git remote add upstream https://github.com/yagamis/eosio-developer-portal-documents-in-chinese.git` 添加为远端库
6. 运行 `git remote update`更新
7. 运行 `git fetch upstream master` 拉取我的库的更新到本地
8. 运行 `git rebase upstream/master` 将我的更新合并到你的分支

这是一个初始化流程，只需要做一遍就行，之后请一直在develop分支进行修改。

如果修改过程中项目库有了更新，请重复6、7、8步。

修改之后，首先push到你的库，然后登录GitHub，在你的库的首页可以看到一个 `pull request` 按钮，点击它，填写一些说明信息，然后提交即可。

二、你也可以用图形界面版本的github客户端来操作。


# 开源协议
基于[WTFPL](http://en.wikipedia.org/wiki/WTFPL)协议开源。



[yagamis]:https://github.com/yagamis
