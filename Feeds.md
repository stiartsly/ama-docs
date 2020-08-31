Feeds Project
============

## Page1 
### Introduction

**大家好，我是XXX，目前是Feeds dApp项目的产品负责人。**
*Hi everyone, I’m XXX and I’m currently the project lead of the Feeds Capsule.*



**非常感谢大家观看这个视频。**

*Thank you for watching this video*.




## Page2
### What is Feeds

**Feeds dApp简要地说就是一款去中心化的社交应用软件，用户在这款应用中完全拥有自己数据的控制权。**

*In brief , Feeds Capsule is a decentralised social platform application where users remain in full control of their own data.*

**当初我们在立项启动开发这款去中心化应用时，主要有两个初衷：**

*When we decided to launch the development of this decentralised application, there are two main purposes in there:*

- **当 elastOS应用成功发布給社区后，就会需要有一款以流量导向为主的应用来吸引和引导社区人员使用elastOS；**

*Once elastOS is successfully released to the community, a traffic-oriented application would be necessary to attract users to onboard elastOS.*

- **在使用亦来云基础服务之上，探索一种新型的去中心化应用和服务模式。**

*And meanwhile, we are exploring a new type of decentralised application and service model based on Elastos infrastructures.*

**希望Feeds dApp能够持续践行和实现这两个项目初衷，同时也是立身践行 “You Own Your Data”的亦来云项目宗旨, 这其中就需要亦来云社区爱好者的参与和支持.**

*Therefore, we hope Feeds Capsule will accomplish these two original purposes well, and also  implement the mission of “You own your data” into reality, which requires the engagement and support from Elastos community.*



### Feeds Update （Feeds现状）

**Feeds dApp以技术预览版形式已于今年8月中旬完成初始版本发布。至现在为止，已经迭代了一个BugFix版本和一个新特性版本。**

*The initial release of technical preview version of Feeds Capsule was just completed in mid-August.  And so far,  a new bug-fix version and a new feature version were released successively.*

### What's next 

**Feeds开发团队将继续致力于dApp用户体验的持续提升，同时不断集成更多的社交新特性。我们也在考虑在Feeds dApp中引入经济激励模型，激励产生更多的优质内容，通过内容进而吸引更多的用户。**

*Feeds team will keep committed to improvements on user experience of this capsule, and integration of new essential social features. Meanwhile, we are planing to introduce an economic incentive model to attract more user engagement with high-quality content.*



## Page2
### Defining Traits of Feeds

**与传统的社交应用（如Twitter和微博）相比，Feeds dApp具有以下最基本的特征**

*Compared with traditional social application such Twitter and Weibo, Feeds Capsule has the following most essential traits:*

- **使用去中心化ID身份验证登录后台服务。传统的社交应用使用中心化的用户账号系统或者第三方OAuth方式进行用户认证和授权。基于这种传统的用户身份认证方式不仅无法保证用户对自己账号信息的控制，也无法避免潜在的单点服务登录失败的问题**
  
  *Feeds Capsule use Elastos DID (Decentralised ID) to sign-in and access backend services. In comparison, for traditional social application,  they use the centralised account system or 3rd-party OAuth framework for authentication and authorisation, in which, not only it can not be guaranteed the full control of user's own credential, but also make it impossible to avoid the potential failure of single sign-on service.*

- **由于Feeds服务的去中心化，从前端用户角度来看，拥有了对不同后台服务访问的选择权，这样有益于服务内容的多样化**

  *With the decentralisation of Feeds services,  users have freedom of choices to get access for more different Feeds services, which would be beneficial to the diversity of service contents.*

- **同时由于Feeds服务的去中心化，Feeds 服务可以由任何人运行，并为用户提供对自己数据的完全控制权。**

  *With the decentralisation of Feeds service, it shows that the Feeds service can be run by anyone and empower them with the full control of their own data.*

  

## Page3
**在用户体验上，Feeds dApp 其实跟Twitter， 微博等比较类似。**

*In terms of the services and the user experience, Feeds Capsule is actually similar to Twitter and Weibo.*

**Feeds中如果用户对某个Feed感兴趣，则需要用户先登录该Feeds所在的Feeds Service，然后再关注对应的Feeds，进而阅读Feeds里面的系列微说，基于微说回复一些评注。**

*Once a user becomes interested in a certain feed, he can sign in with Elastos DID to Feeds backend service where the feed would be located. Then he can read the series of posts in this feed after following it, where he also can reply with comments on those posts.*

**从这几个图你可以看到，我们关注了几个Feeds，而这些Feeds在各自不同的Feeds 服务节点上。目前这些Feeds服务节点由不同的团队或者个人根据自己兴趣进行运行和管理。**

*On these figures, we have followed several Feeds, whereas these Feeds are located on different Feeds services, which currently are operated and managed by specific teams and individuals according to their own interests.*



## Page4

**目前Feeds Service已经支持Ubuntu/Debian Linux,  macOS等平台，可以运行在VPS，Raspberry Pi以及桌面设备上。**

*Currently, Feeds service supports Ubuntu/Debian Linux and macOS platforms, and can run on VPS, Raspberry Pi and desktop devices etc.*

