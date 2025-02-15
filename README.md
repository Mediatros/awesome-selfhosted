# Awesome-Selfhosted

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Selfhosting is the process of locally hosting and managing applications instead of renting from SaaS providers.

This is a list of [Free](https://en.wikipedia.org/wiki/Free_software) Software [network services](https://en.wikipedia.org/wiki/Network_service) and [web applications](https://en.wikipedia.org/wiki/Web_application) which can be hosted locally. Non-Free software is listed on the [Non-Free](non-free.md) page.

See [Contributing](#contributing).

Table of Contents
=================

  - [Analytics](#analytics)
  - [Automation](#automation)
  - [Blogging Platforms](#blogging-platforms)
  - [Bookmarks & Link Sharing](#bookmarks--link-sharing)
  - [Calendar and Address Books](#calendar-and-address-books)
  - [Communication systems](#communication-systems)
    - [Custom](#custom)
    - [Email](#email)
      - [Complete solutions](#complete-solutions)
      - [Mail Transfer Agents](#mail-transfer-agents)
      - [Mail Delivery Agents](#mail-delivery-agents)
      - [Mailing lists](#mailing-lists)
      - [Webmail clients](#webmail-clients)
    - [IRC](#irc)
    - [SIP](#sip)
    - [Social Networks and Forums](#social-networks-and-forums)
    - [XMPP](#xmpp)
      - [XMPP Servers](#xmpp-servers)
      - [XMPP Web Clients](#xmpp-web-clients)
  - [Content Management Systems (CMS)](#content-management-systems-cms)
    - [E-commerce](#e-commerce)
  - [Document Archiving](#document-archiving)
  - [Enterprise Resource Planning](#enterprise-resource-planning)
  - [Federated Identity/Authentication](#federated-identityauthentication)
  - [Feed Readers](#feed-readers)
  - [File Sharing and Synchronization](#file-sharing-and-synchronization)
      - [Distributed filesystems](#distributed-filesystems)
      - [File transfer/synchronization](#file-transfersynchronization)
      - [Peer-to-peer filesharing](#peer-to-peer-filesharing)
      - [Single-click/drag-n-drop upload](#single-clickdrag-n-drop-upload)
      - [Web based file managers](#web-based-file-managers)
  - [Games](#games)
  - [Gateways](#gateways)
  - [Groupware](#groupware)
  - [Learning and Courses](#learning-and-courses)
  - [Maps & GPS](#maps--gps)
  - [Video Streaming](#video-streaming)
  - [Mind Maps](#mind-maps)
  - [Money, Budgeting and Management](#money-budgeting-and-management)
  - [Monitoring and Administration](#monitoring-and-administration)
  - [Music Streaming](#music-streaming)
  - [Note-taking & Editors](#note-taking--editors)
  - [Office Suites](#office-suites)
  - [Password Managers](#password-managers)
  - [Pastebins](#pastebins)
  - [Personal Dashboards](#personal-dashboards)
  - [Photo and Video Galleries](#photo-and-video-galleries)
  - [Polls and Events](#polls-and-events)
  - [Proxy](#proxy)
  - [Read it Later Lists](#read-it-later-lists)
  - [Search Engines](#search-engines)
  - [Software Development](#software-development)
    - [Project Management](#project-management)
    - [Bug Trackers](#bug-trackers)
    - [IDE/Tools](#idetools)
    - [Continuous Integration](#continuous-integration)
    - [Documentation Generators](#documentation-generators)
  - [Static site generators](#static-site-generators)
  - [Task management/To-do lists](#task-managementto-do-lists)
  - [Ticketing](#ticketing)
  - [URL Shorteners](#url-shorteners)
  - [VPN](#vpn)
  - [Web servers](#web-servers)
  - [Wikis](#wikis)
  - [Self-hosting Solutions](#self-hosting-solutions)
  - [List of Licenses](#list-of-licenses)
  - [External links](#external-links)
  - [Contributing](#contributing)
  - [License](#license)


-----------------------------------------------------------------------------

<!-- BEGIN SOFTWARE LIST -->

## Analytics

_Web Analytics_

  * [AWStats](http://www.awstats.org/) - Generates web, streaming, ftp or mail server statistics graphically. ([Source Code](https://github.com/eldy/awstats)) `GPLv3` `Perl`
  * [Countly](https://count.ly) - Real time mobile & web analytics, crash reporting and push notifications platform. ([Source Code](https://github.com/countly)) `AGPL` `Javascript`
  * [GoAccess](http://goaccess.io/) - Real-time web log analyzer and interactive viewer that runs in a terminal. ([Source Code](https://github.com/allinurl/goaccess)) `GPLv2` `C`
  * [Open Web Analytics](http://www.openwebanalytics.com/) - Google Analytics and Piwik alternative. ([Source Code](https://github.com/padams/Open-Web-Analytics/)) `GPL` `PHP`
  * [Piwik](https://piwik.org/) - Leading open-source analytics platform that gives you more than just powerful analytics. ([Source Code](https://github.com/piwik/)) `GPLv3` `PHP`
  * [Snowplow](http://snowplowanalytics.com/) - Have every single event, from your websites, mobile apps, desktop applications and server-side systems, stored in your own data warehouse and available to action in real-time. ([Source Code](https://github.com/snowplow/)) `Apache` `Scala`
  * [ThinkUp](https://www.thinkup.com/) - Insights into your social networking activity on Twitter, Facebook, Instagram, and beyond. ([Source Code](https://github.com/ThinkUpLLC/ThinkUp)) `GPL` `PHP`
  * [Webalizer](http://www.webalizer.org/) - Fast web server log file analysis. `GPL` `C`


## Automation

  * [Alltube](http://www.alltubedownload.net) - A web interface for [youtube-dl](https://github.com/rg3/youtube-dl), a program to download videos and audio from [more than 100 websites](https://rg3.github.io/youtube-dl/supportedsites.html). ([Demo](http://www.alltubedownload.net), [Source Code](https://github.com/Rudloff/alltube)) `GPL` `PHP`
  * [AmIUnique](https://amiunique.org/) - Learn how identifiable you are on the Internet (browser fingerprinting tool). ([Source code](https://github.com/DIVERSIFY-project/amiunique) `MIT` `Java`
  * [Healthchecks](https://healthchecks.io/) - Django app which listens for pings and sends alerts when pings are late. ([Source Code](https://github.com/healthchecks/healthchecks)) `BSD` `Python`
  * [Huginn](https://github.com/cantino/huginn) - Allows you to build agents that monitor and act on your behalf - `MIT` `Ruby`
  * [Http2pic](https://http2pic.haschek.at/) - Website screenshots/renderer. It uses the wkhtmltox to render websites with various options. ([Source Code](https://github.com/chrisiaut/http2pic)) `Apache 2.0` `PHP/Javascript`
  * [RSS-Bridge](https://github.com/sebsauvage/rss-bridge) - rss-bridge is a PHP project capable of generating ATOM feeds for websites which don't have one. `Public domain` `PHP`
  * [TriggerHappy](http://trigger-happy.eu/) - An opensource clone of IFTTT, a bridge between your internet services. ([Source Code](https://github.com/foxmask/django-th)) `BSD` `Python`
  * [WTFDYUM](https://github.com/jchampemont/WTFDYUM) a.k.a Why The Fuck Did You Unfollow Me - Find out who stops following you on Twitter. ([Demo](https://www.wtfdyu.me/), [Source Code](https://github.com/jchampemont/WTFDYUM)) `Apache` `Java`


## Blogging Platforms

See also [Static Site Generators](#static-site-generators), [Content Management Systems](#content-management-systems-cms) and [WeblogMatrix](http://www.weblogmatrix.org/)

  * [Anchor CMS](https://anchorcms.com/) - Anchor is a free, lightweight, faster-than-a-bullet, simple blogging system, made for art–directed posts. ([Source Code](https://github.com/anchorcms/anchor-cms)) `GPLv3` `PHP`
  * [Antville](https://antville.org) - Antville is a free, open source project aimed at the development of a high performance, feature rich weblog hosting software. ([Source Code](https://github.com/antville/antville)) `Apache` `JavaScript`
  * [Blogotext](http://lehollandaisvolant.net/blogotext/en/) - A free blog-engine written in PHP and using SQLite. This offers you both an unmatched simplicity during installation and great performances. ([Source Code](https://github.com/timovn/blogotext)) `MIT` `PHP`
  * [Chyrp](https://github.com/chyrp/chyrp) - An extra-awesome, extra-lightweight blog engine. `MIT` `PHP`
  * [Dotclear](http://dotclear.org/) - Take control over your blog! ([Source Code](https://hg.dotclear.org/dotclear)) `GPLv2` `PHP`
  * [Ghost](https://ghost.org/) - Just a blogging platform. ([Source Code](https://github.com/TryGhost/Ghost)) `MIT` `Nodejs`
  * [htmly](https://www.htmly.com/) - Databaseless Blogging Platform (Flat-File Blog). ([Demo](https://www.htmly.com/demo/), [Source Code](https://github.com/danpros/htmly)) `GPLv2` `PHP`
  * [Known](https://withknown.com/) - A single website for all your content. ([Source Code](https://github.com/idno/idno)) `Apache` `PHP`
  * [Noddity](http://noddity.com/) - It's a blog, it's a wiki, it's a fast CMS! ([Source Code](https://github.com/TehShrike/noddity)) `WTFPL` `Nodejs`
  * [PluXml](http://www.pluxml.org/) - XML-based blog/CMS platform. ([Source Code](https://github.com/pluxml/PluXml)) `GPL` `PHP`
  * [Wagtail](https://wagtail.io/) - A Django content management system focused on flexibility and user experience. ([Source Code](https://github.com/torchbox/wagtail)) `BSD` `Python`
  * [Wordpress](https://wordpress.org/) - Create a beautiful website or blog. ([Source Code](https://github.com/WordPress/WordPress)) `GPLv2`


## Bookmarks & Link Sharing

  * [Bookie](https://github.com/bookieio/Bookie) - Python based delicious.com replacement. ([Demo](http://bmark.us/)) `AGPLv3` `Python`
  * [Firefox Accounts Server](https://docs.services.mozilla.com/howtos/run-fxa.html)
   * [Firefox Sync Server](https://docs.services.mozilla.com/howtos/run-sync-1.5.html) - Sync Firefox bookmarks, passwords, history, tabs, preferences. ([Source Code](https://github.com/mozilla-services/syncserver)) `MPLv2` `Python`
  * [Lobsters](https://lobste.rs) - Run your own link aggregation site. ([Source Code](https://github.com/jcs/lobsters)) `BSD` `Ruby`
  * [Myyna](http://www.myyna.com/) - Open source alternative to Pinterest. ([Demo](http://demo.myyna.com/), [Source Code](https://github.com/cubettech/myyna)) `MIT` `Nodejs`
  * [No Fuss Bookmarks](http://nofussbm.herokuapp.com/signup.html) - Very simple software and service to store bookmarks especially designed for hackers (that don't need fancy interfaces, but nice API). ([Source Code]( https://github.com/mapio/nofussbm)) `GPLv3` `Python`
  * [Pinry](http://getpinry.com/) - The tiling image board system for people who want to save, tag, and share images, videos, and webpages. ([Source Code](https://github.com/pinry/pinry)) `BSD` `Python`
  * [Scuttle](https://github.com/scronide/scuttle) - Web-based social bookmarking system. Allows multiple users to store, share and tag their favourite links. `GPLv2` `PHP`
  * [Shaarli](https://github.com/shaarli/Shaarli) - Personal, minimalist, super-fast, no-database bookmarking and link sharing plaform. ([Demo](http://shaarlidemo.tuxfamily.org/Shaarli/) `demo/demo`) `Zlib` `PHP`
  * [unmark](https://unmark.it/) - An open source to do app for links. ([Source Code](https://github.com/plainmade/unmark)) `MIT` `PHP`


## Calendar and Address Books

Some [Groupware](#groupware) solutions also feature calendar/address book editing and synchronization.

  * [AgenDAV](http://agendav.org/) - Multilanguage CalDAV web client with a rich AJAX interface and shared calendars support. [Source Code](https://github.com/adobo/agendav) `GPLv3` `PHP`
  * [Baïkal](http://baikal-server.com/) - Lightweight CalDAV+CardDAV server. ([Source Code](https://github.com/fruux/Baikal)) `GPLv3` `PHP`
  * [CalendarServer](http://trac.calendarserver.org/) - A standards-compliant server implementing the CalDAV and CardDAV protocols. `Apache` `Python`
  * [calypso](http://keithp.com/calypso/) - A python-based CalDAV/CardDAV server. ([Source Code](http://keithp.com/cgi-bin/gitweb.cgi?p=calypso.git;a=tree)) `GPLv3` `Python`
  * [DAViCal](http://www.davical.org/) - A server for calendar sharing (CalDAV). ([Source Code](https://gitlab.com/davical-project/davical)) `MIT` `PHP`
  * [ownCloud calendar](https://doc.owncloud.org/server/9.0/user_manual/pim/calendar.html) - The ownCloud Calendar app enables you to create and edit events, synchronize to other calendars you might use, and create new, personalized calendars. ([Source Code](https://github.com/owncloud/calendar-rework)) `AGPLv3` `PHP`
  * [Radicale](http://radicale.org/) - A Simple Calendar and Contact Server. ([Source Code](https://github.com/Kozea/Radicale)) `GPLv3` `Python`
  * [sabre/dav](http://sabre.io/) - A open source CardDAV, CalDAV and WebDAV server. ([Source Code](https://github.com/fruux/sabre-dav)) `MIT` `PHP`


## Communication systems

### Custom

  * [Freenet](https://freenetproject.org/index.html) - Anonymously share files, browse and publish "freesites" (web sites accessible only through Freenet) and chat on forums. ([Source Code](https://github.com/freenet/fred)) `GPLv2` `Java`
  * [Friends](http://moose-team.github.io/friends/) - P2P chat powered by the web. ([Source Code](https://github.com/moose-team/friends)) `MIT` `Nodejs`
  * [GNUNet](https://gnunet.org/) - Free software framework for decentralized, peer-to-peer networking. ([Source Code](https://gnunet.org/svn/)) `GPLv3` `C/Java`
  * [Jitsi Meet](https://jitsi.org/Projects/JitsiMeet) - Jitsi Meet is an OpenSource (MIT) WebRTC JavaScript application that uses Jitsi Videobridge to provide high quality, scalable video conferences. ([Source Code](https://github.com/jitsi/jitsi-meet)) `MIT ` `JavaScript`
  * [Jitsi Video Bridge](https://jitsi.org/Projects/JitsiVideobridge) - WebRTC compatible Selective Forwarding Unit (SFU) that allows for multiuser video communication. ([Source Code](https://github.com/jitsi/jitsi-videobridge)) `Apache` `Java`
  * [Kandan](http://getkandan.com/) - Kandan is an Open Source Alternative to HipChat. ([Source Code](https://github.com/kandanapp/kandan)) `AGPLv3` `Ruby`
  * [Lets-Chat](http://sdelements.github.io/lets-chat/) - A self hosted chat suite written in Node. ([Source Code](https://github.com/sdelements/lets-chat)) `MIT` `JavaScript, NodeJS`
  * [Mattermost](http://www.mattermost.org/) - Open-source, on-prem Slack-alternative. It can be integrated with [Gitlab](https://about.gitlab.com/). ([Source Code](https://github.com/mattermost/platform)) `AGPLv3/Apache 2.0` `Go`
  * [Mibew](https://mibew.org) - Mibew Messenger is an open-source live support application written in PHP and MySQL. It enables one-on-one chat assistance in real-time directly from your website. ([Demo](https://mibew.org/demo2), [Source Code](https://github.com/Mibew/mibew)) `Apache` `PHP/Javascript`
  * [Mumble](http://wiki.mumble.info/wiki/Main_Page) - Low-latency, high quality voice/text chat software. ([Source Code](https://github.com/mumble-voip/mumble)) `BSD` `C++`
    * [Mumblecop](https://bitbucket.org/Flandoo/mumblecop) - Stream audio from youtube and soundcloud, simulate dice rolls, or write your own commands with a simple plugin format. `MIT` `Ruby`
  * [Node-Chat](https://github.com/IgorAntun/node-chat) - A not-so-basic open-source chat with admin features. `MIT` `Nodejs`
  * [RetroShare](http://retroshare.org) - Secured and decentralized communication system. Offers decentralized chat, forums, messaging, file transfer. ([Source Code](https://github.com/RetroShare/RetroShare)) `GPLv2` `С++`
  * [Rocket.Chat](https://rocket.chat/) – Teamchat solution similar to Gitter.im or Slack. ([Source Code](https://github.com/RocketChat/Rocket.Chat)) `MIT` `Nodejs`
  * [Synapse](https://matrix.org/blog/project/synapse/) - A server for [Matrix](https://matrix.org/), an open standard for decentralized persistent communication. ([Source Code](https://github.com/matrix-org/synapse)) `Apache` `Python`
    * [Vector](https://matrix.org/blog/project/vector/) - A glossy Matrix web client with an emphasis on performance and usability. ([Source Code](https://github.com/vector-im/vector-web)) `Apache` `Javascript`
    * [Matrix Console Web](https://matrix.org/blog/project/matrix-console-web/) - A web client meant to be a showcase of Matrix capabilities, and reference implementation of the Matrix standard. ([Source Code](https://github.com/matrix-org/matrix-angular-sdk)) `Apache` `Javascript`
  * [Syndie](https://www.syndie.de) - Syndie is a libre system for operating distributed forums. `CC0` `Java`
  * [TextBelt](https://github.com/typpo/textbelt) - An outgoing SMS API that uses carrier-specific gateways to deliver your text messages for free, and without ads. ` ⚠ ` `MIT` `JavaScript`
  * [Tox](https://tox.chat/) - A distributed, secure messenger with audio and video chat capabilities. ([Source Code](https://github.com/irungentoo/toxcore)) `GPLv3` `C`
  * [Tuber](https://blog.trailofbits.com/2015/12/15/self-hosted-video-chat-with-tuber/) - Peer-to-peer video chat that works. ([Source Code](https://github.com/trailofbits/tubertc)) `MIT` `JavaScript`
  * [Zulip](https://zulip.org) - Zulip is a powerful, open source group chat application. ([Source Code](https://github.com/zulip/zulip)) `Apache 2.0/Other` `Python/Django`


### Email

#### Complete solutions

_simple deployment of a mail server, e.g. for inexperienced or impatient admins._

  * [Mailcow](https://mailcow.email/) - Mail server suite based on Dovecot, Postfix and other open source software, that provides a modern Web UI for administration. ([Source Code](https://github.com/andryyy/mailcow)) `GPLv2` `PHP/Shell`  
  * [Mail-in-a-Box](https://mailinabox.email/) - Turns any Ubuntu server into a fully functional mail server with one command. `CC0` `Shell/Other`
  * [iRedMail](http://www.iredmail.org/) - Full-featured mail server solution based on Postfix and Dovecot. ([Source Code](https://bitbucket.org/zhb/iredmail/commits/)) `GPLv3` `Shell`
  * [Citadel](http://www.citadel.org/) - Feature packed, easy, versatile, and powerful mail server, thanks to exclusive "rooms" based architecture. ([Source Code](http://code.citadel.org/?p=citadel.git;a=summary))
  * [Modoboa](http://modoboa.org/en/) - Modoboa is a mail hosting and management platform including a modern and simplified Web User Interface. ([Source Code](https://github.com/tonioo/modoboa)) `MIT` `Python`


#### Mail Transfer Agents

_MTAs / SMTP servers_

* [Courier MTA](http://www.courier-mta.org/) - Fast, scalable, enterprise mail/groupware server providing ESMTP, IMAP, POP3, webmail, mailing list, basic web-based calendaring and scheduling services. ([Source Code](http://www.courier-mta.org/repo.html)) `GPLv3` `C`
* [Exim](http://www.exim.org/) - Message transfer agent (MTA) developed at the University of Cambridge. `GPL`
* [Haraka](http://haraka.github.io/) - A high-performance, pluginable SMTP server written in JavaScript. ([Source Code](https://github.com/haraka/Haraka)) `MIT` `Javascript`
* [MailCatcher](http://mailcatcher.me/) - Ruby gem that deploys a simply SMTP MTA gateway that accepts all mail and displays in web interface. Useful for debugging or development. ([Source Code](https://github.com/sj26/mailcatcher)) `MIT` `Ruby`
* [Maildrop](https://github.com/m242/maildrop) - Disposable email SMTP server, also useful for development. `MIT` `Scala`
* [OpenSMTPD](https://opensmtpd.org/) - Secure SMTP server implementation from the OpenBSD project. `ISC`
* [Postfix](http://www.postfix.org/) - Fast, easy to administer, and secure Sendmail replacement. `IPL` `C`
* [Qmail](http://www.qmail.org/top.html) - Secure Sendmail replacement. `CC0`
* [Sendmail](http://www.sendmail.com/sm/open_source/) - Message transfer agent (MTA).


#### Mail Delivery Agents

_MDAs - IMAP/POP3 software_

* [Cyrus IMAP/POP3](http://cyrusimap.org/) - Intended to be run on sealed servers, where normal users are not permitted to log in.
* [Dovecot](http://www.dovecot.org/) - IMAP and POP3 server written primarily with security in mind. ([Source Code](https://github.com/dovecot/core)) `MIT / LGPLv2` `C`
* [Piler](http://www.mailpiler.org/wiki/start) - feature rich open source email archiving solution. ([Source Code](https://bitbucket.org/jsuto/piler)) `GPLv3` `C`


#### Mailing lists

_Mailing lists servers._

  * [Mailman](https://www.gnu.org/software/mailman/) - The Gnu mailing list server. `Python` `GPL`
  * [Sympa](https://www.sympa.org/) - A mailing list manager. `Perl` `GPL`


#### Webmail clients

  * [Cypht](http://cypht.org/index.html) - A feed reader for your email accounts. ([Source Code](https://github.com/jasonmunro/hm3)) `GPLv2` `PHP`
  * [Mailpile](https://www.mailpile.is/) - Webmail client with search, filtering, encryption features and more. ([Source Code](https://github.com/mailpile/Mailpile)) `AGPLv3` `Python`
  * [RainLoop](http://www.rainloop.net/) - Simple, modern & fast webmail with IMAP/SMTP Support and multi accounting. ([Demo](http://demo.rainloop.net/), [Source Code](https://github.com/RainLoop/rainloop-webmail)). `AGPLv3` `PHP`
  * [Roundcube](https://roundcube.net) - Browser-based IMAP client with an application-like user interface. ([Screenshots](https://roundcube.net/screens/)) ([Source Code](https://github.com/roundcube/roundcubemail/)) `GPLv3` `PHP`
  * [SquirrelMail](http://squirrelmail.org) - Another browser-based IMAP client. ([Source Code](https://sourceforge.net/p/squirrelmail/code/HEAD/tree/)) `GPLv2` `PHP`
  * [WebMail Lite](http://www.afterlogic.org/webmail-lite) - Web-based IMAP Mail client. ([Source Code](https://github.com/afterlogic/webmail-lite)) `GPLv3` `PHP`


### IRC

*[IRC](https://en.wikipedia.org/wiki/Internet_Relay_Chat) communication software*

  * [Convos](http://convos.by/) - Always online web IRC client. ([Demo](http://demo.convos.by), [Source Code](http://github.com/nordaaker/convos)) `ARTv2` `Perl`
  * [IRCAnywhere](http://ircanywhere.com/) - Open-source self-hosted alternative to IRCCloud. ([Source Code](https://github.com/ircanywhere/ircanywhere)) `JavaScript` `Nodejs`
  * [Quassel IRC](http://quassel-irc.org/) - distributed IRC client, meaning that one (or multiple) client(s) can attach to and detach from a central core. ([Source Code](https://github.com/quassel/quassel)) `GPLv2` `C++`
  * [Shout](http://shout-irc.com/) - The self-hosted web IRC client. ([Demo](http://demo.shout-irc.com/), [Source Code](https://github.com/erming/shout)) `MIT` `Nodejs`
  * [Weechat](https://weechat.org/) - A fast, light and extensible chat client. `GPLv3` `C`
  * [ZNC](http://wiki.znc.in/ZNC) - An advanced IRC bouncer. ([Source Code](https://github.com/znc/znc)) `Apache` `C++`


### SIP

*[SIP](https://en.wikipedia.org/wiki/Session_Initiation_Protocol) telephony software*

  * [Asterisk](http://www.asterisk.org/) - An easy to use but advanced IP PXB system, VoIP gateway and conference server. `GPLv2` `C`
  * [FreeSWITCH](https://freeswitch.org/) - Scalable open source cross-platform telephony platform. ([Source Code](https://freeswitch.org/stash/projects/FS/repos/freeswitch/browse)) `MPLv2` `C`
  * [Kamailio](http://www.kamailio.org/w/) - Modular SIP server (registrar/proxy/router/etc) ([Source Code](https://github.com/kamailio/kamailio)) `GPLv2` `C`
  * [Ostel](https://dev.guardianproject.info/projects/ostel/wiki/Server_Documentation) - Secure SIP telephony setup with ZRTP encryption. `GPLv3` `Ruby`


### Social Networks and Forums

  * [Anahita](https://www.getanahita.com/) - Open Source Social Networking Framework & Platform. ([Source Code](https://github.com/anahitasocial)) `GPLv3` `PHP`
  * [Bootcamp](http://trybootcamp.vitorfs.com) - An enterprise social network. ([Source Code](https://github.com/vitorfs/bootcamp)) `MIT` `Python`
  * [Buddycloud](http://buddycloud.com/) - Tools, libraries, services and a community to build user-to-user, group and social messaging into your app. Saves time. Scales up. Supports you. ([Source Code](https://github.com/buddycloud)) `Apache 2.0` `Java/Javascript`
  * [BuddyPress](https://buddypress.org/about/) - A powerful plugin that takes your WordPress.org powered site beyond the blog with social-network features like user profiles, activity streams, user groups, and more. ([Source Code](https://buddypress.svn.wordpress.org/trunk/)) `GPLv2` `PHP`
  * [diaspora*](https://diasporafoundation.org/) - Distributed social networking server. ([Demo](http://podupti.me/random.php), [Source Code](https://github.com/diaspora/diaspora)) `AGPLv3` `Ruby`
  * [Discourse](http://www.discourse.org/) - Advanced forum / community solution based on Ruby and JS. ([Source Code](https://github.com/discourse/discourse)) `GPLv2` `Ruby`
  * [Elgg](https://elgg.org/) - A powerful open source social networking engine. ([Source Code](https://github.com/Elgg/Elgg)) `GPLv2` `PHP`
  * [Flarum](http://flarum.org) - Delightfully simple forums. Flarum is the next-generation forum software that makes online discussion fun again. ([Source Code](https://github.com/flarum/flarum)) `MIT` `PHP`
  * [FluxBB](http://fluxbb.org/) - Fast, light, user-friendly forum software for your website. ([Source Code](https://github.com/fluxbb/fluxbb)) `GPLv2` `PHP`
  * [Friendica](http://friendica.com/) - Social Communication Server. ([Source Code](https://github.com/friendica/friendica)) `AGPLv3`
  * [Gnu Social](https://gnu.io/social/) - Social communication software for both public and private communications. ([Source Code](https://git.gnu.io/gnu/gnu-social)) `AGPLv3` `PHP`
  * [Hubzilla](https://github.com/redmatrix/hubzilla) - Independent general-purpose websites that not only connect with their associated members and viewers, but also connect together. `MIT` `PHP`
  * [HumHub](https://www.humhub.org/) - A flexible kit for private social networks. ([Source Code](https://github.com/humhub/humhub)) `AGPLv3` `PHP`
  * [Isso](http://posativ.org/isso/) - A lightweight commenting server written in Python and JavaScript. It aims to be a drop-in replacement for Disqus. ([Source Code](https://github.com/posativ/isso)) `MIT` `Python`
  * [Jappix](https://jappix.com/) - Jappix is an open social platform, that let's you easily get or keep in touch with everyone. ([Source Code](https://github.com/jappix/jappix)) `AGPLv3`
  * [Loomio](https://www.loomio.org/) - Loomio is a collaborative decision-making tool that makes it easy for anyone to participate in decisions which affect them.  ([Source Code](https://github.com/loomio/loomio)) `AGPLv3` `Ruby`
  * [Movim](https://movim.eu/) - A brand new social network, full of awesome features in a modern and smart interface. ([Source Code](https://github.com/movim/movim)) `AGPLv3` `PHP` 
  * [MyBB](http://www.mybb.com/) - Free, extensible forum software package. ([Source Code](https://github.com/mybb/mybb)) `LGPLv3` `PHP` 
  * [Newebe](http://newebe.org/) - A Distributed Social Network. ([Source Code](https://github.com/gelnior/newebe)) `AGPLv3` `Python`
  * [NodeBB](https://nodebb.org/) - Node.js based forum software built for the modern web. ([Source Code](https://github.com/NodeBB/NodeBB)) `GPLv3` `Nodejs`
  * [Oxwall](http://www.oxwall.org/) Oxwall is used for a wide range of projects starting from family sites and custom social networks to collaboration tools and enterprise community solutions. ([Source Code](https://bitbucket.org/oxwall/public) `CPALv1` `PHP`
  * [phpBB](https://www.phpbb.com/) - Flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. ([Source Code](https://github.com/phpbb/phpbb)) `GPLv2` `PHP`
  * [PPnet](https://github.com/pixelpark/ppnet) Create and host your own social network. `MIT` `JavaScript`
  * [Pump.io](http://pump.io/) - Stream server that does most of what people really want from a social network. ([Source Code](https://github.com/e14n/pump.io)) `Apache` `JavaScript, NodeJS`
  * [Reddit](https://www.reddit.com/) - Social networking and news website where registered community members can submit content. ([Demo](https://www.reddit.com/) [Source Code](https://github.com/reddit/reddit)) `CPALv1` `Python`
  * [RedMatrix](https://github.com/redmatrix/redmatrix) - Complete decentralised publishing, sharing, and communications system. `MIT` `PHP`
  * [twister](http://twister.net.co/) - P2P microblogging platform. ([Source Code](https://github.com/miguelfreitas/twister-core)) `GPLv2` `PHP`
  * [Vanilla Forums](https://vanillaforums.org/) - Simple and flexible forum software. ([Source Code](https://github.com/vanilla/vanilla)) `GPLv2` `PHP`


### XMPP

_[Extensible Messaging and Presence Protocol](https://en.wikipedia.org/wiki/XMPP) software_

#### XMPP Servers

  * [ejabberd](https://www.ejabberd.im/) - XMPP instant messaging server. ([Source Code](https://github.com/processone/ejabberd)) `GPL` `Erlang`
  * [Metronome IM](https://lightwitch.org/metronome) - Fork of Prosody IM. ([Source Code](http://code.lightwitch.org/)) `MIT` `Lua`
  * [MongooseIM](https://www.erlang-solutions.com/products/mongooseim.html) - Fork of ejabberd. ([Source Code](https://github.com/esl/MongooseIM)) `MIT` `Erlang`
  * [Openfire](http://www.igniterealtime.org/projects/openfire/) - Real time collaboration (RTC) server. ([Source Code](https://github.com/igniterealtime/Openfire)) `Apache` `Java`
  * [Prosody IM](http://prosody.im/) - Feature-rich and easy to configure XMPP server. ([Source Code](http://hg.prosody.im/)) `MIT` `Lua`
  * [Tigase](http://www.tigase.net/content/tigase-xmpp-server) - XMPP server implementation in Java. `Java`


#### XMPP Web Clients

  * [Candy](http://candy-chat.github.io/candy/) - Multi user XMPP client written in Javascript. ([Source Code](https://github.com/candy-chat/candy)) `MIT` `JavaScript`
  * [Converse.js](https://conversejs.org/) - A free and open-source XMPP chat client in your browser. ([Source Code](https://github.com/jcbrand/converse.js)) `MPLv2` `Javascript`
  * [Kaiwa](http://getkaiwa.com/) - Web based chat client in the style of common paid alternatives. ([Source Code](https://github.com/digicoop/kaiwa)) `MIT` `Javascript, NodeJS`
  * [Kontalk](http://kontalk.org/) – Kontalk is an Open Source Messenger, similiar to WhatsApp (app for android only currently), including end-to-end encryption, server is based on Tigase XMPP Server - ([Source Code](https://github.com/kontalk)) `GPLv3`
  * [Salut à Toi](http://www.salut-a-toi.org/) - Multipurpose, multi frontend, libre and decentralised communication tool. ([Source Code](http://repos.goffi.org/sat)) `AGPLv3` `Python`
    * [Libervia](http://wiki.goffi.org/wiki/Libervia/en) - Web frontend from Salut à Toi. ([Source Code](http://repos.goffi.org/libervia)) `AGPLv3` `Python`


## Content Management Systems (CMS)

CMS are a practical way to setup a website with many features. CMS often come with third party plugins, themes and functionality that is easy to add and customize to your needs. See also [Blogging Platforms](#blogging-platforms) and [Static Site Generators](#static-site-generators)

  * [99ko CMS](http://www.99ko.org/) - 99ko allows you to create a website in minutes without knowledge of Web development. It does not use a database server but relies on simple text files (JSON format) to store your data. ([Source Code](https://github.com/99ko-project/99ko-cms))
  * [Apostrophe 2](http://apostrophenow.org/) - A node.js CMS with a focus on extensible in-context editing tools. ([Demo](http://demo.apostrophenow.com/), [Source Code](https://github.com/punkave/apostrophe)) `MIT` `NodeJS`
  * [Baun](http://bauncms.com/) - A modern, lightweight, extensible CMS for PHP. ([Source Code](https://github.com/BaunCMS/Baun)) `MIT` `PHP`
  * [BigTree CMS](https://www.bigtreecms.org/) - Straightforward, well documented, and capable written with PHP and MySQL. ([Source Code](https://github.com/bigtreecms/BigTree-CMS)) `LGPL` `PHP`
  * [Bolt](https://bolt.cm/) - Sophisticated, lightweight & simple CMS. ([Source Code](https://github.com/bolt/bolt)) `MIT` `PHP`
  * [CMS Made Simple](http://www.cmsmadesimple.org/) - Open source content management system, faster and easier management of website contents, scalable for small businesses to large corporations. ([Source Code](http://svn.cmsmadesimple.org/svn/cmsmadesimple/trunk/)) `GPL` `PHP`
  * [Concrete 5 CMS](http://www.concrete5.org/) - An open source content management system. ([Source Code](https://github.com/concrete5/concrete5)) `MIT` `PHP`
  * [Drupal](https://www.drupal.org/) - Advanced open source content management platform. ([Source Code](http://cgit.drupalcode.org/drupal)) `GPL` `PHP`
  * [Gazelle](https://github.com/WhatCD/Gazelle) - Gazelle is a web framework geared towards private BitTorrent trackers. Although naturally focusing on music, it can be modified for most needs. `unlicensed` `PHP`
  * [Grav](https://getgrav.org/) - Modern, Crazy Fast, Ridiculously Easy and Amazingly Powerful Flat-File CMS. ([Source Code](https://github.com/getgrav/grav)) `MIT` `PHP`
  * [GetSimple CMS](http://get-simple.info/) - The Simplest Content Management System. Ever. `GPLv3`
  * [ImpressPages CMS](https://www.impresspages.org/) - Easy code meets easy admin. ([Demo](https://www.impresspages.org/demo), [Source Code](https://github.com/impresspages/ImpressPages)) `GPLv3`/`MIT`  `PHP`
  * [Joomla!](https://www.joomla.org/) - Advanced Content Management System (CMS). ([Source Code](http://joomlacode.org/gf/project/joomla/scmsvn/)) `GPL` `PHP`
  * [KeystoneJS](http://keystonejs.com/) - Node.js CMS & Web Application Platform. ([Demo](http://demo.keystonejs.com/), [Source Code](https://github.com/keystonejs/keystone)) `MIT` `NodeJS`
  * [MODX](http://modx.com/) - MODX is an advanced content management and publishing platform. The current version is called 'Revolution'. ([Source Code](https://github.com/modxcms/revolution)) `GPLv2` `PHP`
  * [Neos](https://www.neos.io) - Neos or TYPO3 Neos (for version 1) is a modern, open source CMS based on the Flow framework. ([Source Code](https://git.typo3.org/Packages/TYPO3.Neos.git)) `GPLv3` `PHP`
  * [october](http://octobercms.com/) - Free, open-source, self-hosted CMS platform based on the Laravel PHP Framework. ([Source Code](https://github.com/octobercms/october)) `MIT` `PHP`
  * [Pagekit](https://pagekit.com/) - A new modern CMS to create and share. ([Source Code](https://github.com/pagekit/pagekit)) `MIT` `PHP`
  * [Pico](http://picocms.org/) - A stupidly simple, blazing fast, flat file CMS. ([Source Code](https://github.com/picocms/Pico)) `MIT` `PHP`
  * [Pimcore](https://www.pimcore.org/) - Multi-Channel Experience and Engagement Management Platform. ([Source Code](https://github.com/pimcore/pimcore)) `BSD` `PHP`
  * [Plone](https://plone.org/) - Powerful open-source CMS system. ([Source Code](https://github.com/plone)) `Zope` `Python`
  * [Publify](http://publify.co/) - A simple but full featured web publishing software. ([Demo](http://demo.publify.co/), [Source Code](https://github.com/publify/publify)) `MIT` `Ruby`
  * [Redaxscript](http:/redaxscript.com) - Ultra lightweight CMS for MySQL, SQLite and PostgreSQL. ([Demo](http://demo.redaxscript.com/demo/login), [Source Code](https://github.com/redaxmedia/redaxscript)) `GPLv3` `PHP`
  * [SilverStripe](https://www.silverstripe.org) - Easy to use CMS with powerful MVC framework underlying. ([Demo](http://demo.silverstripe.org/), [Source Code](https://github.com/silverstripe)) `BSD` `PHP`
  * [Sphido](http://www.sphido.org/) - A fast, lightweight, flat file CMS for PHP. ([Source Code](https://github.com/sphido/cms)) `MIT` `PHP`
  * [SPIP](http://www.spip.net/fr) - Publication system for the Internet aimed at collaborative work, multilingual environments, and simplicity of use for web authors. ([Source Code](https://core.spip.net/projects/spip/repository)) `GPLv2` `PHP`
  * [Textpattern](http://textpattern.com/) - A flexible, elegant and easy-to-use CMS. ([Demo](http://textpattern.co/demo), [Source Code](https://github.com/textpattern/textpattern)) `GPLv2` `PHP`
  * [TYPO3](https://typo3.org/) - A powerful and advanced CMS with a large community. ([Source Code](https://github.com/TYPO3/TYPO3.CMS)) `GPLv2` `PHP`
  * [Wordpress](https://wordpress.org/) - The worlds most-used blogging and CMS engine. ([Source code mirror](https://github.com/WordPress/WordPress)) `GPLv2`

_Recipe management_

  * [OpenEats](http://www.openeats.org/) - A recipe management site that allows users to create, store, share and rate recipes, create grocery lists, and more. ([Source Code](https://github.com/qgriffith/OpenEats)) `BSD` `Python/Django`

### E-commerce

* [OpenCart](https://www.opencart.com) - Free open source shopping cart solution. ([Source Code](https://github.com/opencart/opencart)) `GPLv3` `PHP`
* [Open Classifieds](http://open-classifieds.com/) - Free open-source, self-hosted CMS for classifieds sites. ([Source Code](https://github.com/open-classifieds/openclassifieds2))  `GPL` `PHP`
* [Open eShop](https://open-eshop.com/) - Sell your digital goods with licenses and provide support. ([Source Code](https://github.com/open-classifieds/open-eshop))  `GPL` `PHP`
* [PrestaShop](https://www.prestashop.com/) - PrestaShop offers a free, open-source and fully scalable e-commerce solution. ([Demo](http://demo.prestashop.com/), [Source Code](https://github.com/PrestaShop/PrestaShop)) `OSL 3.0` `PHP`
* [Shoop](https://www.shoop.io/) - Django powered fully customizable open source e-commerce framework for small and large sites. ([B2C demo](https://demo1.shoop.io/), [B2B demo](https://demo2.shoop.io/), [Source Code](https://github.com/shoopio/shoop)) `AGPLv3` `Python`
* [WooCommerce](https://www.woothemes.com/woocommerce/) - WordPress based e-commerce solution. ([Source Code](https://github.com/woothemes/woocommerce)) `GPL` `PHP`


## Document Archiving

  * [CUPS](https://www.cups.org/) - The Common Unix Print System uses Internet Printing Protocol (IPP) to support printing to local and network printers. ([Source Code](https://www.cups.org/software.php)) `GPLv2` `C`
  * [Paperless](https://github.com/danielquinn/paperless) - Scan, index, and archive all of your paper documents. `GPLv3` `Python`
  * [SANE Network Scanning](http://sane-project.org/) - allow remote clients to access image acquisition devices (scanners) available on the local host. ([Source Code](http://www.sane-project.org/cvs.html)) `GPLv2` `C`


## Enterprise Resource Planning

* [Odoo](http://odoo.com) - Free open source ERP system. ([Source Code](https://github.com/odoo/odoo)), ([Demo](https://demo.odoo.com/)) `LGPLv3` `Python`


## Federated Identity/Authentication

  * [FreeRADIUS](http://freeradius.org/) - High performance and highly configurable multi-protocol policy/authentication server, supporting RADIUS, DHCPv4 and VMPS. ([Source Code](https://github.com/FreeRADIUS/freeradius-server)) `GPLv2` `C`
   * [daloRADIUS](http://www.daloradius.com) - Open-source web management platform for FreeRADIUS-based deployments. ([Source Code](https://github.com/lirantal/daloradius)) `GPLv2`
  * [IndieAuth](https://indieauth.com) - Sign in with your domain name (using the [rel-me-auth](http://microformats.org/wiki/relmeauth) protocol). `Apache` `Ruby`
  * [Libravatar](https://www.libravatar.org/) - Libravatar is a service which delivers your avatar (profile picture) to other websites. ([Demo](https://www.libravatar.org/account/new/), [Source Code](https://github.com/libravatar/libravatar)) `AGPLv3` `Python`
  * [OpenCA OCSPD](https://pki.openca.org/projects/ocspd/) - An [OCSP](https://en.wikipedia.org/wiki/Online_Certificate_Status_Protocol) Responder.
  * [OpenID/OpenID Connect](http://openid.net/developers/libraries/) - A Simple Identity layer on top of OAuth 2.0
  * [OSIAM](https://www.osiam.org) - Open Source Identity and Access Management implementing OAuth 2.0 and SCIMv2. ([Source Code](https://github.com/osiam/osiam)) `MIT` `Java`


## Feed Readers

  * [Cacocloud](https://github.com/Cacodaimon/CacoCloud) - A simple, fast and secure PHP/AngularJS based feed and mail reader, password and bookmark manager.
  * [CommaFeed](https://www.commafeed.com/) - Google Reader inspired self-hosted RSS reader. ([Source Code](https://github.com/Athou/commafeed))
  * [Creaky Coot](https://github.com/piero-la-lune/Creaky-Coot) - Minimalist and responsive RSS reader and links saver
  * [Feedbin](https://feedbin.com/) - A simple, fast and nice looking RSS reader. ([Source Code](https://github.com/feedbin/feedbin))
  * [FeedHQ](https://feedhq.org/) - FeedHQ is a web-based feed reader. ([Source Code](https://github.com/feedhq/feedhq))
  * [FreshRSS](http://freshrss.org/) - A self-hostable RSS feed aggregator. ([Demo](http://demo.freshrss.org/i/), [Source Code](https://github.com/FreshRSS/FreshRSS), [Mobile app](https://github.com/Alkarex/EasyRSS)) `AGPLv3`
  * [Kriss Feed](http://tontof.net/kriss/feed/) - A simple and smart (or stupid) feed reader. ([Demo](http://tontof.net/feed/), [Source Code](https://github.com/tontof/kriss_feed/))
  * [Leed](http://leed.idleman.fr) - Leed (for Light Feed) is a Free and minimalist RSS aggregator. ([Source Code](https://github.com/ldleman/Leed))
  * [Leselys](https://github.com/socketubs/leselys) - Your very elegant RSS reader
  * [Lite-Reader](http://cubny.com/lite-reader/) - Read your feeds on your own machine with a simple and lite application. ([Source Code](https://github.com/cubny/lite-reader))
  * [Moonmoon](http://moonmoon.org/) - simple feed agregator (planet like): it only aggregates feeds and spits them out in one single page. ([Source Code](https://github.com/mauricesvay/moonmoon)) `BSD` `PHP`
  * [Miniflux](https://miniflux.net/) - Miniflux is a minimalist and open source news reader. ([Source Code](https://github.com/miniflux/miniflux))
  * [NewsBlur](https://github.com/samuelclay/NewsBlur) - NewsBlur is a personal news reader that brings people together to talk about the world. A new sound of an old instrument
  * [Nunux Reader](http://reader.nunux.org/) - A simple, fast and reactive RSS reader. ([Source Code](https://github.com/ncarlier/nunux-reader)) `GPLv3` `Nodejs`
  * [Reader-Self](http://readerself.com/) Self-hosted rss reader (php / mysql or sqlite) - Google Reader alternative. ([Source Code](https://github.com/readerself/readerself))
  * [Readr](https://github.com/pabloprieto/Readr) - A clean & simple, self-hosted RSS reader
  * [RSS2EMail](http://www.allthingsrss.com/rss2email/) - Fetches RSS/Atom-feeds and pushes new Content to any email-reciever, supports OPML `GPL` `Python`
  * [RSSminer](http://www.rssminer.net/) -An online rss reader written in clojure & javascript & java. ([Source Code](https://github.com/shenfeng/rssminer))
  * [RSS Monster](https://github.com/pietheinstrengholt/rssmonster) - RSS Monster is an easy to use web-based RSS aggregator and reader compatible with the Fever API, created as an alternative for Google Reader. `MIT` `PHP`
  * [Screaming Liquid Tiger](https://github.com/herrbischoff/screaming-liquid-tiger) - Simple script to automatically generate valid RSS and Atom feeds from a list of media files in the same folder. `MIT` `PHP`
  * [Selfoss](http://selfoss.aditu.de/) - The new multipurpose rss reader, live stream, mashup, aggregation web application. ([Source Code](https://github.com/SSilence/selfoss)) `AGPLv3` `PHP`
  * [Stringer](https://github.com/swanson/stringer) - A work-in-progress self-hosted, anti-social RSS reader. `MIT` `Ruby`
  * [Tiny Tiny RSS](https://tt-rss.org/gitlab/fox/tt-rss) - Open source web-based news feed (RSS/Atom) reader and aggregator. ([Public instance](http://framanews.org/)) `GPLv3` `PHP`
    * [gritttt-rss](http://gritttt-rss.nicolashoening.de/) - More features for Tiny Tiny RSS. ([Source Code](https://github.com/nhoening/gritttt-rss)) `BSD` `Python`
    * [ttrss-mobile](https://github.com/mboinet/ttrss-mobile) - A mobile webapp for Tiny Tiny RSS. `AGPLv3` `Nodejs`



## File Sharing and Synchronization

Some [Groupware](#groupware) solutions also feature file sharing and synchronization.


#### Distributed filesystems

  * [Camlistore](https://camlistore.org/) - Camlistore is a set of open source formats, protocols, and software for modeling, storing, searching, sharing and synchronizing data in the post-PC era. Data may be files or objects, tweets or 5TB videos, and you can access it via a phone, browser or FUSE filesystem. ([Source Code](https://github.com/camlistore/camlistore)) `Apache` `Go`
  * [Go IPFS](https://github.com/ipfs/go-ipfs) - Implementation of [IPFS](http://ipfs.io/), a global, versioned, peer-to-peer filesystem that seeks to connect all computing devices with the same system of files. It combines good ideas from Git, BitTorrent, Kademlia, SFS, and the Web. It is like a single bittorrent swarm, exchanging git objects.
  * [Ori Filesystem](http://ori.scs.stanford.edu/) - A Secure Distributed File System built for offline operation. ([Source Code](https://bitbucket.org/orifs/ori/wiki/Home)) `MIT` `C++`
  * [Swift](http://docs.openstack.org/developer/swift/) - A highly available, distributed, eventually consistent object/blob store.
  * [Tahoe-LAFS](https://www.tahoe-lafs.org/trac/tahoe-lafs) - Tahoe-LAFS is a Free and Open decentralized cloud storage system. It distributes your data across multiple servers. Even if some of the servers fail or are taken over by an attacker, the entire file store continues to function correctly, preserving your privacy and security.


#### File transfer/synchronization

  * [Git Annex](http://git-annex.branchable.com/assistant/quickstart/) - File synchronization between computers, servers, external drives
  * [OpenSSH/SFTP](http://www.openssh.com/) - Secure File Transfer Program. ([Source Code](http://cvsweb.openbsd.org/cgi-bin/cvsweb/src/usr.bin/ssh)) `BSD` `C`
  * [Samba](https://www.samba.org/) - Samba is the standard Windows interoperability suite of programs for Linux and Unix. It provides secure, stable and fast file and print services for all clients using the SMB/CIFS protocol. ([Source Code](https://git.samba.org/samba.git/)) `GPLv3` `C`
  * [Seafile](https://www.seafile.com/en/home/) - File hosting and sharing solution primary for teams and organizations. ([Demo](https://seacloud.cc/demo)) `GPLv2`
  * [SparkleShare](http://sparkleshare.org/) - Self hosted, instant, secure file sync
  * [Syncany](https://www.syncany.org/) - Secure file sync software for arbitrary storage backends - An open-source cloud storage and filesharing application. Securely synchronize your files to any kind of storage! `GPLv3` `Java`
  * [Syncthing](https://syncthing.net/) - Syncthing is an open source peer-to-peer file synchronisation tool. ([Source Code](https://github.com/syncthing/syncthing)) `MPLv2` `Go`
  * [Z-Push](https://z-push.org/) - An implementation of Microsoft’s [ActiveSync](https://en.wikipedia.org/wiki/ActiveSync) protocol
  * [ownCloud](https://owncloud.org/) - All-in-one solution for saving, synchronizing, viewing, editing and sharing files, calendars, address books and more - `AGPLv3` `PHP`
  * [Pydio](https://pyd.io/) - Turn any web server into a powerful file management system and an alternative to mainstream cloud storage providers.


#### Peer-to-peer filesharing

  * [FilePizza](http://file.pizza/) - Peer-to-peer file transfers in your browser. ([Source Code](https://github.com/kern/filepizza)) `BSD` `Nodejs`
  * [FileTea](https://filetea.me/) - Anonymous, volatile file sharing: does not store any file on server. Bridges a download to the recipient’s browser with an upload from the source’s browser. ([Source Code](https://github.com/elima/FileTea) `AGPLv3` `C`
  * [instant.io](https://github.com/feross/instant.io) - Streaming file transfer over WebTorrent. ([Demo](https://instant.io)) `MIT` `Nodejs`
  * [Opentracker](http://erdgeist.org/arts/software/opentracker/) - Open and free bittorrent tracker. It aims for minimal resource usage and is intended to run at your wlan router. ([Source Code](http://erdgeist.org/gitweb/opentracker/) `Public domain` `C`
  * [ShareFest](https://github.com/peer5/sharefest) - Web based p2p file sharing built on WebRTC Data Channels API. ([Demo](https://www.sharefest.me/)) `Apache 2.0` `Nodejs`


#### Single-click/drag-n-drop upload

  * [BoZoN](https://github.com/broncowdd/BoZoN) - Minimalist Drag & drop file sharing app. `AGPLv3` `PHP`
  * [Coquelicot](https://coquelicot.potager.org/) - Coquelicot is a “one-click” file sharing web application with a focus on protecting users’ privacy. - `AGPLv3`
  * [Dropcenter](http://projet.idleman.fr/dropcenter/) - Upload files by simple drag-n-drop.
  * [droppy](https://github.com/silverwind/droppy) - droppy is a self-hosted cloud server with an interface similar to desktop file managers and has capabilites to edit files on-the-fly as well as view and playback media directly in the browser. ([Demo](http://droppy.silverwind.io/)) `BSD` `Nodejs`
  * [img.bi](https://github.com/imgbi/img.bi) - img.bi is a secure image hosting. Images are encrypted using AES-256 with random key in browser before upload. `GPLv3` `Nodejs`
  * [ipfs.pics](https://ipfs.pics/) - ipfs.pics is a o distributed image hosting website. ([Source Code](https://github.com/ipfspics/server)) `AGPL` `PHP`
  * [Jirafeau](https://gitlab.com/mojo42/Jirafeau/wikis/home) - Jirafeau is a web site permitting to upload a file in a simple way and give an unique link to it. ([Demo](http://jirafeau.net/))
  * [Jyraphe](http://home.gna.org/jyraphe/) - Jyraphe is a web application of file repository, easy to install and easy to use.
  * [linx](https://github.com/andreimarcu/linx-server) - File sharing application and pastebin with API, auto-expiry, deletion keys, and web seed support. ([Demo](https://linx.li/)) `GPLv3` `Go`
  * [lutim](https://github.com/ldidry/lutim) - Let's Upload That Image !
  * [Mediacrush](https://mediacru.sh/) - A website you can upload images, audio, and video to, and receive a link to share it with your friends. ([Source Code](https://github.com/MediaCrush/MediaCrush))
  * [Nimbus](https://github.com/ethanal/nimbus) - A drag-and-drop shortlink file sharer for OS X - `MIT` `Python`
  * [OnionShare](https://onionshare.org/) - Securely and anonymously share a file of any size.
  * [PictShare](https://www.pictshare.net/) - PictShare is a multi lingual, open source image hosting service with a simple resizing and upload API. ([Demo](https://www.pictshare.net/), [Source Code](https://github.com/chrisiaut/pictshare)) `Apache` `PHP/JavaScript`
  * [Pomf](https://github.com/nokonoko/Pomf) - Simple file uploading and sharing, source for the now shut down site Pomf.se. `MIT` `PHP/Nodejs`
  * [ProjectSend](http://www.projectsend.org/) - Upload files and assign them to specific clients you create. Give access to those files to your clients. ([Source Code](https://github.com/ignacionelson/ProjectSend)) `GPLv2` `PHP`
  * [Up1](https://github.com/Upload/Up1) - A Client-side Encrypted Image Host. ([Demo](https://up1.ca/)) `MIT` `Nodejs`
  * [uPste](https://u.pste.pw) - A private file hosting application with an emphasis on serving technology communities. ([Source Code](https://github.com/TheReverend403/uPste)) `AGPLv3` `PHP`
  * [YouTransfer](http://www.youtransfer.io) - YouTransfer is a simple but elegant self-hosted file transfer & sharing solution. ([Demo](http://demo.youtransfer.io/), [Source Code](https://github.com/remie/YouTransfer)) `Apache` `Nodejs`


#### Web based file managers

  * [Apaxy](http://adamwhitcroft.com/apaxy/) - Theme built to enhance the experience of browsing web directories, using the mod_autoindex Apache module and some CSS to override the default style of a directory listing. ([Source Code](https://github.com/AdamWhitcroft/Apaxy) `Public domain` `CSS`
  * [eXtplorer](http://extplorer.sourceforge.net/) - A PHP and JavaScript based File Manager
  * [h5ai](https://larsjung.de/h5ai/) - Modern file indexer for HTTP web servers with focus on your files. Directories are displayed in a appealing way and browsing them is enhanced by different views, a breadcrumb and a tree overview. ([Source Code](https://github.com/lrsjng/h5ai), [Demo](https://larsjung.de/h5ai/demo/)) `MIT` `PHP/Javascript`


## Games

  * [20euros](https://github.com/jatekos101/20euros) - Clone of 2048 game with euros. - Unlicensed
  * [Agar.IO Clone](https://github.com/huytd/agar.io-clone) - Agar.io clone written with Socket.IO and HTML5 canvas - `MIT`
  * [Cubiks-2048](https://github.com/Kshitij-Banerjee/Cubiks-2048) - Clone of 2048 game in 3D. - `CCANC 4.0`
  * [TournamentMango](http://tournamentmango.com/) - TournamentMango is an open source tournament bracket and user management system. You can build an archive of players and keep track of all their scores over time as well as their regular characters, games, and aliases. ([Source Code](https://github.com/seiyria/tournamentmango)) `MIT` `Javascript`


## Gateways

  * [GateOne](https://github.com/liftoff/GateOne/) - Gate One is an HTML5 web-based terminal emulator and SSH client. - `AGPLv3`
  * [Guacamole](http://guac-dev.org/) - Guacamole is a clientless remote desktop gateway. It supports standard protocols like VNC and RDP. ([Source Code](https://github.com/glyptodon/)) `MIT` `Java/C`


## Groupware

  * [Citadel](http://www.citadel.org/doku.php) - Groupware including email, calendar/scheduling, address books, forums, mailing lists, IM, wiki and blog engines, RSS aggregation and more. ([Source Code](http://www.citadel.org/doku.php/installation:source)) `GPLv3` `C`
  * [Cozy Cloud](https://cozy.io) - A personal cloud where you can read your emails or manage and sync your contact, files or calendars, with an app store full of community contributions. ([Source Code](https://github.com/cozy)) `GPLv3` `Nodejs`
  * [egroupware](http://www.egroupware.org/) - Software suite including calendars, address books, notepad, project management tools, client relationship management tools (CRM), knowledge management tools, a wiki and a CMS.
  * [Horde](http://www.horde.org/) - The Horde Project is about creating high quality Open Source applications and libraries, based on PHP and the Horde Framework. - `GPL`
  * [Kolab](https://kolab.org/) - Kolab community is a unified communication and collaboration system - `Various FLOSS Licenses` ([Source Code](https://git.kolab.org/))
  * [Mayan EDMS](http://www.mayan-edms.com) - Free Open Source Electronic Document Management System. An electronic vault for your documents with preview generation, OCR, and automatic categorization among other features. ([Demo](http://demo.mayan-edms.com), [Source Code](https://gitlab.com/mayan-edms/mayan-edms)) `Apache` `Python/Django`
  * [Openmeetings](https://openmeetings.apache.org/index.html) - ([Source Code](https://svn.apache.org/viewvc/openmeetings/trunk/singlewebapp/)) - Openmeetings provides video conferencing, instant messaging, white board, collaborative document editing and other groupware tools using API functions of the Red5 Streaming Server for Remoting and Streaming. `Apache 2.0`  `Java`
  * [Sogo](http://www.sogo.nu/) - SOGo offers multiple ways to access the calendaring and messaging data. CalDAV, CardDAV, GroupDAV, as well as ActiveSync, including native Outlook compatibility and web interface. ([Demo](http://www.sogo.nu/tour/online_demo.html), [Source Code](http://www.sogo.nu/development/source_code.html)) `GPLv1/LGPLv2` `Objective-C`
  * [Tine 2.0org](https://www.tine20.org) - Contacts, Calendar, Tasks, WebDAV, ActiveSync, VOIP, Mail-Client, CRM, Sales, Projects, Timetracker - ([Demo](https://demo.tine20.net)) `AGPLv3`
  * [Zimbra Collaboration](https://www.zimbra.com/downloads/) - Email, calendar, collaboration server with web interface and lots of integrations.  ([Source Code]( https://www.zimbra.com/open-source-email-overview/)) `GPLv2/CPALv1` `Java`


## Learning and Courses

  * [Chamilo LMS](https://chamilo.org/chamilo-lms/) - Chamilo LMS allows you to create a virtual campus for the provision of online or semi-online training. ([Source Code](https://github.com/chamilo/chamilo-lms)) `GPLv3` `PHP`
  * [edX](https://www.edx.org/) - The Open edX platform is open-source code that powers [edX.org](https://www.edx.org/). ([Source Code](https://github.com/edx/)) `AGPLv3` `Python`
  * [lxHive](http://www.lxhive.com/) - Open Source ExperienceAPI compliant Learning Record Store (LRS) - previously code-named TinCanAPI. [Source Code](https://github.com/Brightcookie/lxHive) `GPLv3` `PHP`
  * [Mahara](https://mahara.org/) - Open Source fully featured web application to build students electronic portfolio. [Source Code](https://github.com/MaharaProject/mahara) `GPLv3` `PHP`
  * [Moodle](https://moodle.org/) - Moodle is a learning and courses platform with one of the largest open source communities worldwide. ([Demo](https://moodle.org/demo/), [Source Code](https://git.moodle.org/gw)) `GPL` `PHP`
  * [Sakai](https://www.sakaiproject.org/) - The Sakai project provides a flexible and feature-rich environment for teaching, learning, research and other collaboration. ([Demo](https://www.sakaiproject.org/try-sakai), [Source Code](https://github.com/sakaiproject/sakai)) `ECLv2` `Java`


## Maps & GPS

  * [Graphhopper](https://graphhopper.com/) - Fast routing library and server using OpenStreetMap. ([Source Code](https://github.com/graphhopper/graphhopper))
  * [MapBBCodeShare](https://github.com/MapBBCode/share.mapbbcode.org) - Tool for sharing custom OSM maps. Support for annotated markers, polygons, lines, multi-format import/export, multiple layers, shortlinks... ([Demo](http://share.mapbbcode.org/)) `WTFPL/Other` `PHP/Javascript`
  * [Openstreetmap](http://www.openstreetmap.org/) - OpenStreetMap is a map of the world, created by people like you and free to use under an open license. ([Source Code](https://github.com/openstreetmap/openstreetmap-website))
  * [Traccar](https://www.traccar.org/) - Java application to track GPS positions. Supports loads of tracking devices and protocols, has an Android and iOS App. Has a web interface to view your trips - ([Demo](http://demo.traccar.org/), [Source Code](https://github.com/tananaev?tab=repositories)) `Apache`
  * [uMap](https://umap.openstreetmap.fr/en/) - Create maps with OpenStreetMap layers in a minute and embed them in your site. ([Source Code](https://github.com/umap-project/umap)) `WTFPL` `Python/Django`

## Video Streaming

  * [CyTube](https://github.com/calzoneman/sync) - CyTube is a web application providing media synchronization, chat, and more for an arbitrary number of channels. ([Demo](http://cytu.be)) `MIT` `Nodejs`
  * [Emby](https://github.com/MediaBrowser/Emby) - A home media server built using other popular open source technologies. - `GPLv2`
  * [Flumotion](http://flumotion.net/) - A streaming media server with intuitive graphical administration tools. ([Source Code](https://github.com/Flumotion/flumotion)) `LGPLv2` `Python`
  * [HTPC Manager](http://htpc.io/) - A fully responsive interface to manage all your favorite media on your HTPC. - `MIT`
  * [ReadyMedia](http://sourceforge.net/projects/minidlna/) - A simple media server software, with the aim of being fully compliant with DLNA/UPnP-AV clients. `GPLv2` `C`
  * [Restreamer](https://datarhei.github.io/restreamer/) - Restreamer allows you to do h.264 real-time video streaming on your website without a streaming provider. ([Source Code](https://github.com/datarhei/restreamer)) `Apache` `Nodejs`
  * [Rygel](https://wiki.gnome.org/action/show/Projects/Rygel) - Rygel is a home media solution (UPnP AV MediaServer) that allows you to easily share audio, video and pictures to other devices. Additionally, media player software may use Rygel to become a MediaRenderer that may be controlled remotely by a UPnP or DLNA Controller. `GPLv3` `C`
  * [Streama](https://github.com/dularion/streama) - Self-hosted Netflix alternative. - `MIT` `Java`
  * [Zoneminder](https://github.com/ZoneMinder/ZoneMinder) - Closed-circuit television (CCTV) software application which supports IP, USB and Analog cameras. `GPLv2` `PHP`

## Mind Maps

 * [Mindmaps](https://github.com/drichard/mindmaps) - An open source, offline capable, mind mapping application. ([Demo](http://drichard.org/mindmaps/))


## Money, Budgeting and Management

  * [Galette](http://galette.eu/dc/) - Galette is a membership management web application towards non profit organizations. ([Source Code](http://git.tuxfamily.org/galette/galette.git/)) `GPLv3` `PHP`
  * [GLPI](http://www.glpi-project.org/spip.php?lang=en) - GLPI is an IT assests/resources/inventory manager. ([Source Code](https://forge.glpi-project.org/projects/glpi)) `GPLv2` `PHP`
  * [GRR](http://grr.devome.com/?lang=en) - Assets management and booking for small/medium companies. ([demo](http://grr.devome.com/demo/week_all.php?year=2015&month=07&day=28&area=94), _administrateur/azerty_) `GPLv2` `PHP`
  * [Inventaire](https://inventaire.io/welcome) - Collaborative resources mapper project, while yet only focused on exploring books mapping with wikidata and ISBNs. ([Source Code](https://github.com/inventaire/inventaire)) `AGPLv3` `Nodejs`
  * [Invoice Ninja](https://www.invoiceninja.com/) - A powerful tool to invoice clients online. ([Demo](https://app.invoiceninja.com/invoices/create), [Source Code](https://github.com/invoiceninja/invoiceninja)) `AAL` `PHP`
  * [InvoicePlane](https://invoiceplane.com/) - Manage quotes, invoices, payments and customers for your small business. ([Demo](https://demo.invoiceplane.com), [Source Code](https://github.com/InvoicePlane/InvoicePlane)) `MIT`
  * [IHateMoney](http://ihatemoney.org/) - Manage your shared expenses, easily. ([Source Code](https://github.com/spiral-project/ihatemoney)) `BSD` `Python`
  * [Tryton](http://www.tryton.org/) - Core base of a complete business solution (ERP). ([Demo](http://demo.tryton.org) admin/admin, [Source Code](https://hg.tryton.org)) `GPLv3` `Python`
  * [Koha](https://koha-community.org/) - Fully featured, scalable library management system (integrated library system - ILS). ([Source Code](https://github.com/Koha-Community/Koha)) `GPLv3` `Perl`
  * [StockazNG](https://dev.sigpipe.me/dashie/StockazNG) - Asset Management System. `MIT` `Python`


## Monitoring and Administration

  * [Prometheus](http://prometheus.io/) - Monitoring system and time series database. ([Source Code](https://github.com/prometheus/prometheus)) `Apache` `Go`
  * [psdash](https://github.com/Jahaja/psdash) - A linux system information web dashboard using psutils and flask
  * [pyDash](https://github.com/k3oni/pydash) - Small web-based monitoring dashboard for linux. ([Demo](http://pydash.hostechs.com/main/) - _admin/admin_)
  * [sensu](https://sensuapp.org/) - Monitor servers, services, application health, and business KPIs. Get notified about failures before your users do. Collect and analyze custom metrics. `MIT`
   * [uchiwa](https://uchiwa.io/) - Simple dashboard for sensu


## Music Streaming

  * [Ampache](http://ampache.org/) - A web based audio/video streaming application. ([Demo](http://play.dogmazic.net/), [Source Code](https://github.com/ampache/ampache)) `AGPLv3` `PHP`
  * [CherryMusic](http://www.fomori.org/cherrymusic/) - Minimalistic Web-Mediaplayer. ([Source Code](https://github.com/devsnd/cherrymusic)) `GPLv3` `Python`
  * [cloudtunes](https://github.com/jkbrzt/cloudtunes) - Web-based music player for the cloud. `MIT` `Python/Javascript`
  * [GNU FM](https://gnu.io/fm/) - Running music community websites, alternative to last.fm. ([Source Code](http://git.savannah.gnu.org/cgit/librefm.git/)) `GPLv3` `PHP`
  * [Groove Basin](http://groovebasin.com/) - A music player server with a web-based user interface inspired by Amarok 1.4 ([Source Code](https://github.com/andrewrk/groovebasin)) `MIT` `Nodejs`
  * [koel](http://koel.phanan.net/) - A personal music streaming server that works. ([Source Code](https://github.com/phanan/koel)) `MIT` `PHP`
  * [Mopidy](http://mopidy.readthedocs.org/) - Extensible music server. Offers a superset of the mpd API, as well as integration with 3rd party services like Spotify, SoundCloud etc. ([Source Code](https://github.com/mopidy/mopidy)) `Apache` `Python`
  * [mpd](http://www.musicpd.org/) - Daemon to remotely play music, stream music, handle and organize playlists. Many clients available. `GPLv2` `C++`
  * [Sonerezh](https://www.sonerezh.bzh/) - A self-hosted, web-based application for stream your music, everywhere. ([Demo](https://www.sonerezh.bzh/demo/), [Documentation](https://www.sonerezh.bzh/docs/), [Source Code](https://github.com/sonerezh/sonerezh)) `GPLv3` `PHP`
  * [Subsonic](http://subsonic.org/) - Open-source web-based media streamer and jukebox. ([Demo](http://demo.subsonic.org/login.view?user=guest4&password=guest), [Source Code](https://github.com/EugeneKay/subsonic)) `GPLv3` `Java`


## Note-taking & Editors

  * [dillinger](http://dillinger.io/) - The last Markdown editor, ever. ([Source Code](https://github.com/joemccann/dillinger/)) `MIT` `Nodejs`
  * [Jotter](https://github.com/yosko/jotter) - Jotter is a lightweight, no database, powerful web notebook that lets you create and manage notes online safely, quickly & easily. ([Demo](http://tools.yosko.net/demos/jotter/) - `demo/demo`)
  * [Laverna](https://laverna.cc/) - Laverna is a JavaScript note taking application with Markdown editor and encryption support. Consider it like open source alternative to Evernote. ([Source Code](https://github.com/Laverna/laverna), [Demo](https://laverna.cc/index.html#notes))
  * [minimalist-web-notepad](https://github.com/pereorga/minimalist-web-notepad) - A minimalist http://notepad.cc clone. `Apache` `PHP`
  * [notes](https://github.com/SSilence/notes) - Simple script for personal notes with a single page with a WYSIWYG Editor. `GPLv3` `PHP`
  * [OpenNote](https://github.com/FoxUSA/OpenNote) - OpenNote was built to be an open web-based alternative to Microsoft OneNote (T) and EverNote.
  * [Paperwork](http://paperwork.rocks) - OpenSource note-taking & archiving alternative to Evernote, Microsoft OneNote & Google Keep. ([Source Code](https://github.com/twostairs/paperwork))
  * [Turtl](https://turtl.it/) - A totally private personal database and note taking app. ([Source Code](https://github.com/turtl)) `GPLv3` `CommonLisp`


## Office Suites

  * [EtherCalc](https://ethercalc.org/) - Web spreadsheet. - `CPALv1`
  * [Etherpad](http://etherpad.org/) - Etherpad is a highly customizable Open Source online editor providing collaborative editing in really real-time. - `Apache`
  * [Infinoted](https://github.com/gobby/gobby/wiki/Dedicated%20Server) - A server for [Gobby](https://github.com/gobby/gobby/wiki), a multi-platform collaborative text editor. ([Source Code](https://github.com/gobby/gobby)) `MIT` `C++`
  * [ONLYOFFICE](http://onlyoffice.org/) - An office suite that enables you to manage documents, projects, team and customer relations in one place. ([Source Code](https://github.com/ONLYOFFICE/DocumentServer)) `AGPLv3` `Nodejs`
  * [PHPOffice](http://phpoffice.github.io/) - PHPOffice contains libraries which permits to write and read files from most office suites. `LGPLv3` `PHP`
  * [WebODF](http://webodf.org/) - Tools and libraries to view and edit Open Document Format (ODF) files. ([Source Code](https://github.com/kogmbh/WebODF)) `AGPLv3` `Javascript`
  * [ownCloud documents](https://doc.owncloud.org/server/8.2/user_manual/documents.html) - Collaborative editing and sharing of rich-text documents. ([Source Code](https://github.com/owncloud/documents)) `AGPLv3` `PHP`


## Password Managers

 * [RatticDB](http://rattic.org/) - Password Management for Humans. ([Source Code](https://github.com/tildaslash/RatticWeb), [Demo](https://demo.rattic.org/cred/list/))
 * [Teampass](http://teampass.net/) - Password manager dedicated for managing passwords in a collaborative way on any server Apache, MySQL and PHP. ([Source Code](https://github.com/nilsteampassnet/TeamPass/)) `GPLv3` `PHP`
 * [keeweb](https://antelle.github.io/keeweb/) - This webapp is a browser and desktop password manager compatible with KeePass databases. ([Source Code](https://github.com/antelle/keeweb)) `MIT` `JavaScript`


## Pastebins

  * [0bin](https://github.com/sametmax/0bin) - Client side encrypted pastebin. `WTFPL` `Python`
  * [cryptonote](https://cryptonote.me/) - A simple open source web application that lets users encrypt and share messages that can only be read once. ([Source Code](https://github.com/alainmeier/cryptonote)) `BSD` `Ruby`
  * [gist](https://gitlab.deblan.org/deblan/gist) - GIST is an open-source application to share code. `PHP` `GPLv3`
  * [hastebin](http://hastebin.com/about.md) - Open source pastebin written in node.js. ([Source Code](https://github.com/seejohnrun/haste-server), [Demo](http://hastebin.com/)) `Nodejs` `MIT`
  * [Pastedown](http://pastedown.ctrl-c.us/) - Self-hosted pastebin server. It is meant to handle Markdown well, but it also works with code snippets (and does syntax highlighting). ([Source Code](https://github.com/cespare/pastedown)) `MIT` `Go`
  * [pb](https://github.com/ptpb/pb) - Lightweight pastebin (and url shortener) built using flask. ([Demo](https://ptpb.pw/)) `GPLv3` `Python/Flask`
  * [Phaste](https://pste.pw) - A Phalcon-based, MySQL pastebin application with privacy-respecting Piwik integration and syntax highlighting. ([Source Code](https://github.com/FoxDev/Phaste)) `PHP` `AGPLv3`
  * [snipt](https://snipt.net/) - Long-term memory for coders. Share and store code snippets  ([Source Code](https://github.com/nicksergeant/snipt/)) `BSD` `Python`
  * [Sticky Notes](http://sayakb.github.io/sticky-notes/) - A powerful open-source pastebin application for effortless code sharing. `PHP`
  * [Stikked](https://github.com/claudehohl/Stikked) - An advanced and beautiful pastebin. `PHP` `GPLv3`
  * [tastebin](https://github.com/andreineculau/tastebin) - Updated version of hastebin plus additional features. `Apache` `Nodejs`
  * [ZeroBin](https://github.com/elrido/ZeroBin/wiki) - ZeroBin is a minimalist, opensource online pastebin/discussion board where the server has zero knowledge of hosted data. ([Demo](https://zerobin.dssr.ch/), [Source Code](https://github.com/elrido/ZeroBin)) `Zlib` `PHP`


## Personal Dashboards

  * [Dj Diabetes](https://github.com/foxmask/dj-diabetes) - My Glucose Manager - follow your daily health  `BSD` `Python`
  * [Freeboard](https://freeboard.io) - An open source real-time dashboard builder for IOT and other web mashups. ([Source Code](https://github.com/freeboard/freeboard)) `MIT` `Nodejs`
  * [Habitica](http://habitica.com/) - A habit tracker app which treats your goals like a Role Playing Game. Previously called HabitRPG. ([Source Code](https://github.com/HabitRPG/habitrpg)) `GPLv3/Other` `Nodejs`
  * [Phant](http://phant.io/) - Phant is a modular data logging tool for collecting data from the Internet of Things. ([Demo](https://data.sparkfun.com/), [Source Code](https://github.com/sparkfun/phant)) `GPLv3` `Nodejs`
  * [Reportr](https://github.com/Reportr/dashboard) - Your life's personal dashboard. ([Source Code](https://github.com/Reportr/dashboard))
  * [Thingspeak](https://thingspeak.com/) - An open source “Internet of Things” application and API to store and retrieve data from things using HTTP. ([Demo](https://thingspeak.com/channels/public), [Source Code](https://github.com/iobridge/thingspeak)) `GPL` `Ruby`
  * [Tipboard](http://allegro.tech/tipboard/) - In-house, tasty, local dashboarding system. ([Source Code](https://github.com/allegro/tipboard)) `Apache` `Python`
  * [wger](https://github.com/rolandgeider/wger) - A web-based personal workout, fitness and weight logger/tracker. It can also be used as a simple gym management utility and offers a full REST API as well. ([Demo](https://wger.de)) `AGPLv3` `Python`

## Photo and Video Galleries

  * [CumulusClips](http://cumulusclips.org/) - Your own video sharing website with CumulusClips video sharing script. You can build a YouTube clone where users can upload, rate, comment on videos, and much more.  `GPLv2` `PHP` ([Demo](https://tube.devosi.org/))
  * [Gallery](http://galleryproject.org/) - The simplest, most intuitive way to host your photos on your website. ([Source Code](https://github.com/gallery/gallery3)) `GPLv2` `PHP`
  * [Koken](http://koken.me/) - Content management and web site publishing for photographers. `PHP`
  * [Lychee](http://lychee.electerious.com/) - An open source grid and album based photo-management-system. ([Source Code](https://github.com/electerious/Lychee)) `MIT` `PHP`
  * [MediaDrop](http://mediadrop.net/) - A video, audio and podcast publication platform. ([Source Code](https://github.com/mediadrop/mediadrop)) `GPLv3` `Python`
  * [Mediagoblin](http://mediagoblin.org) - A Free software media publishing platform that anyone can run. You can think of it as a decentralized alternative to Flickr, YouTube, SoundCloud, etc. `AGPLv3` `Python`
  * [MinigalNano](https://github.com/sebsauvage/MinigalNano) - MinigalNano is a very simple image gallery. It adheres to the KISS principle and is very easy to install. MinigalNano does not have a web admin interface: You just upload your images in the photo folder on your server (using FTP, SFTP) ([Demo](http://boards.tomcanac.com/)) `CC BY-SA 3.0` `PHP`
  * [phog](https://github.com/hillman/phog) - Static photo gallery generator with S3 uploader. `Python`
  * [Photofloat](http://blog.zx2c4.com/567) - A Web 2.0 Photo Gallery Done Right via Static JSON & Dynamic Javascript. ([Demo](http://photos.jasondonenfeld.com/)) `Javascript` `GPLv2`
  * [PhotoLight](https://github.com/thibaud-rohmer/PhotoLight) - The easiest photo gallery there is. `PHP` `GPLv3`
  * [Photoshow](http://www.photoshow-gallery.com/) - ([Source Code](https://github.com/thibaud-rohmer/PhotoShow)) `Javascript` `GPLv3`
  * [Piwigo](http://piwigo.org/) - Photo gallery software for the web, built by an active community of users and developers. - `GPLv2` `PHP`
  * [Plumi](http://blog.plumi.org/) - Create your own sophisticated video-sharing site. ([Source Code](https://github.com/plumi/plumi.app)) `GPLv2` `Python`
  * [Pygmyfoto](https://github.com/dmpop/pygmyfoto) - A crude solution for publishing a photo roll on the web. `PHP`
  * [Shot.io](http://shot.io/) - Mobile optimised photo publishing platform (self-hosted Flickr alternative) ([Source Code](https://github.com/AliasIO/Shot.io)) `GPLv3` `PHP`
  * [sigal](https://github.com/saimn/sigal) - Yet another simple static gallery generator. `MIT` `Python`
  * [UberGallery](http://www.ubergallery.net) - UberGallery is an easy to use, simple to manage, web photo gallery. UberGallery does not require a database and supports JPEG, GIF and PNG file types. Simply upload your images and UberGallery will automatically generate thumbnails and output HTML. ([Source Code](https://github.com/UberGallery/UberGallery)) `MIT` `PHP`
  * [Videobin](http://videobin.org/code) - A simple video upload and sharing service with transcoding. ([Demo](http://videobin.org/), [Source Code](https://r-w-x.org/videobin.git)) `GPLv3` `Python`
  * [Zenphoto](http://www.zenphoto.org/) - Open-source gallery and CMS project. ([Source Code](https://github.com/zenphoto/zenphoto))  `GPLv2` `PHP`


## Polls and Events

  * [dudle](http://primelife.ercim.eu/results/opensource/63-dudle) - An online scheduling application. ([demo](https://dudle.inf.tu-dresden.de/)) `AGPLv3` `Ruby`
  * [Framadate](https://framadate.org/) - An online service for planning an appointment or make a decision quickly and easily: Make a poll, Define dates or subjects to choose, Send the poll link to your friends or colleagues, Discuss and make a decision. ([Demo](https://framadate.org/aqg259dth55iuhwm), [Source Code](https://git.framasoft.org/framasoft/framadate)) `CeCILL-B` `PHP`
  * [Kyélà](http://kyela.net/) - Participation polls for group events - ([Source Code](https://github.com/abienvenu/Kyela), [Demo](http://kyela.net/55232734237c8/))
  * [LimeSurvey](https://www.limesurvey.org) - Feature-rich Open Source web based polling software. Supports extensive survey logic. - ([Demo](https://demo.limesurvey.org))
  * [MaterialPoll](https://github.com/nearbycoder/materialpoll) - An opensource strawpoll.me clone for creating random polls. - ([Source Code](https://github.com/nearbycoder/materialpoll), [Demo](http://materialpoll.tk))
  * [Nuages](https://nuages.domainepublic.net/) - Collaborative meeting poll system, similar to doodle or rdvz. ([Source Code](http://git.domainepublic.net/?p=nuages.git;a=tree)) `GPLv3` `Python/Django`


## Proxy

  * [scotty](http://www.scotty-transporter.org/) - Scotty is a free opensource proxy software for bypassing filter and censorship systems. - ([Source Code](https://github.com/SSilence/scotty)) `GPLv3` `Java`
  * [Oranjeproxy](http://lehollandaisvolant.net/tout/oranjeproxy/) - Anonymizing web proxy. ([Source Code](https://github.com/AmauryCarrade/OranjeProxy)) `GPLv2` `PHP`
  * [Privoxy](http://www.privoxy.org) - A non-caching web proxy with advanced filtering capabilities for enhancing privacy, modifying web page data and HTTP headers, controlling access, and removing ads and other obnoxious Internet junk. `GPLv2` `C`
  * [Squid](http://www.squid-cache.org/) - Caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages. ([Source Code](http://bazaar.launchpad.net/~squid/squid/3-trunk/files)) `GPLv2` `C`
  * [Swiperproxy](https://swiperproxy.github.io/) - A lightning-fast, open source web proxy that is easy for you to run and customize. ([Source Code](https://github.com/swiperproxy/swiperproxy), [Demo](http://proxy.donttrustrobots.nl/)) `MIT`
  * [Tinyproxy](https://banu.com/tinyproxy/) - Light-weight HTTP/HTTPS proxy daemon. ([Source Code](https://git.banu.com/tinyproxy/)) `GPLv2` `C`
  * [Pound](http://www.apsis.ch/pound/) - Light-weight reverse proxy and load balancer for HTTP/HTTPS. ([Source Code](http://www.apsis.ch/pound/)) `GPLv2` `C`

## Read it Later Lists

  * [Nunux Keeper](http://keeper.nunux.org/) - Your personal content curation service. ([Source Code](https://github.com/ncarlier/nunux-keeper)) `GPLv3` `Nodejs`
  * [Readityourself](https://github.com/memiks/readityourself) - Read the web without ads, comments, or tweets. ([Demo](http://www.readityourself.net/)) `MIT` `PHP`
  * [Wallabag](https://www.wallabag.org/?lang=fr_fr) - Wallabag, formerly Poche, is a web application allowing you to save articles to read them later with improved readability. ([Demo](http://demo.wallabag.org/), [Public instance](http://www.framabag.org/), [Source Code](https://github.com/wallabag/wallabag) `MIT` `PHP`


## Search Engines

  * [Searx](https://github.com/asciimoo/searx) - A privacy-respecting, hackable metasearch engine. ([Demo](https://searx.me/), [Public instances](https://github.com/asciimoo/searx/wiki/Searx-instances))
  * [Seeks](https://beniz.github.io/seeks/) - A websearch proxy and collaborative distributed tool for websearch. `AGPLv3` `C++`
  * [Yacy](http://yacy.net/en/index.html) - Peer based, decentralized search engine server. `GPL2` `Java`


## Software Development

### Project Management

See also [Ticketing](#ticketing), [Task management/To-do lists](#task-managementto-do-lists)*

  * [Apache Bloodhound](https://bloodhound.apache.org/) - Manage software products, Keep track of features, tasks and bugs. `Apache` `Python`
  * [CaseBox](https://www.casebox.org) - Manage all your organisation's information in one system.
  * [Fossil](https://www.fossil-scm.org/index.html/doc/trunk/www/index.wiki) - Distributed version control system featuring wiki and bug tracker - `BSD` `C`
  * [gitbucket](http://takezoe.github.io/gitbucket/) - The easily installable GitHub clone powered by Scala - ([Source Code](https://github.com/gitbucket/gitbucket))
  * [GitLab](http://gitlab.org/) - Self Hosted Git Management Application - GitLab is open source software to collaborate on code. Manage git repositories with fine grained access controls that keep your code secure. Perform code reviews and enhance collaboration with merge requests. Each project can also have an issue tracker and a wiki. ([Public instance](https://git.framasoft.org/))
  * [Gitlist](http://gitlist.org/) - A web-based git repository browser - GitList allows you to browse repositories using your favorite browser, viewing files under different revisions, commit history and diffs. ([Source Code](https://github.com/klaussilveira/gitlist))
  * [Gitprep](http://gitprep.yukikimoto.com/) - Portable Github clone. ([Source Code](https://github.com/yuki-kimoto/gitprep), [Demo](http://perlcodesample.sakura.ne.jp/gitprep/gitprep.cgi))
  * [Gogs](https://github.com/gogits/gogs) - A painless self-hosted Git Service written in Go. ([Demo](https://try.gogs.io/))
  * [Kallithea](https://kallithea-scm.org/) - Source code management system that supports two leading version control systems, Mercurial and Git, with a web interface. ([Source Code](https://kallithea-scm.org/repos/kallithea)) `GPLv3` `Python`
  * [Klaus](https://github.com/jonashaag/klaus/) - A simple, easy-to-set-up Git web viewer that Just Works. ([Demo](http://klausdemo.lophus.org/)) `ISC` `Python`
  * [OpenProject](https://www.openproject.org) - Project collaboration.
  * [Phabricator](http://phabricator.org/) - Collection of web applications that help build better software. ([Source Code](https://github.com/phacility/phabricator), [Demo](https://secure.phabricator.com/)) `Apache` `PHP`
  * [Redmine](http://www.redmine.org/) - Redmine is a flexible project management web application. `Ruby` `GPLv2`
  * [Taiga](https://taiga.io/) - Agile Project Management Tool based on the Kanban and Scrum methods.  ([Source Code](https://github.com/taigaio))
  * [The Bug Genie](http://www.thebuggenie.com/) - Written in PHP.
  * [Trac](http://trac.edgewall.org/) - Written in python.
  * [Phproject](http://www.phproject.org/) - A high performance full-featured project management system. ([Source Code](https://github.com/Alanaktion/phproject), [Demo](http://demo.phproject.org/)) `GPLv3`


### Bug Trackers

See **[Ticketing](#ticketing)**


### IDE/Tools

  * [Codiad](http://codiad.com/) - A web-based IDE framework with a small footprint and minimal requirements. ([Source Code](https://github.com/Codiad/Codiad))
  * [JS Bin](http://jsbin.com/) - Open source collaborative web development debugging tool. ([Source Code](https://github.com/jsbin/jsbin)) `MIT` `Nodejs`
  * [Microglark](http://micro.glark.io) - A hacky minimalistic remote pair programming editor. ([Demo](http://micro.glark.io), [Source Code](https://github.com/Bluefinch/microglark)) `AGPLv3` `Javascript`
  * [Regexr](http://regexr.com/) - RegExr is a HTML/JS based tool for creating, testing, and learning about Regular Expressions. ([Source Code](https://github.com/gskinner/regexr/)) `MIT` `Nodejs`
  * [RStudio Server](https://www.rstudio.com/products/rstudio/#Server) - Web browser based IDE for R. ([Source Code](https://github.com/rstudio/rstudio/)) `AGPLv3` `Java/C++`


### Continuous Integration

  * [Factor.io](https://factor.io/) - It's like IFTTT (if-this-then-that) for Dev and DevOps. ([Source Code](https://github.com/factor-io/factor)) `MIT` `Ruby`
  * [Jenkins](https://jenkins-ci.org/) - Continuous Integration Server. ([Source Code](https://github.com/jenkinsci/jenkins/)) `MIT` `Java`
  * [PHPCI](https://www.phptesting.org/) - Free and open source continuous integration specifically designed for PHP. ([Source Code](https://github.com/block8/phpci)) `BSD` `PHP`
  * [Strider](http://stridercd.com/) - Open Source Continuous Deployment / Continuous Integration platform. ([Source Code](https://github.com/Strider-CD/strider)) `BSD` `Node.js`


### Documentation Generators

  * [daux.io](https://github.com/justinwalsh/daux.io) - Daux.io is an documentation generator that uses a simple folder structure and Markdown files to create custom documentation on the fly. It helps you create great looking documentation in a developer friendly way. `MIT`
  * [Docstore](http://haldean.org/) - A basic site for hosting static documents - docstore is a simple way to serve Markdown files without any server-side processing, and without requiring you (as the author) to recompile every time you change an article. It consists of a very simple JS script that makes an ajax request to your server, runs a Markdown processor on what it finds, and then displays the results. Clone the repository and add articles in the text/ directory to get started. ([Source Code](https://github.com/haldean/docstore))
  * [Flatdoc](http://ricostacruz.com/flatdoc/) - A small JavaScript file that fetches Markdown files and renders them as full pages. `MIT` `Javascript`
  * [markdown-tree](https://github.com/mil/markdown-tree) - Serve a hierarchy / tree directory of markdown files. Use intended for small sites built in markdown
  * [MdWiki](https://dynalon.github.io/mdwiki/#!index.md) - A Markdown CMS/Wiki completely built in HTML5/Javascript and runs 100% on the client. ([Source Code](https://github.com/Dynalon/mdwiki))
  * [Read the Docs](https://docs.readthedocs.org/en/latest/install.html) - Host documentation, making it fully searchable and easy to find; import your docs using any major version control system, including Mercurial, Git, Subversion, and Bazaar. ([Demo](https://readthedocs.org/projects/), [Source Code](https://github.com/rtfd/readthedocs.org)) `MIT` `Python`


## Static site generators

See https://staticsitegenerators.net and https://www.staticgen.com


## Task management/To-do lists

*See also [Project Management](#project-management) and [Ticketing](#ticketing).*

  * [bulldog](https://github.com/infews/bulldog) - HTML5 task manager, built on todo.txt. `MIT` `HTML5`
  * [Crepido](https://github.com/arshad/crepido) - Create (kanban) boards to track users and projects from flat markdown files. `MIT` `Javascript/Others`
  * [Restyaboard](http://restya.com/board/) - Open source Trello-like kanban board. ([Demo](http://restya.com/board/demo.html), [Source Code](https://github.com/RestyaPlatform/board)) `OSL v3.0` `PHP`
  * [Kanboard](http://kanboard.net/) - A simple and open source visual task board. `AGPLv3`
  * [myTinyTodo](http://www.mytinytodo.net/) - Simple way to manage your todo list in AJAX style. Uses PHP, jQuery, SQLite/MySQL. GTD compliant. `GPL`
  * [TaskBoard](http://taskboard.matthewross.me/) - A Kanban-inspired app for keeping track of things that need to get done. ([Source Code](https://github.com/kiswa/TaskBoard)) `MIT`
  * [Taskfreak](http://www.taskfreak.com/original) - A simple but efficient web based task manager written in PHP. ([Demo](http://demo.taskfreak.com/))
  * [tasks.php](https://github.com/RaymiiOrg/tasks.php) - A simple task/todo list manager. `MIT`
  * [Taskwarrior](https://taskwarrior.org/) - Taskwarrior is Free and Open Source Software that manages your TODO list from your command line. It is flexible, fast, efficient, and unobtrusive. It does its job then gets out of your way. ([Source Code](https://taskwarrior.org/download/#git)) `MIT` `C++`
  * [Tinyissue](https://github.com/satrun77/tinyissue) - Simple Issue Tracking for Teams. `MIT` `PHP`
  * [Tracks](http://www.getontracks.org/) - A web-based application to help you implement David Allen’s [Getting Things Done™](https://en.wikipedia.org/wiki/Getting_Things_Done) methodology. - `GPLV2`
  * [Wekan](https://wekan.io/) - An open-source Trello-like kanban. ([Demo](https://oasis.sandstorm.io/appdemo/m86q05rdvj14yvn78ghaxynqz7u2svw6rnttptxx49g1785cdv1h), [Source Code](https://github.com/wekan/wekan)) `MIT` `JavaScript/Meteor`



## Ticketing

*See also [Task management/To-do lists](#task-managementto-do-lists) and [Project Management](#project-management)*

  * [osTicket](http://osticket.com/) - Simple support ticket system.
  * [OTRS](http://www.otrs.com/) - Trouble ticket system for assigning tickets to incoming queries and tracking further communications.
  * [Request Tracker](https://www.bestpractical.com/rt/) - Ticket-tracking system written in Perl.
  * [Bugzilla](https://www.bugzilla.org/) - General-purpose bugtracker and testing tool originally developed and used by the Mozilla project. `MPLv2` `Pearl`
  * [Bumpy Booby](http://bumpy-booby.derivoile.fr/) - A simple, responsive and highly customizable PHP bug tracking system. ([Source Code](https://github.com/piero-la-lune/Bumpy-Booby)) `MIT` `PHP`
  * [Cerb](http://www.cerberusweb.com/) - Group-based e-mail management project.
  * [Flyspray](http://www.flyspray.org/) - Uncomplicated, web-based bug tracking system. ([Source Code](https://github.com/Flyspray/flyspray)) `GPLv2`
  * [Gaskit](https://github.com/bkeepers/gaskit) - A git-backed issue tracker. It uses a branch in your local git database to store the tickets. `GPL`
  * [HuBoard](https://github.com/huboard/huboard) `⚠ ` – Instant project management for your GitHub issues (Connects directly GitHub API) `MIT` `Ruby`
  * [MantisBT](https://www.mantisbt.org/) - Self hosted bug tracker, fits best for software development - ([Demo](https://www.mantisbt.org/bugs/my_view_page.php)) - ([Source Code](https://github.com/mantisbt/mantisbt)) `GPLv2`
  * [TheBugGenie](http://www.thebuggenie.com) - Ticket system with extensive user rights system.

## URL Shorteners

  * [Lstu](https://github.com/ldidry/lstu) - _Let's SHorten That Url_ - Lightweight URL shortener
  * [Nimbus](https://github.com/ethanal/nimbus) - A URL shortener and file sharer with a drag-and-drop OS X menu bar client and web interface - `MIT` `Python`
  * [Polr](https://project.polr.me/) - A modern, minimalist, modular, and lightweight URL shortener. ([Source Code](https://github.com/Cydrobolt/polr))
  * [YOURLS](http://yourls.org/) - YOURLS is a set of PHP scripts that will allow you to run Your Own URL Shortener. Features include password protection, URL customization, bookmarklets, statistics, API, plugins, jsonp. ([Source Code](https://github.com/YOURLS/YOURLS/), [Documentation](https://github.com/YOURLS/YOURLS/wiki)) `MIT`

## VPN

See https://github.com/n1trux/awesome-sysadmin#vpn


## Web servers

See https://github.com/n1trux/awesome-sysadmin#web


## Wikis

See also [Documentation Generators](#documentation-generators), [Wikimatrix](http://www.wikimatrix.org/), [Wiki Engines on WikiIndex](http://wikiindex.org/Category:Wiki_Engine), [List of wiki software on wikipedia](https://en.wikipedia.org/wiki/List_of_wiki_software), [Comparison of wiki software on wikipedia](https://en.wikipedia.org/wiki/Comparison_of_wiki_software).

  * [Blazekiss](https://github.com/ldleman/blazekiss) - BlazeKiss is a KISS-based wiki (Keep It Simple, Stupid) - simplicity and functionality comes before all. `PHP`
  * [BookStack](https://www.bookstackapp.com/) - BookStack is a simple, self-hosted, easy-to-use platform for organizing and storing information. It allows for documentation to be stored in a book like fashion. ([Demo](https://www.bookstackapp.com/#demo), [Source Code](https://github.com/ssddanbrown/BookStack)) `MIT` `PHP`
  * [Codex](https://github.com/codex-project/codex) - Codex is a simple file-based Markdown documentation platform built on top of Laravel. - `MIT` `PHP`
  * [commonplace](https://github.com/fredoliveira/commonplace) - A server for your markdown files. Give it a directory, and Commonplace gives you a url, pretty pages, and quick editing. `Ruby`
  * [Dokuwiki](http://www.splitbrain.org/projects/dokuwiki) - An easy to use, lightweight, standards-compliant wiki engine with a simple syntax allowing reading the data outside the wiki. All data is stored in plain files, therefore no database is required. - `GPL` `PHP`
  * [Gitit](https://github.com/jgm/gitit) - A wiki program that stores pages and uploaded files in a git repository, which can then be modified using the VCS command line tools or the wiki's web interface. Supported markups include pandoc's extended version of markdown, reStructuredText, LaTeX, and HTML. Pages can be exported in a number of different formats, including LaTeX, RTF, OpenOffice ODT, and MediaWiki markup. Other features include: plugins, syntax highlighting, caching, ATOM feeds. `Haskell`
  * [Gollum](https://github.com/gollum/gollum) - A simple, Git-powered wiki with a sweet API and local frontend.
  * [Gruik](http://gruik.io/) - An open-source markdown note-taking web app. ([Source Code](https://github.com/grena/gruik)) `PHP`
  * [ikiwiki](http://ikiwiki.info/) - A wiki compiler.
  * [jingo](https://github.com/claudioc/jingo) - A git based wiki engine written for node.js, with a decent design, a search capability and a good typography. ([Source Code](https://github.com/claudioc/jingo), [Demo](http://jingo.cica.li:6067/wiki/home)) `MIT`  `NodeJS`
  * [Mediawiki](https://www.mediawiki.org/wiki/MediaWiki) `PHP`
  * [MoinMoin](https://moinmo.in/) - An advanced, easy to use and extensible WikiEngine with a large community of users.
  * [Olelo/Gitwiki](https://github.com/minad/olelo) - Olelo is a wiki that stores pages in a Git repository, supports many markup styles and has an extensible, hackable architecture! Features: Edit, move or delete pages; Page attribute editor; Support for hierarchical wikis (directory structure); File upload; History, commit and diff view; Locales (Czech, English, French, German); Support for many markup languages (Creole, Markdown, Textile); RSS/Atom changelog for whole wiki or pages; Section editing for Creole; Embedded LaTeX formulas; Syntax highlighting; Image resizing, SVG to PNG/JPEG conversion; Auto-generated table of contents; Previews; View pages as S5 presentation; Privacy features: Access control lists, Private wiki, Read-only wiki. ([Demo](http://gitwiki.org/)) `Ruby`
  * [PmWiki](http://www.pmwiki.org) - Wiki-based system for collaborative creation and maintenance of websites.
  * [Raneto](http://raneto.com/) - Raneto is an open source Knowledgebase platform that uses static Markdown files to power your Knowledgebase - `MIT` `NodeJS`
  * [Realms](https://github.com/scragg0x/realms-wiki) - A git-backed wiki inspired by Gollum. `Python`
  * [Redaxscript](http://redaxscript.com/) - Ultra lightweight website engine. `GPL` `PHP`
  * [TiddlyWiki](http://tiddlywiki.com/) - A reusable non-linear personal web notebook. ([Source Code](https://github.com/Jermolene/TiddlyWiki5)) `BSD` `Javascript/Nodejs`
  * [WiKiss](http://wikiss.tuxfamily.org/) - A Wiki, simple to use and install. `PHP`
  * [Wikitten](https://github.com/victorstanciu/Wikitten) - Wikitten is a small, fast, PHP wiki, and the perfect place to store your notes, code snippets, ideas, and so on. `PHP`


------------------------------------

## Self-hosting Solutions

  * [arkOS](https://arkos.io/) - Install arkOS to a dedicated device and host your own websites, email, files and more. ([Source Code](https://git.coderouge.co/groups/arkOS) [[1]](https://github.com/cznweb)) `MIT/GPL` `Nodejs/Other`
  * [FreedomBone](https://github.com/bashrc/freedombone) - Home server configuration based on Debian. `GPLv3` `Shell`
  * [FreedomBox](https://wiki.debian.org/FreedomBox) - A community project to develop, design and promote personal servers running free software for private, personal, communications. `GPLv3` `Python/Other`
  * [Piratebox](https://piratebox.cc/start) - A DIY anonymous offline file-sharing and communications system built with free software and inexpensive off-the-shelf hardware. ([Source Code](https://github.com/PirateBox-Dev)). `GPLv3` `Python/Other`
  * [Sandstorm](https://sandstorm.io/) - Personal server for running self-hosted apps easily and securely. ([Demo](https://demo.sandstorm.io/), [Source Code](https://github.com/sandstorm-io/sandstorm)) `Apache` `C++/Other`
  * [sovereign](https://github.com/sovereign/sovereign) - A set of Ansible playbooks to build and maintain your own private cloud: email, calendar, contacts, file sync, IRC bouncer, VPN, and more. `GPLv3` `YAML/Other`
  * [UBOS](http://ubos.net/) - Linux distro that runs on indie boxes (personal servers and IoT devices). Single-command installation and management of apps - Jenkins, Mediawiki, Owncloud, Wordpress, etc., - and other [features](http://ubos.net/about/).`GPLv3` `Perl/Other` 
  * [yunohost](https://yunohost.org/) - A server operating system aiming to make self-hosting accessible to everyone. ([Source Code](https://github.com/YunoHost)) `AGPL` `Python/Other`

<!-- END SOFTWARE LIST -->

-------------------------------------------------------

## List of Licenses

 * ` ⚠ ` - Depends on a third party network service
 * `AAL` - [Attribution Assurance License](https://opensource.org/licenses/AAL)
 * `AGPLv3` - [GNU Affero General Public License 3.0](https://www.gnu.org/licenses/agpl-3.0)
 * `Apache` - [Apache, Version 2.0](http://www.apache.org/licenses/)
 * `ARTv2` - [Artistic License Version 2.0](http://opensource.org/licenses/Artistic-2.0)
 * `BSD` - [FreeBSD License](https://www.freebsd.org/copyright/license.html)
 * `CC0` - [Public Domain](https://creativecommons.org/about/cc0/)
 * `CeCILL-B` - [CEA CNRS INRIA Logiciel Libre](http://www.cecill.info/licences/Licence_CeCILL-B_V1-en.txt)
 * `CPALv1` - [Common Public Attribution License Version 1.0](http://opensource.org/licenses/CPAL-1.0)
 * `ECLv2` - [Educational Community License, Version 2.0 ](http://opensource.org/licenses/ECL-2.0)
 * `GPL` - [GNU General Public License](https://www.gnu.org/licenses/gpl-1.0)
 * `GPLv2` - [GNU General Public License 2.0](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)
 * `GPLv3` - [GNU General Public License 3.0](http://www.gnu.org/licenses/gpl-3.0.en.html)
 * `IPL` - [IBM Public License](https://opensource.org/licenses/IPL-1.0)
 * `ISC` - [Internet Software Consortium License](https://www.isc.org/downloads/software-support-policy/isc-license/)
 * `LGPLv2.1` - [Lesser General Public License 2.1](http://opensource.org/licenses/LGPL-2.1)
 * `LGPLv3` - [Lesser General Public License 3.0](http://opensource.org/licenses/LGPL-3.0)
 * `MIT` - [MIT License](http://opensource.org/licenses/MIT)
 * `MPLv2` - [Mozilla Public License](https://www.mozilla.org/MPL/2.0/index.txt)
 * `Zope` - [Zope Public License 2.0](http://opensource.org/licenses/ZPL-2.0)


-------------------------------------------------------

## External links

 * [Awesome Big Data](https://github.com/onurakpolat/awesome-bigdata) - A curated list of awesome big data frameworks, resources and other awesomeness.
 * [Awesome Sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of amazingly awesome open source sysadmin resources.
 * [PRISM Break](https://prism-break.org/en/), [privacytools.io](https://www.privacytools.io/), [Alternative Internet](https://redecentralize.github.io/alternative-internet/) - Lists of software aimed at privacy and decentralization (in some form).
 * Dynamic Domain Name services: [Afraid.org](https://freedns.afraid.org/domain/registry/), [Pagekite](https://pagekite.net/)
 * Communities/forums: [/r/selfhosted](https://www.reddit.com/r/selfhosted), [Auto-Hébergement (FR)](http://www.auto-hebergement.fr/)

-------------------------------------------------------

## Contributing

 * To **add an entry**: clone/[download](https://github.com/Kickball/awesome-selfhosted/archive/master.zip) and enter the repository, run `make add` and follow the instructions; or [edit the README.md file](https://github.com/Kickball/awesome-selfhosted/edit/master/README.md) directly. See [Editing files in another user's repository](https://help.github.com/articles/editing-files-in-another-user-s-repository/), [Creating Pull Requests](https://help.github.com/articles/creating-a-pull-request/), [Using Pull Requests](https://help.github.com/articles/using-pull-requests/) for help on sending your patch.
 * The **syntax** for links is ``[Name](http://homepage/) - Short description. ([Demo](http://url.to/demo), [Source Code](http://url.of/source/code)) `License` `Language` ``. All projects should have their **license** and main server-side **language**/platform/requirement listed, and a description at most 250 characters long.
 * Non-[Free](https://en.wikipedia.org/wiki/Free_software) software must be marked `⊘ Proprietary` next to the title, and added to [non-free.md](non-free.md)
 * Software with no development activity for 6-12 months may be removed from the list.
 * Check current [issues](https://github.com/Kickball/awesome-selfhosted/issues) and [Pull Requests](https://github.com/Kickball/awesome-selfhosted/pulls), as well as [closed issues/PRs](https://github.com/Kickball/awesome-selfhosted/pulls?utf8=%E2%9C%93&q=is%3Aclosed+)
 * The list of contributors can be updated with `make contrib`. Several checks are available: `make noexternallink; make missinglicenselanguage; make nofullstop`


## License

This list is under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) License.


The list of contributors can be found below

    219	nodiscc <nodiscc@gmail.com>
    188	Edward D <ed.kickball@hotmail.com>
    26	Andrew <AndyR207@users.noreply.github.com>
    22	Kickball <ed.kickball@hotmail.com>
    14	Kovah <mail@kovah.de>
    13	jungle-boogie <sean@jungleboogie.me>
    9	Joubert RedRat <eu+github@redrat.com.br>
    7	Andrew Peng <pengc99@gmail.com>
    7	Thomas Dalichow <info@thomasdalichow.de>
    7	n1trux <n1trux@users.noreply.github.com>
    7	phre4k <me@phre4k.at>
    7	édouard u. <mail@edouard.us>
    6	Per Guth <mail@perguth.de>
    6	Thomas Dalichow <2012-02-05.github.com@thomasdalichow.de>
    5	Jean Champémont <jchampemont@users.noreply.github.com>
    5	Moti Korets <moti.kor@gmail.com>
    5	cave beat <cave@cavebeat.org>
    4	Andrew <andrew@rylatt.me>
    4	Cory Gibbons <hello@corygibbons.com>
    4	Dominik Pfaffenbauer <dominik@lineofcode.at>
    4	Dr. Azrael Tod <github.com@g33ky.de>
    4	Ilya Sevostyanov <d3th@zeen.ru>
    4	Jean Elchinger <jinformatique@riseup.net>
    4	Joshua Westerheide <dev@jdoubleu.de>
    4	Marius Voila <marius.voila@gmail.com>
    4	dattaz <taz@dattaz.fr>
    3	Akhyar Amarullah <akhyrul@gmail.com>
    3	Conor O'Callaghan <brioscaibriste@users.noreply.github.com>
    3	Ethan Lowman <ethanal@users.noreply.github.com>
    3	FoxMaSk <foxmask@users.noreply.github.com>
    3	George C. Privon <privong@users.noreply.github.com>
    3	Görkem Çetin <gc@count.ly>
    3	Jan Vlnas <jnv@users.noreply.github.com>
    3	Lee Watson <rev@revthefox.co.uk>
    3	Leo Gaggl <leo@brightcookie.com.au>
    3	Marc Picaud <picaud.marc@gmail.com>
    3	Mariusz Kozakowski <11mariom+wordpress@gmail.com>
    3	Martin Gontovnikas <martin@gon.to>
    3	Pavan Yara <yarapavan@gmail.com>
    3	Tobi Schäfer <interface@p3k.org>
    3	Ye Lin Aung <me@yelinaung.com>
    3	cave <cavebeat@users.noreply.github.com>
    3	jungle-boogie <sean@rastasean.net>
    3	rett gerst <rettgerst@users.noreply.github.com>
    2	Albert Cervera i Areny <albert@nan-tic.com>
    2	Alexander Ryzhov <gtihub@ryzhov-al.ru>
    2	Alexis Metaireau <alexis@notmyidea.org>
    2	Andrew Hayworth <hayworth@meraki.net>
    2	Bartłomiej Kurzeja <B3QL@users.noreply.github.com>
    2	Brendan Abolivier <contact@brendanabolivier.com>
    2	Charles Farence III <charles@charlessite90.com>
    2	Chris Missal <chris.missal@gmail.com>
    2	Costin Moise <necenzurat@gmail.com>
    2	David Leonard <david@appliedtrust.com>
    2	David Wayne Baxter <dbxt@users.noreply.github.com>
    2	Deryck <dhenson02@users.noreply.github.com>
    2	Greg V <greg@unrelenting.technology>
    2	Henry Ruhs <info@redaxmedia.com>
    2	Jason Robinson <mail@jasonrobinson.me>
    2	Joseph Dykstra <josephdykstra@gmail.com>
    2	Julien Bisconti <veggiemonk@users.noreply.github.com>
    2	Kevin Vandenborne <kevin.vandenborne@gmail.com>
    2	Marien Fressinaud <dev@marienfressinaud.fr>
    2	Massimo Santini <massimo.santini@gmail.com>
    2	Matthieu Aubry <matt@piwik.org>
    2	Mikael Peigney <Mika56@users.noreply.github.com>
    2	Nicolas Carlier <n.carlier@nunux.org>
    2	Patrik Ragnarsson <patrik@starkast.net>
    2	Peter Thaleikis <spekulatius@users.noreply.github.com>
    2	Poorchop <Poorchop@users.noreply.github.com>
    2	ReadmeCritic <frankensteinbot@gmail.com>
    2	Ricardo Torres <ricardo@rictorres.com.br>
    2	Roland Geider <roland@geider.net>
    2	Simon Vieille <simon@deblan.fr>
    2	Stefano <sabas88@gmail.com>
    2	Thomas Citharel <tcit@tcit.fr>
    2	cron410 <cron410@gmail.com>
    2	jimykk <JimyKK@users.noreply.github.com>
    2	tomc3 <wordoftheday003@gmail.com>
    2	yuche <i@yuche.me>
    1	Alys <alice.harris@oldgods.net>
    1	Andrew Murray <radarhere@gmail.com>
    1	Angel Velasquez <angvp@archlinux.org>
    1	Bob Mottram <bob@robotics.uk.to>
    1	Brett <brettex@hotmail.com>
    1	Burung Hantu <privacytoolsIO@users.noreply.github.com>
    1	Caleb Xu <calebcenter@live.com>
    1	Calle Wolff <carl@wolff.se>
    1	Chanchal Kumar Ghosh <chanchal_ghosh1987@yahoo.co.in>
    1	Chema <neo22s@gmail.com>
    1	Craig Davison <craig@davison.io>
    1	Dan <rocks.in.the.cloud@gmail.com>
    1	Dirk Krause <dirkk0@googlemail.com>
    1	Dmitriy Volkov <wldhx+vcs+github_com@wldhx.me>
    1	Doğan Çelik <dogancelik@users.noreply.github.com>
    1	Dražen Lučanin <kermit666@gmail.com>
    1	Eren Hatırnaz <erenhatirnaz@hotmail.com.tr>
    1	Florian Wilhelm <f.wilhelm@tarent.de>
    1	Igor Antun <IgorAntun@users.noreply.github.com>
    1	Jan <jayphizzle@users.noreply.github.com>
    1	Jean Menezes da Rocha <jean@menezesdarocha.info>
    1	Jeremiah Marks <jeremiah@jlmarks.org>
    1	Joel Calado <joelcalado@gmail.com>
    1	Josh Harmon <me@joshharmon.me>
    1	Joshua Hamilton <joshua.hamilton@fabricut.com>
    1	José Castro <cogurov@gmail.com>
    1	Julien Bisconti <julien.bisconti@gmail.com>
    1	Justin O'Reilly <justin@oreilly.me>
    1	Keith Thibodeaux <kthib89+github@gmail.com>
    1	Keith Thibodeaux <kthibodeaux@peachtreebilling.com>
    1	Keyhaku <jones@bious.fr>
    1	Kyle Stetz <kylestetz@gmail.com>
    1	Liran Tal <liran.tal@gmail.com>
    1	Marcin Karpezo <m.karpezo@nencki.gov.pl>
    1	Marcus Ramberg <marcus@nordaaker.com>
    1	MatFluor <MatFluor@users.noreply.github.com>
    1	Matt Hazinski <matt@matthazinski.com>
    1	Michael Burns <michael@mirwin.net>
    1	Mike Steele <mike@steel.fm>
    1	Morris Jobke <hey@morrisjobke.de>
    1	Murdoc Bates <trockenasche@gmail.com>
    1	Norman Xu <im@norm.im>
    1	Oliver Kopp <kopp.dev@gmail.com>
    1	Pavel Lobashov <ShockwaveNN@gmail.com>
    1	Pavel Lobashov <shockwavenn@gmail.com>
    1	Phill <phill@formbet.co.uk>
    1	Remy Adriaanse <remy@adriaanse.it>
    1	Remy Honig <remyhonig@users.noreply.github.com>
    1	Riddler <Iamjithin@live.com>
    1	Roberto Rosario <roberto.rosario.gonzalez@gmail.com>
    1	Ryan Halliday <ry167@ry167.com>
    1	Stefan Bohacek <stefan.bohacek@gmail.com>
    1	Stefan Bohacek <stefan@fourtonfish.com>
    1	Tobias Zeising <tobias.zeising@aditu.de>
    1	benmaynard11 <allowin-217941-github@vhost244.maynardnetworks.com>
    1	bricej13 <bricej13@gmail.com>
    1	cbdev <cb@cbcdn.com>
    1	dimqua <dimqua@lavabit.com>
    1	florianl <florianl@users.noreply.github.com>
    1	lachlan-00 <lachlan.00@gmail.com>
    1	littleguga <littleguga@users.noreply.github.com>
    1	memorex258 <phillip.a.brown@live.com>
    1	mertinop <martin.santibanez.a@gmail.com>
    1	sc0repi0 <sc0repi0@gmx.de>
    1	skarphet <skarphet@users.noreply.github.com>
    1	steven jacobs <stjacobs@fastmail.fm>
    1	stevesbrain <stevesbrain@users.noreply.github.com>
    1	ttoups <ich@timotoups.de>
    1	wxcafé <wxcafe@wxcafe.net>

