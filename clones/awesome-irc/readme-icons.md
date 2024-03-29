# Awesome IRC [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of awesome [IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) resources.

A list of tools, software & other resources related to the Internet Relay Chat (IRC) protocol.

IRC (Internet Relay Chat) is an open source protocol that can be used for multi-user text based communication through channels.

## Contents

- [Clients](#clients)
- [Bouncers](#bouncers)
  - [Self-hosted](#self-hosted)
  - [Hosted](#hosted)
- [Daemons](#daemons)
- [Services](#services)
- [Bots](#bots)
- [Frameworks](#frameworks)
  - [Bridges](#bridges)
- [Channels](#channels)
  - [Discovery](#discovery)
  - [Platforms](#platforms)
  - [Programming](#programming)
- [Networks](#networks)
- [Articles](#articles)
- [Guides](#guides)
- [Protocol](#protocol)
- [Miscellaneous](#miscellaneous)

### Clients

_You use these to connect to IRC._

- [![Komanda-icon-24px](https://user-images.githubusercontent.com/15098724/56874874-bf5ba580-69f1-11e9-9d3e-5265c43bcc7d.png) Komanda](https://komanda.io) - Designed for people who write code (beta). ([source](https://github.com/mephux/komanda)) `Linux`
- [![Textual-icon-24px](https://user-images.githubusercontent.com/15098724/56874954-680a0500-69f2-11e9-87ec-d4015ce54af5.png) Textual](https://www.codeux.com/textual/) - Very customizable, ZNC integration, iCloud sync ($4.99). ([source](https://github.com/Codeux-Software/Textual)) `macOS`
- [![Limechat-icon-24px](https://user-images.githubusercontent.com/15098724/56875043-04cca280-69f3-11e9-8e1f-285e54784fe4.png) LimeChat](http://limechat.net/mac/) - One window for multiple servers, keyboard shortcuts, fast & stable. ([source](https://github.com/psychs/limechat)) `macOS` `iOS`
- [![Hexchat-icon-24px](https://user-images.githubusercontent.com/15098724/56874706-b28a8200-69f0-11e9-9ca7-27c8779134e0.png) HexChat](https://hexchat.github.io) - Based on XChat, easy to use, spell check & multiple languages. ([source](https://github.com/hexchat/hexchat)) `Windows` `macOS` `Linux`
- [![KiwiIRC-icon-24px](https://user-images.githubusercontent.com/15098724/56875143-a7852100-69f3-11e9-8b33-2035c156c016.png) Kiwi IRC](https://kiwiirc.com) - Powerful modern IRC messenger for the web. ([source](https://github.com/kiwiirc/kiwiirc), [demo](https://kiwiirc.com/nextclient/)) `Web`
- [![CIRC-icon-24px](https://user-images.githubusercontent.com/15098724/56875201-1498b680-69f4-11e9-91ff-ae3b674c82be.png) CIRC](https://flackr.github.io/circ/) - Uses the chrome.sockets APIs to connect directly to IRC servers without needing a proxy. ([source](https://github.com/flackr/circ)) `Chrome`
- [![Quassel-icon-24px](https://user-images.githubusercontent.com/15098724/56875264-84a73c80-69f4-11e9-807c-75db09db0ec5.png) Quassel](https://quassel-irc.org) - Distributed (clients can attach to and detach from a central core that stays permanently online. ([source](https://github.com/quassel/quassel)) `Linux` `macOS` `Windows`
- [![YAAIC-icon-24px](https://user-images.githubusercontent.com/15098724/56875320-f8e1e000-69f4-11e9-9665-de50e95f4d91.png) Yaaic](https://www.yaaic.org) - Multi-server/channel support, SASL support, Smooth channel scrolling / swiping. ([source](https://github.com/pocmo/Yaaic)) `Android`
- [![KokoIRC-icon-24px](https://user-images.githubusercontent.com/15098724/56875424-c389c200-69f5-11e9-8464-5132a289aefd.png) Koko](https://github.com/KokoIRC/koko) - Minimalistic design, VIM-like shortcuts and built on electron. `Windows` `macOS`
- [relay.js](https://github.com/Fauntleroy/relay.js) - Focuses on making IRC less intimidating and easier to use. ([demo](http://demo.relayjs.com)) `Web`
- [![Circe-icon-24px](https://user-images.githubusercontent.com/15098724/56875558-a3a6ce00-69f6-11e9-92da-2e4d8c7b4a53.png) Circe](https://github.com/jorgenschaefer/circe) - For use in Emacs, sane defaults. `Emacs`
- [![Smuxi-icon-24px](https://user-images.githubusercontent.com/15098724/56875672-2f205f00-69f7-11e9-8cac-5721602234bb.png) Smuxi](https://smuxi.im) - User-friendly, based on GNOME / GTK+. ([source](https://github.com/meebey/smuxi)) `Linux` `Windows` `macOS`
- [![KvIRC-icon-24px](https://user-images.githubusercontent.com/15098724/56874636-1d878900-69f0-11e9-856e-719c4c822e25.png) KvIRC](http://www.kvirc.net) - Free, portable, based on Qt GUI toolkit. ([source](https://github.com/kvirc/KVIrc)) `Linux` `macOS` `Windows`
- [![Konversation-icon-24px](https://user-images.githubusercontent.com/15098724/56876024-609a2a00-69f9-11e9-91dd-196f310776d7.png) Konversation](https://konversation.kde.org) - User-friendly client built on the KDE Platform. ([source](https://github.com/KDE/konversation)) `Linux`
- [![sic-icon-24px](https://user-images.githubusercontent.com/15098724/56876157-457bea00-69fa-11e9-94f5-11dcd0bfb00c.png) sic](https://tools.suckless.org/sic/) - **S**imple **I**RC **c**lient - a terminal client in less than 250 lines of C. `Linux`
- [![Colloquy-icon-24px](https://user-images.githubusercontent.com/15098724/56876204-a3103680-69fa-11e9-8169-00e0450722de.png) Colloquy](http://colloquy.info) - AppleScript-enabled IRC client. `macOS`
- [![irssi-icon-24px](https://user-images.githubusercontent.com/15098724/56876266-0c904500-69fb-11e9-85a9-00796373cf88.png) irssi](https://irssi.org) - Terminal client, multi-protocol friendly for module authors, GPLv2. `Linux` `macOS` `Cygwin` `BSD`
- [![RevolutionIRC-icon-24px](https://user-images.githubusercontent.com/15098724/56876444-4f065180-69fc-11e9-8200-b244b6a86e94.png) Revolution IRC](https://github.com/MCMrARM/revolution-irc) - Feature-full, actively maintained Android IRC client. ([source](https://github.com/MCMrARM/revolution-irc)) `Android`
- [![AdiIRC-icon-24px](https://user-images.githubusercontent.com/15098724/56632956-0e2fc680-6611-11e9-949e-c79c21f465a0.png) AdiIRC](https://adiirc.com) - Never has a client offered such granular settings for every aspect of the IRC experience. ([features](https://dev.adiirc.com/projects/adiirc/wiki/Features), [screenshots](https://dev.adiirc.com/projects/adiirc/wiki/Screenshots)) `Windows` `WINE`
- [![IRCforAndroid-icon-24px](https://user-images.githubusercontent.com/15098724/56655816-b3b25c80-6648-11e9-92e1-12ca4587d9eb.png) IRC for Android™](https://www.countercultured.net/android/) Android/Chrome OS client for power users, with ZNC built-ins, notification logic, reliable DCC, keybinds for hardware keyboards, etc. `Android` `ChromeOS`

_More? Clients that include bouncers are found [below](#bouncers)._

### Bouncers

_Useful for disconnecting and reconnecting without losing the chat session._

#### Hosted

- [![IRCCloud-icon-24px](https://user-images.githubusercontent.com/15098724/56879253-ba581f80-6a0c-11e9-8f6b-8461c10ed149.png) IRCCloud](https://www.irccloud.com) - Group chat for teams, friends, and communities. stay connected, chat from anywhere, and never miss a message (+client) (£0-£3.50/month).
  - [iOS App](https://github.com/irccloud/ios) - Official. `Objective-C`
  - [Android App](https://github.com/irccloud/android) - Official. `Java`
  - [Nimbus](https://github.com/jnordberg/irccloudapp) - Standalone client. `macOS` `Objective-C`
- [![Grove-icon-24px](https://user-images.githubusercontent.com/15098724/56879376-541fcc80-6a0d-11e9-882a-980aa6f285bf.png) Grove](https://grove.io) - Hosted IRC and so much more (+client) ($10-$125/month).

- [![Convos-icon-24px](https://user-images.githubusercontent.com/15098724/56879497-d8724f80-6a0d-11e9-844d-7a5380b4524b.png) Convos](https://convos.chat) - Always online web IRC client. ([source](https://github.com/convos-chat/convos), [demo](https://demo.convos.chat)) `Perl` `JavaScript` `Web`
- [![ZNC-icon-24px](https://user-images.githubusercontent.com/15098724/56879721-d8268400-6a0e-11e9-8b74-c2c748d15c4a.png) ZNC](https://wiki.znc.in/ZNC) - Most popular. many different plugins. ([source](https://github.com/znc/znc))
- [![BIP-icon-24px](https://user-images.githubusercontent.com/15098724/56899123-89491080-6a47-11e9-8513-4c8d09be32d9.png) BIP IRC Proxy](https://bip.milkypond.org) - Always online, lightweight and secure Open Source IRC proxying with backlogging. ([source](https://projects.duckcorp.org/projects/bip/repository)) `C`
- [![TheLounge-icon-24px](https://user-images.githubusercontent.com/15098724/56899491-6b2fe000-6a48-11e9-9f01-1ed2cfb86b09.png) TheLounge](https://thelounge.chat) - Responsive, self-hosted & support for multiple users. ([source](https://github.com/thelounge/thelounge), [demo](https://demo.thelounge.chat/)) `JavaScript` `Node.js` `Web`
- [![weechat-icon-24px](https://user-images.githubusercontent.com/15098724/56876389-e028f880-69fb-11e9-82d6-8084e17f2f04.png) WeeChat](https://weechat.org) - A fast, light and extensible chat client. ([source](https://github.com/weechat/weechat)) `Linux` `macOS` `Windows`

### Daemons

_Used for running your own IRC server or network._

- [ircd.js](https://github.com/alexyoung/ircd.js) - Server will allow clients to connect, join channels, change topics; basic stuff.
- [InspIRCd](https://www.inspircd.org) - Modular, stable, written from scratch. ([source](https://github.com/inspircd/inspircd))
- [miniircd](https://github.com/jrosdahl/miniircd) - Very simple and limited.
- [ngIRCd](https://ngircd.barton.de) - Portable and lightweight for small or private networks. ([source](https://github.com/ngircd/ngircd))
- [Hulk](https://github.com/chrisdone/hulk) - Intended for private business use or hobby work. `Haskell`
- [Oragono](https://oragono.io) - Modern, experimental server that's portable and designed around specifications. ([source](https://github.com/oragono/oragono))
- [charybdis](https://github.com/charybdis-ircd/charybdis) - Scalable IRCv3 server.
- [RobustIRC](https://robustirc.net) - IRC server without netsplits.

### Services

_Used to provide user accounts and bots like NickServ/ChanServ to your network._

- [Atheme](https://atheme.github.io) - Designed for large networks with high scalability requirements. ([source](https://github.com/atheme/atheme))
- [anope](https://anope.org) - Designed for flexibility and ease of use. ([source](https://github.com/anope/anope))

### Bots

_IRC users which provide services for humans, e.g. integrations or information._

- [Sopel](https://sopel.chat) - Tonnes of ready made features, tutorial, fully documented. ([source](https://github.com/sopel-irc/sopel)) `Python`
- [phenny](http://inamidst.com/phenny/) - Simple, module creation guide. ([source](https://github.com/sbp/phenny)) `Python`
- [IRCcat](https://github.com/RJ/irccat) - Simplifies messaging from shell scripts. `Java`
- [Limnoria](https://github.com/ProgVal/Limnoria) - Robust, user friendly, developer friendly. `Python`
- [Twitch Plays](https://github.com/aidanrwt/twitch-plays) - Takes input from the chat and presses the corresponding key. `Python`
- [Skybot](https://github.com/rmmh/skybot) - Main goals are simplicity and power. `Python`
- [Jenni](https://github.com/myano/jenni) - `Python`
- [talkbackbot](https://geekchick77.dreamwidth.org/472.html) - Responds to configured trigger phrases with quotes from notable women. ([source](https://github.com/jessamynsmith/talkbackbot)) `Python`
- [lazybot](https://github.com/Raynes/lazybot) - User-friendly and powerful. `Clojure`
- [IRC-BF](https://github.com/ddevault/bf-irc-bot) - `Brainfuck`
- [geordi](https://github.com/Eelis/geordi) - Compiles and runs C++ code snippets. `C++`
- [CloudBot](https://github.com/CloudBotIRC/CloudBot) - Simple, fast, expandable. `Python`
- [yossarian-bot](https://github.com/woodruffw/yossarian-bot) - Large default plugin set, Cinch-based. `Ruby`
- [helga](https://github.com/shaunduncan/helga) - Pluggable chat bot supporting multiple protocols. `Python`

### Frameworks

_Helpful to write bots or integrate IRC with applications._

- [node-irc](https://github.com/Throne3d/node-irc) `JavaScript`
- [Cinch](https://github.com/cinchrb/cinch) - Quickly create bots with minimal effort. `Ruby`
- [goirc](https://github.com/fluffle/goirc) - Event-based, stateful, lacking documentation. `Go`
- [Hubot IRC Adapter](https://github.com/nandub/hubot-irc) - The IRC adapter for hubot. `JavaScript`
- [go-ircevent](https://github.com/thoj/go-ircevent) - Event-based. `Go`
- [pyaib](https://github.com/facebook/pyaib) - Easy to use framework for writing bots. `Python`
- [slate-irc](https://github.com/slate/slate-irc) - Plugin system, simple api, arbitrary input stream, debug support. `JavaScript`
- [PircBotX](https://github.com/pircbotx/pircbotx) - Event based IRC Library with a straightforward API (updated fork of [PircBot](http://www.jibble.org/pircbot.php)). `Java`
- [IRC::Client](https://github.com/perl6-community-modules/perl6-IRC-Client) - `Perl6` based extendable IRC client framework.

#### Bridges

_Sends messages back and forth._

- [discord-irc](https://github.com/reactiflux/discord-irc) - Discord ↔ IRC. `JavaScript`
- [slack-irc](https://github.com/ekmartin/slack-irc) - Slack ↔ IRC. `JavaScript`
- [irc-slack](https://github.com/insomniacslk/irc-slack) - Slack ↔ IRC. `Go`
- [BitlBee](https://www.bitlbee.org/main.php/news.r.html) - XMPP, Jabber, Google Talk, MSN Messenger, Yahoo! Messenger, AIM, ICQ, Twitter API, HipChat ↔ IRC. `C`
- [teleirc](https://github.com/FruitieX/teleirc) - Telegram ↔ IRC. `JavaScript`
- [toxirc](https://github.com/endoffile78/toxirc) - Tox ↔ IRC. `C`
- [skyweb2irc](https://github.com/ProgVal/skyweb2irc) - Skype (webclient API) ↔ IRC. `Javascript`
- [whapp-irc](https://github.com/lieuwex/whapp-irc) - WhatsApp Web ↔ IRC. `Go`
- [matterbridge](https://github.com/42wim/matterbridge) - IRC ↔ Mattermost ↔ Discord ↔ XMPP ↔ Gitter ↔ Slack ↔ Discord ↔ Telegram ↔ ... `Go`

### Channels

_IRC channels._

#### Discovery

- [netsplit.de Search](https://netsplit.de/channels/) - Searches 563 different networks.
- [mibbit Search](https://search.mibbit.com) - Searches networks listed [here](https://search.mibbit.com/networks).
- [KiwiIRC Search](https://kiwiirc.com/search) - Searches 318 different networks.

#### Platforms

- [##linux](https://freenode.linux.community)@freenode - Linux support and discussion channel. ([rules](https://freenode.linux.community/channel-rules/))
- [#ubuntu](https://help.ubuntu.com/community/InternetRelayChat)@freenode - Official ubuntu support channel. ([rules](https://wiki.ubuntu.com/IRC/Guidelines))

#### Programming

- [#python](https://www.python.org/community/irc/)@freenode - Good place for short python questions. ([rules](https://www.python.org/psf/codeofconduct/))

### Networks

_A collection of IRC servers is known as a network._

- [freenode](https://freenode.net) - The largest network, for free and open source software communities. ([rules](https://freenode.net/policies))
- [Snoonet](https://snoonet.org) - Community of redditors and subreddits. ([rules](https://snoonet.org/rules/))
- [OFTC](https://oftc.net) - Community for free and open source software communities.

### Articles

_Articles and blog posts about IRC._

- [Please don't use Slack for FOSS projects](https://drewdevault.com/2015/11/01/Please-stop-using-slack.html) - Drew DeVault's Blog.
- [IRC Networks Under Systematic Attack From Governments](https://www.quakenet.org/articles/102-press-release-irc-networks-under-systematic-attack-from-governments) - QuakeNet.
- [IRC is dead, long live IRC](https://royal.pingdom.com/irc-is-dead-long-live-irc/) - Royal Pingdom.
- [IRC Has Lost 60% Of Its Users Since 2003, But Life As A Robot Is Just Beginning](https://techcrunch.com/2013/01/06/irc-has-lost-60-of-its-users-since-2003-but-life-as-a-robot-is-just-beginning/) - Alex Williams (TechCrunch).

### Guides

_How-to's, documentation and books._

- [#irchelp](https://www.irchelp.org) - A vast amount of reasonably up-to-date information.

### Protocol

_Information and resources about the IRC protocol itself._

- [IRCv3 Working Group](https://ircv3.net) - A group of IRC software authors working to enhance, improve, maintain and standardize the IRC protocol. ([source](https://github.com/ircv3/ircv3.github.io))
- [Modern IRC Documents](https://modern.ircdocs.horse) - An attempt to write an update to the original IRC protocol. documentation ([source](https://github.com/ircdocs/modern-irc))
- [IRC Definition Files](https://defs.ircdocs.horse) - Lists of numerics, modes, ISUPPORT tokens and other protocol details. ([source](https://github.com/ircdocs/irc-defs))
- [grawity's IRC docs](https://github.com/grawity/irc-docs) - Collection of misc IRC protocol documentation.
- [Protocol Statistics](https://stats.ircdocs.horse) - Statistics around the server software in use on networks today. ([source](https://github.com/ircdocs/irc-stats))
- [IRC Parser Tests](https://github.com/ircdocs/parser-tests) - A CC0 set of test suites, to ensure IRC message parsers are consistent.

### Miscellaneous

_Items that belong on the list but defy classification._

- [IRC LC](https://irc.lc) - Create a URL that points to a channel on a IRC network.

## Use

The best ways to use this list are:

- by browsing the [contents](#contents)
- by using <kbd>command</kbd> + <kbd>F</kbd> to search the contents

This list also uses tags to help when searching the contents:

- **Language** - `Python`, `Java`, `C++`, `Go`, `JavaScript`, `Ruby`, `C` etc.
- **Platform** - `Web`, `macOS`, `Windows`, `Linux`, `Chrome` etc.

## Credits

**[Craig Davison](https://davison.io)**

[![GitHub](https://img.shields.io/github/followers/davisonio.svg?style=social&label=Follow%20@davisonio)](https://github.com/davisonio) [![Twitter](https://img.shields.io/twitter/follow/davisonio.svg?style=social)](https://twitter.com/davisonio)

...and [contributors](https://github.com/davisonio/awesome-irc/graphs/contributors).

**[Contributions are welcome!](https://github.com/davisonio/awesome-irc/blob/master/contributing.md)**

## License

Unless otherwise stated:

- Copyright © 2016+ [Craig Davison](https://davison.io). Licensed under [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/).
