Elastos Carrier Project
====================

## Page1

大家好，我是XXX,  Elastos Carrier 项目的负责人。
*Hi, everyone. This is XXX,  currently the  project lead of Elastos Carrier.*

很高兴能通过这个视频机会向大家讲解Carrier项目的当前进展和后续规划。
*It is great be here to address the current status of Elastos Carrier and it's next plans.*

## Page2
### What is Elastos Carrier

Elastos Carrier 简单地说，就是一个去中心化的端对端完全加密的消息和数据通信平台。
*In brief, Elastos Carrier is a decentralised network platform with fully data encryption for end-to-end communication.*

Carrier网络中没有特殊的中心服务器和其他节点进行数据监听和备份。
*There is no special central servers or nodes involved with monitoring and backup for traffic in this Carrier network*

同时由于保证端到端的数据加密，即使出现中间者攻击截取通信数据，也无法对数据进行解密分析处理。
*And with guarantees of end-to-end data encryption, even if there is a man-in-middle attack intecept during communication, the data cannot be possibly decrypted.*

### Elastos Carrier Update

Elastos Carrier 就已有的在线数据通信功能已处于稳定成熟阶段，但是Carrier平台作为一个完整的通信解决方案，还需要包含成熟的去中心化模式的离线消息存取机制，以及作为补充的Push消息通知支持。
*Currently, online communication over Carrier network has been already enough  stable and mature to bear applications in practice. But as a whole package of communication solution,  Elastos Carrier also need a decentralized-like offline message storage machanism and Push message notification machanism supported.*

目前这两部分还处于缺失状态，即使有支持也仅是临时方案。
*At present,  these two parts are still missing, even though there is an interim solution for offline message storage.*

### Next Step

后续在持续优化原有的SDK功能外，计划会发布与社区合作的基于Carrier网络的WebRTC SDK，支持基本的音视频和数据通信功能。
*In addition to continuing to improve the implementation of supported features, we have a plan to release WebRTC SDK over Carrier network , where WebRTC SDK is an outsoucing project with one community team and now can support basic audio/video communication as well as data communication.*

同时基于目前缺失的功能进行预研尝试，能够孵化出可产品化的PoC版本。
*Meanwhile, we will take great efforts to make pre-search and incubate on PoC products for the missing parts of Carrier platform.*

## Page3

从实现层面和用户体验看，Elastos Carrier 网络具有以下最基本的特征和优势：
*From the view of implementation and user experience,  Elastos Carrier has the following most essential traits or advantages:*

- Carrier网络完全是去中心化的通信网络，每个节点都是Carrier网络中的同等节点。因此不会出现所谓的某个节点失效，导致整个网络失效的问题；
*Carrier network is a completely decentralized communication network, and each node is an equivalent node in there. Therefore, the inaccessible failure of certain nodes will not cause any inaccessible failures of the entire Carrier network.*

- Carrier网络是一个自治的网络，任何运行Carrier SDK的应用都可以加入成为网络中的节点，也可以随时离开网络；
Carrier network is also an autonomous network,  which means that any application running with Carrier SDK can join in the network as a Carrier node and leave the network at any time without any censorship from central authority.

- Carrier网络中数据通信必须基于好友之间进行，并且好友间的数据通信完全是安全可靠的端对端加密的。基本不可能出现中间人攻击导致通信数据泄密的问题；
The data communication in the Carrier network would carry out between friends and should be completely secure due to end-to-end encryption.  It is basically impossible for a man-in-the-middle attack for decryption and cause the leakage of communication data.

- Carrier网络中的节点可以是NAT-穿透的。也就是说，即使两个通信节点在不同的局域网环境里，比如使用手机基于办公室的网络通过Carrier可以正常访问到家里局域网的设备。
*The nodes in the Carrier network can be NAT-penetrating.  In other words, even if the two Carrier nodes are sit in different LANs. For example, you can use a mobile phone using office LAN to access the services or devices at your home LAN.*

## Page4

目前已经有社区团队基于Elastos Carrier网络和Carrier SDK实现各种特色应用。比如ElastOS核心平台应用elastOS，社区项目Hyper IM，Hyper Connect IoT 解决方案，社区的Feeds Capsule应用。
*Now, there are various featured applications using Carrier SDK and Elastos Carrier netwok, such as elastOS, the core application used as runtime,  Hyper IM application,  Hyper Connect IoT solution, and Feeds Capsule.*

