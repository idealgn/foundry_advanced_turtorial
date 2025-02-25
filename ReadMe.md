<h1 align="center"> 2024 年 Foundry 进阶开发教程 <br></h1>
<p align="center"><strong>学习如何使用 Foundry 进行更深一步的 Solidity 智能合约开发 <br>作者： lllu_23</br></strong>
</p>

<br>
<br>
<br>
<h1><strong>Warning: 本教程中构建的所有代码未经过严格审核，仅用于学习交流的目的，禁止在实际的生产环境中使用！！！！！！</strong></h1>
<br>
<br>
<br>

# 推荐的学习资料
1. [Solidity 官方文档](https://docs.soliditylang.org/): 如果你有一定的编程基础，对一些 `Solidity` 基础变量的定义或语法的使用还不太了解，又不想花太多的时间去看视频教程，那么结合文档进行学习会是一个更不错的选择
2. [Foundry 官方文档](https://book.getfoundry.sh/): 这是使用 `Foundry` 框架进行 `Solidity` 智能合约开发必须要阅读的资料，同时当你真正开始构建生产级别应用时，可以在其中找到很多我并未在提及到的开发技巧和解决错误的方法
3. [以太坊官网](https://ethereum.org/zh/): 这是以太坊的官方网站，页面大都进行了中文翻译，对中文开发者非常友好，你可以在这里了解到以太坊生态相关的基础知识，路线图和资讯。如果你对以太坊白皮书感兴趣的话，在导航栏中你也能找到 Vitalik 在 2014 年撰写的白皮书
4. [WTF 学院](https://www.wtf.academy/): 由 0XAA 大佬创建的 Web3 开源大学，里面涵盖了很多教程: Solidity 的基础课程，ethers.js，甚至还有 ZK 相关的课程，强烈推荐新入门 Web3 的开发者通过这个社区进行课程学习

# 推荐的视频教程（中文）

1.[北京大学肖臻老师的《区块链技术与应用》公开课](https://www.bilibili.com/video/BV1Vt411X7JF ): 课程内容主要是讲解以太坊和比特币的底层原理，虽然肖臻老师录制该课程的时间为 2018 年，但是课程容并不过时，其中涉及到编程的内容很少，大多数都是对区块链的认真看完会帮助你打下非常坚实的理论基础

2.[B站 up主：五里墩茶社的《跟我学Solidity》系列](https://space.bilibili.com/615957867/channel/collectiondetail?sid=1067760 )这是我看过讲解 `Solidity` 最为详细的中文教程博主，从最基础的知识一直讲到实际的合约编写，所有使用 `Solidity` 开发智能合约，需要的基础知识都囊括其中了，其视频配套使用的` WTF 学院`发布的一系列区块链相关课程我在上面也有提到，输入入门必看系列！！！

3. 如果你已经了解了 `Solidity` 的相关基本知识，接下来应该开始学习框架从而进入到实际开发中，目前主流的 `Solidity` 开发框架有两个： `Hardhat` 与 `Foundry`，这两个课程都是由 `Patrick Collins` 老师讲授的，
- Hardhat 框架的课程链接：[（32 小时最全课程）区块链，智能合约 & 全栈 Web3 开发](https://www.bilibili.com/video/BV1Ca411n7ta)
- Foundry 框架的课程链接：[【人工精翻】B站最新Solidity智能合约Foundry框架零基础教程1-12课（已完结)](https://www.bilibili.com/video/BV13a4y1F7V3)
**这个课程也是我在 2023 年断断续续花了 100 多个小时翻译的，我个人认为在视频教程里面非常优质的课程了，学完这个 Foundry 课程基本就不用再看其他任何教程了！！！**

4. 学完长达 21 小时的框架课程之后，你就应该已经完全具备独立开发基本的 DeFi、NFT 相关智能合约的能力了，这个时候我会建议你补充一下智能合约审计相关的知识，同样是由 `Patrick Collins` 老师讲授，此外，还有更为详细的智能合约审计相关课程由 `Owen` 老师讲授。
入门基本的智能合约安全审计课程：[2024年智能合约安全审计课程（第1-5课）](https://www.bilibili.com/video/BV1B94y1M71V) 
进阶的智能合约安全审计课程： [21 小时智能合约安全审计课程（基础知识+案例实战）](https://www.bilibili.com/video/BV1qK4y1i7Zw) 

# 非常优质的 Web3 开发者社区
- [Chainlink预言机](https://space.bilibili.com/482973600)
- [DappLearning](https://space.bilibili.com/2145417872/)
- [DoraHacks](https://space.bilibili.com/445312136/)
- [登链社区](https://space.bilibili.com/581611011)
- [TinTinLand](https://space.bilibili.com/1152852334)

# 如何解决你在编程学习当中遇到的问题

## 1. 搜索引擎
### 当你遇到了编译错误或者是你无法解决的问题，你可以尝试将你的代码片段复制粘贴到搜索引擎的对话框中，看一看有没有人遇到和你类似的错误，如果是常规错误，那么大部分时候靠搜索引擎就能解决
**Tips**：
不要将错误代码整段整段的复制到对话框中，这样搜索引擎通常会无法检索到正确的信息
- 正确做法：选择较为核心的错误提示进行搜索
### 搜索引擎推荐：
  - [百度](https://www.baidu.com/)
  - [谷歌](https://www.baidu.com/)

## 2. 论坛
### Stack Exchange 是一个专注于以太坊生态的论坛，里面有很多开发者提出的问题，也有很多大佬会帮忙解答，如果你在搜索栏中无法找到类似的错误解决办法，发个贴并附上详细的代码以及错误提示，相信不久之后就会有大佬帮你解答。
  - [Stack Exchange Ethereum](https://ethereum.stackexchange.com/)

## 3. 免费的 AI 助手
### 如何使用这一类的人工智能工信就不用我多说了，需要注意的是，一般来说不需要开通会员，也能够帮你解决大部分问题了，按自己的喜好选择适合的工具即可，我个人更加偏爱 ChatGPT 和 Phind。
  - [ChatGPT](https://chat.openai.com/)
  - [Phind](https://www.phind.com/)：与 ChatGPT 类似，但是可以结合提问内容进行网页搜索
  - [Bard](https://bard.google.com/)
  - [claude.ai](https://claude.ai/)

## 4. Github Copilot
### 
**我不推荐新手朋友在学习的过程中使用 Copilot，Copilot 会自动帮你完成很多本应你自己完成的代码，相信我，自己跟着视频教程敲一遍代码，一定能让你学到更多**
  - [copilot](https://github.com/features/copilot)

# 环境配置
1. 安装并配置 `git` 所需的环境
    - [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
        - 安装成功后可以运行 `git --version`，如果安装成功则显示 `git version x.x.x`，截止 2024 年 11 月，当前我使用的版本为 `2.39.5`。
2. 安装并配置 `Foundry`
    - [foundry](https://getfoundry.sh/)
        - 安装成功后可以运行 `forge --version` ，如果安装成功则显示 `git version x.x.x`，截止 2024 年 11 月，当前我使用的版本为 `2.39.5`。
        - You'll know you did it right if you can run `forge --version` and you see a response like `forge 0.2.0 (af97b2c 2024-07-18T00:22:15.301937000Z)`

# 测试网水龙头

## 推荐使用 [Amoy](https://amoy.polygonscan.com/): Polygon 的测试网，之前的名字叫 `Mumbai`, 后来改为了 `Amoy`
1. [Alchemy Faucet (Amoy)](https://sepoliafaucet.com/)
2. [Infura Faucet (Amoy)](https://www.infura.io/faucet/sepolia)
3. [Chainlink Faucet (Amoy)](https://faucets.chain.link/amoy)
-  **Tips: 现在的水龙头基本都需要你在主网钱包中有少量的代币余额，才可以领取测试币**

# 推荐安装的 VSCode 插件

- vscode-icons: 图标优化
- Error Lens: 优化错误提示
- solidity: 以太坊官方插件
- TODO Highlight: TODO 高亮
- indent-rainbow: 缩进显示优化
- Prettier - Code formatter: 代码格式化
- Dracula Theme Official & Shades of Purple: VSCode 主题，选择自己喜欢的即可
- Foundry Test Explorer: 直接在 VSCode的 test explorer 中运行 Foundry 的 solidity 测试
 
# 编程过程中可能会用到的网页工具

- [Ethereum Unit Converter](https://eth-converter.com/): 以太坊的单位转换工具，因为实际在 Solidity 中编程，默认的计量单位为 Wei, 与 ether 之间存在 10 ** 18 的换算，编程时不确定换算是否正确可以使用此工具进行核验

- [OpenZeppelin官网](https://www.openzeppelin.com/): 内有 Solidity 中最全的标准库，官方文档中包含不同操作系统的安装方式，以及查看标准库中一些合约的源代码，同时主页有一个简易的合约定制工具，可以快速生成 ERC-20, ERC-721 等合约的模板

- [Alchemy](https://www.alchemy.com/): 在一定限额内免费的多条公链 API 的工具，同时也支持实时数据分析以及交易监听的

- [Infura](https://www.infura.io/zh): 与 Alchemy 提供的服务差不多，选自己用的顺手的就行

# 智能合约安全相关的学习资料

## 推荐的学习资料
- 入门合约安全审计必读文章: [如何成为智能合约审计员](https://cmichel.io/how-to-become-a-smart-contract-auditor/) Christoph Michel 大佬的博文，这哥们曾经靠合约安全审计一年赚了一百万美元，同时也在文章里分享了自己的一些心得

**@TODO**
这部分内容还有很多学习资料，后面有时间了抽空补上...

## 智能合约安全审计比赛
- [Code4rena](https://code4rena.com/): 相较于其他两个，我个人比较喜欢的平台，可以很方便的查看过往比赛的审计报告，数量很多，选择自己感兴趣的报告查看学习即可。同时也有不定期的公开审计比赛，没有什么门槛限制，有闲暇时间可以参与一下，看看自己的审计能力

- [Immunefi](https://immunefi.com/): 审计比赛平台，同时也有一些合约安全审计的学习资料

- [Sherlock](https://audits.sherlock.xyz/contests): 审计比赛平台,比赛也很多

- [CodeHawks](https://codehawks.cyfrin.io/): Cyfrin 官方推出的审计平台，主要是以其过往的审计报告为主，赏金较少

# 常见的 Foundry 指令(这一部分似乎不是很需要，考虑要不要删了)

## 运行一个本地的 `anvil` 节点
```
anvil
```
`anvil` 非常好用，结合 `cast` 基本可以在本地完成全部的链上操作

## 编译合约
这将默认在本地节点部署智能合约。为了成功部署，你需要在另一个终端中运行 `anvil`。
```
forge compile
```
需要注意的是，确保你合约内标注的 `solc` 版本与安装的版本一致，如果你想指定特定的编译器版本，可以在 `foundry.toml` 中使用
```
solc-version = ["0.x.x"]
```
进行设置

## 构建合约
编译合约并在本地生成字节码和 `ABI` 文件
```
forge build
```

## 部署合约
这将默认在本地节点部署智能合约。为了成功部署，你需要在另一个终端中运行 `anvil`。
**必须要提的是，当前的 `Foundry` 不需要编写部署脚本进行合约部署，可以使用 `forge create` 命令进行快速部署，具体代码如下**
```
forge create <contract_address> --constructor-args <args> --private-key <private_key> --rpc-url <rpc_url>
```

# 使用 `cast` 与合约进行交互
## 一般使用 `cast send` 和  `cast call` 与智能合约进行交互，详细用法可以在[ Foundry 官方文档](https://book.getfoundry.sh/cast/?highlight=cast#how-to-use-cast)  - cast 概览中找到


# 一些 Web3 招聘网站
## 中文招聘网站
- [SmartDeer](https://www.smartdeer.work/zh): 在 IOS/Android 端的应用商店都能自己搜索到，将求职意向选择到 Web3 相关的岗位，会跳转出很多的 Web3 项目方，缺点是 HR 回复速度慢或不回复，需要自己找到联系方式后，通过写邮件或其他方式再次投递简历。
- [abetterweb3]: 华人自制的以 `Notion` 形式发布的招聘网页，可以在上面发布自己的简历，也可以根据项目方贴出来的联系方式直接与项目方联系
- Boss 直聘, 智联招聘, 猎聘这些传统的招聘网站也有很多 Web3 的招聘信息，大家注意甄别，和项目方沟通时记得多留几个心眼，不要踩坑就行

## 海外招聘网站
https://web3.career/<br>
https://remote3.co/<br>
https://remoteok.com/<br>
https://cryptojobslist.com/<br>
https://www.useweb3.xyz/<br>
https://www.cryptojobs.com/<br>
https://blockchain.works-hub.com/<br>
https://abetterweb3.notion.site/abetterweb3-7ce334dcf8524cb79a5894bdd784ddb4<br>

# 未来计划录制的视频教程
1. 使用 `Foundry` 框架编写一份通用的 `ERC-20` 代币合约，并编写一份 `Faucet.sol ` 合约供测试账户通过水龙头领取代币。在未来所有的合约编写过程中，我们都将不再使用 `Amoy` 测试网代码，统一使用我们自己构建的 ERC-20 代币。
2. 使用 MerkleTree (默克尔树)构建一个代币空投合约
3. 使用 `Foundry`, `Circom`, `Snarkjs`编写一份类似 Tornado Cash 的混币器合约，主要目的是真切的让大家感受到 `零知识证明` 在具体项目中的应用，而不仅仅只停留在理论层面。
4. 未完待续...


<br><br><br><br><br>
<p align="center">
<strong>
感谢你阅读全文，希望这篇文档能给你带来一些帮助！<br>
搬运转载请注明出处！！！<br>
作者： lllu_23<br>
联系方式: lllu238744@gmail.com<br>
最后一次更新时间: 2024-11-19<br>
</strong>
</p>