**用户可以从[trinity-tech](https://www.trinity-tech.io/feeds.html)网站获取基于Linux平台的Debian安装包，也可以从[github.com](https://github.com/elastos-trinity/feeds-service/releases/tag/release-v1.1.0) 项目仓库发布包中下载。后续也会正式推出macOS上的Feeds Service应用包。**

*Users can obtain the Debian installation packages from website link [trinity-tech.io](https://www.trinity-tech.io/feeds.html), or from repository on [github.com](https:/ /github.com/elastos-trinity/feeds-service/releases/tag/release-v1.1.0).  Feeds service package running on macOS is in the to-do list now.*



## Page5

### Feeds Update

**Feeds dApp基础特性**

*Basic feature of Feeds Capsule*

- **用户（可以是个人或者机构组织）只能在自己运营的Feeds中发布微说;**

*User (can be individual or organisation ) can only make posts in the feeds he created;*

- **用户可以阅读已关注的Feeds中的微说和评论，同时就微说发表一些评论；**

*User can read posts and comments in the feed being followed, and also can make comments on specific posts in that feed;*

- **用户可以自动收到通知，让你知晓有哪些用户关注了你运营的Feeds，点赞了你发布的微说，或者在你的微说上留下了评注。**

*User can automatically receive notifications which inform you of who followed your feeds, who just liked your posts, and who left comments on your posts etc.*

- **支持扫描二维码分享Feeds服务；**

*Users can share Feeds service via it's address QRCode.*

- **通过ELA钱包打赏你喜欢的Feed**

*Users can tip for your favourite feeds*

## Page6

### What's next

**对于Feeds dApp，完成了技术预览版本的初始发布后，除了在UI/UX层面继续提升和完善用户体验外，还有以下几个方面的特性开发：**

*For Feeds Capsule,  as the technical preview version has been delivered to community, we will continue to improve UI/UX for better user experience, and integrate new essential features with following aspects:*

- **支持更多的分享Feeds服务途径，除了支持主流的第三方应用途径分享，也可以通过elastOS分享Feeds服务。同时，扩展支持直接推荐和分享Feeds本身；**

*Support more ways to share Feeds service. In addition to providing main sharing ways via 3rd-party applications,  you can also share Feeds service via elastOS. And also support for direct recommendation and sharing for Feed itself;*

- **支持私密Feeds。私密Feeds开始时可能对用户不可见，可直接通过朋友推荐请求关注，而且只有Feeds的所有者同意下才允许被关注；**

*Support private feeds, where private feeds may not be visible to users at first, and only could be followed with the approval of feeds owner via friend's recommendation;*

- **支持付费Feeds。付费Feeds只有在用户在完成付费的情况下才能加入该Feeds。一般情况下，这些付费Feeds能给用户提供有价值的创新内容；**

*Support paid feeds, where paid feeds could only be followed when users complete the payment. In general, paid feeds could provide the followers with innovative and valuable knowledge;*

- **支持更多形式的富媒体内容，例如九宫格图片，即拍即用短视频等**

*Support more forms of rich media contents,  such as pictures of Jiugongge, instant short videos, etc.*

- **规划在Feeds dApp生态中引入经济激励机制，例如基于亦来云ETH侧链的ERC20 Token，通过Token奖励吸引更多用户的参与度，从而提升内容品质以及用户流量。**

*We plan to introduce economic incentive model into Feeds Capsule, such as to integrate ERC20 token on ETH side-chain, to attract more engagement from community users with rewards, thereby to promote quality of content and increase traffic as well;*

- **将Feeds dApp改造成也可独立运营在Android/iOS等移动平台上的原生应用。其实目前Feeds dApp前端只是仅能运行elastOS平台的胶囊程序，还无法作为原生应用运行在Android/iOS等平台上。**

*Make Feeds Capsules to be a native application that can directly run on mainstream mobile platforms such as Android and iOS.  In fact, currently Feeds Capsule can only run on elastOS.*



## Page7

### Roadmap - 路线图

- **基于Android elastOS 持续发布 Feeds dApp胶囊程序。计划每两周定期发布一次新功能集成和问题修复版本；**

*Continue to deliver new versions of Feeds Capsule with integration of upcoming  features and bug-fixes for Android elastOS on bi-weekly basis;*

- **一旦elastOS工具链支持将elastOS dApps打包成为移动平台原生应用，同时elastOS运行时提供原生应用支持后，Feeds dApp也将提供Android和iOS的原生应用。这依赖于elastOS的相关工作进展，预定于今年年底提供。**

*Once elastOS toolchain supported packaging capsules as native applications on Android/iOS platforms, and also provided with native application support for dApps, Feeds dApp will provide native application, whic depends on the progress of elastOS, and would be slated on Dec. 2020 for this first release.*



## Page 8

**Feeds dApp项目虽道长路阻，但我们会持续优化和改进用户体验。**

*We know there is a long way off for Feeds Capsule project, and we will surely dedicate ourselves to keeping improvements for better experience.*



**我们期望后续发布的Feeds能够带来更多有趣的特性，吸引更多的优质内容、更多的用户流量，让Feeds的内容和用户生态持续发展。**

*We sincerely hope that subsequent releases of Feeds would bring more interesting features to you,  then can attract higher quality content and more traffic, therefore the ecology of contents and users continue to develop.*



**非常感谢社区人员对Feeds的支持，也欢迎大家通过这里的几个渠道给Feeds提供改进建议。**

*We highly appreciate the full support from community users, and welcome to feedback your any opinions and suggestions for improvement on Feeds via the channels here.*



**再一次感谢大家观看这个视频，谢谢大家**。

*Thank you again for watching this video. Thank you everyone.*