我们可以从社区人员维护的网站 [peerjet.](http://peerjet.com)net 了解目前网络中Carrier节点在世界各地的活动区域和节点数。在准备这个视频时，能够检索到约20多万个活动节点。
*You can learn about the approximate number of active carrier nodes and hot areas in the Carrier network around world from the website [peerjet.net](http://peerjet.net) maintained by community. At the time of preparing this video,  there are more than 200,000 active nodes running as a whole of Carrier network.*

## Page5

至今为止，我们已经向社区发布了多个官方支持的Carrier SDKs的平台版本，包括Android Java，iOS/macOS Swift,  原生 C/C++ SDK，以及基于elastOS Runtime的javascript/typescript SDK。
S*o far, we have released a series of Carrier SDKs for various platforms, such as Native C/C++ SDKs for native systems, Java SDKs for Android platform,  Swift SDKs for iOS/macOS platforms,  and Javascript/Typescript SDKs for elastOS.*

目前Carrier SDK已经支持在Android/iOS移动平台，macOS/Linux/Windows等桌面平台，以及Raspberry Pi设备上运行。
*So, now Carrier SDK supports mainstream mobile platforms of Android/iOS, desktop systems of macOS/Linux/Windows, and Raspberry Pi devices etc.*

## Page6

这里我再简要的说明一下目前Carrier SDKs提供的主要特性支持：
*Here I will briefly explain the main feature currently provided by the Carrier SDKs:*

- 支持相互加好友，以及好友之间的消息通信；
*Supported with adding friends with carrier address and messaging each other between friends.*

- 临时的离线消息支持，目前暂时采用中心化消息存储的临时方案；
*Supported with the interim offline message storage machanism involved with central server;*

- 去中心化的群组支持；所谓去中心化群组表明没有中心化的群主角色，也不会出现被踢出群组。
*Supported with decentralized groups without management of members, which means nobody could be the group owner, and nobody can kick others out the group.*

- 基于Session/Stream连接的数据通信，以及之上的多路复用支持；
*Supported with end-to-end data communication based on Session/Stream connection, and multiplexing on top of Session/Stream.*

- 服务访问点的端口转发功能。比如本来只允许局域网内设备访问的服务入口直接支持为可通过公网访问的代理服务入口;
*Supported with portforwardinng for service access portal. For example,  the service portal that originally only allowed accesses from same LAN can be accessed from pubic network or even other LAN.*

- Pull模式的文件传输，支持断点续传功能;
*Supported with file transfer in pull mode, which support to resume transfering from breakpoint;*

- 基于Carrier 之上的WebRTC，支持最基本的音视频通信功能；
*Provided with WebRTC SDKs over Carrier SDKs, and supported the essential Audio/Video communication.*

## Page7

我们后续除了继续维护和稳定目前已有的SDK基本特性之外，同时也在孵化和实现Carrier中不足甚至是缺失的部分：
*We will continue to maintain and improve the existing basic features of Carrier SDK,  in the other side, we are also incubating and implementing the missing parts of Carrier network:*

- 基于Hive++ 节点服务之上实现离线消息存储机制；
*A techniqual preview version of offline message storage mechanism based on Hive++ node is being undertaken now.*

- 除了已有的去中心化群组，我们也在实现类似Hive++ 服务节点的可管理的Group服务节点的方案，计划能出一个可运行的PoC版本作为下一步工作的评估依据；
*Besides the existing decentralized group mechanism, a central manageable Group solution as service node similar to the Hive++ node is being incubated, and will be delivered with a PoC version as evaluation basis for next step.*

- 我们也在构思可配置的去中心化离线消息存储机制，让用户可以选择自己的方式去存储离线消息。
*And we are also conceiving the solution of configurable decentralized offline message storage, allowing users to choose their own way to store offline messages.*

## Page8

我们除了正常维护和问题修复的版本发布外，还会计划发布基于以下特性的预览版或者PoC（概念验证）版本：
*In addition to the regular releases based improvements and bugfixes for Carrier SDKs, we will plan to release the versions of  techniqual preview or PoC (Proof of Concept) quality for the following features:*

- 关于Group群组的离线消息存储机制。目前已经基于Hive++服务节点方案尝试实现，预计于今年九月底发布第一个技术预览版；
*About the offline message storage mechanism for Carrier group, it has been implementing based on Hive++ Node solution, and the first technical preview version will be released at the end of Dec. this year*

- 我们会在大概于十月发布基于Carrier SDK的WebRTC SDK技术预览版本，支持最基本的音视频通信功能；
*We will publicly release a technical version of WebRTC SDK over Carrier SDK in Oct, which will support the essential Audio/Video communication as well as data communication.*

- 对于可管理的Group群组，尝试在今年底发布一个PoC（概念验证）版本。
*As to the solution of central manageable Group, we have plan to deliver a PoC version at  end of this year.*

## Page9

Elastos Carrier 作为Elastos生态中最基础和重要的服务之一，我们深感职责重大。
*Elastos Carrier as one of the most essential and important infrastractures in the Elastos ecosystem, we deeply feel the reponsibility.*

我们会持续不断稳定和改进Carrier SDKs，同时也会尽心研究和实现目前作为通信平台缺失的部分。
*We will continue to stabilize and improve the Carrier SDKs,  and at the same time, we will take our best efforts to make research and implement the missing parts of Carrier as communication platform.*

在这里，借此机会感谢Elastos项目成立以来社区人员给予的关注和大力支持。
*Here, I would like to take this opportunity to thank the community for your cares and supports since the start of the Elastos project.*

希望社区人员能够加入Carrier Telegram群组中来，尽心参与讨论和提供更多关于Carrier的宝贵意见和建议。
*I also hope that the community members can join the Telegram group of Elastos Carrier,  and would put forward your valuable opinions and suggestion about Carrier .*

再一次感谢大家观看这个视频，谢谢大家。
*Thank you again for watching  this video, thank you all.*