# 什么是NOSTR

想象着有一个完全点对点交换信息的网络。这个网络上的信息不会被任何人审查，你发布的信息不会被任何第三方删除；同时，需要这些信息的人，不管你是否处于在线状态，随时可以从网络上拉取你发布的信息；如果你从一个APP/网站，迁移到另外一个APP/网站，只需要登入相同的账号，而不需要任何其他的迁移工作，你的所有信息（粉丝，发布的内容）都会跟随你到达新的APP；你的注册也不再依赖于邮箱或者是手机号，是不是很酷！

现在，我们有了Nostr。Nostr是"Notes and Other Stuff Transmitted by Relays"的缩写。它本身与HTTP，TCP/IP 类似属于协议的一种而非一个APP或者软件，然而你基本可以基于这个协议搭建任何软件，如社交媒体、文件传输、私聊软件、电商软件甚至DAO。Nostr同时与闪电网络有深度整合，未来极大可能会在各个方面改变人们的行为方式。

Nostr有以下几大特点

1. 简单性\
   Nostr的协议十分简单却通用。 在Nostr里只有两类服务， 客户端和中继；一种数据类型，\`event\`。客户端以event格式发送信息，同时从中继获取自己需要的信息并且展示出来，中继接收且保存信息。
2. 可靠性\
   在整个网络会存在很多中继，一旦有一个中继删除某个客户发送的信息，或者整个中继停止服务，使用者依然可以从其他中继找回自己的数据。
3. 可验证性\
   客户作为网络的参与者，每个人都拥有自己的私钥，所有发送出去的数据以私钥进行签名，同时event里包含公钥，这样所有的参与者可以验证这条信息是否由这个人发出。&#x20;
