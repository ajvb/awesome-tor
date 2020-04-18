# Awesome Tor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome software, articles, and other resources related to the Tor project.

[Tor](https://torproject.org/) is an anonymizing TCP overlay network proxy implemented as a cryptographic mixnet. It is used for protecting the privacy of user communications in a variety of operational environments. Contributions to this list are heartily encouraged. Please see the [contribution guidelines](CONTRIBUTING.md) for details.

# Contents

- [Android-based tools](#android-based-tools)
- [Apple iOS-based tools](#apple-ios-based-tools)
- [Articles](#articles)
- [Bridge tools](#bridge-tools)
- [Conference presentations and talks](#conference-presentations-and-talks)
- [Development and research tools](#development-and-research-tools)
- [End-user tools](#end-user-tools)
- [File sharing](#file-sharing)
- [Funding](#funding)
- [Messaging](#messaging)
- [Offensive tools](#offensive-tools)
- [Onion service tools](#onion-service-tools)
- [Operating System distributions](#operating-system-distributions)
- [Pluggable transports](#pluggable-transports)
- [Relay operator tools](#relay-operator-tools)
- [Tor controller interfaces](#tor-controller-interfaces)
- [Tor protocol implementations](#tor-protocol-implementations)
- [Tor server hardening tools](#tor-server-hardening-tools)
- [Tunneling tools](#tunneling-tools)
- [Web browser-based tools](#web-browser-based-tools)
- [Whistleblowing](#whistleblowing)

# Android-based tools

- [Orbot](https://guardianproject.info/apps/orbot/) - Provides Tor on the Android platform.
- [Orfox](https://guardianproject.info/apps/orfox/) - Provides Tor Browser on the Android platform.

# Apple iOS-based tools

- [Tor.framework](https://github.com/iCepa/Tor.framework) - The easiest way to embed Tor in your iOS application.
- [iCepa](https://github.com/iCepa/iCepa) - Apple iOS system-wide VPN based Tor client.

# Articles

- [Anonbib](https://www.torproject.org/getinvolved/volunteer.html.en#project-anonbib) - List of important papers in the field of anonymity. It's also a set of scripts to generate the website from Latex (bibtex). If we're missing any important papers, please let us know!
- [Connecting to an authenticated Onion service](https://github.com/AnarchoTechNYC/meta/wiki/Connecting-to-an-authenticated-Onion-service) - Guided procedure written for laypeople describing how to configure a Tor client to connect to authenticated Onion services.
- [Scaling Tor hidden services](https://www.benthamsgaze.org/2015/11/17/scaling-tor-hidden-services) - Article on scaling Onion services.

# Bridge tools

- [BridgeDB](https://www.torproject.org/getinvolved/volunteer.html.en#project-bridgedb) - Backend bridge distributor, handling the various pools they're distributed in. This was actively developed until Fall of 2010.

# Conference presentations and talks

- [How Tor Users Got Caught - Defcon 22](https://www.youtube.com/watch?v=7G1LjQSYM5Q) - 4 examples of people who have used Tor for illegal activities and how they were caught. Multiple de-anonymization attacks are shown at the end of the video.
- [How governments have tried to block Tor - 2011](https://www.youtube.com/watch?v=GwMr8Xl7JMQ) - Iran blocked Tor handshakes using Deep Packet Inspection (DPI) in January 2011 and September 2011, an oldy but goody.
- [State Of The Onion - 2014](https://www.youtube.com/watch?v=fOwYgAS4TXE) - Covers technical, social, economic, political and cultural issues pertaining to anonymity, the Tor Project and the ecosystem surrounding our communities.
- [The Tor Network - 2013](https://www.youtube.com/watch?v=CJNxbpbHA-I) - Roger Dingledine and Jacob Appelbaum discuss contemporary Tor Network issues related to censorship, security, privacy and anonymity online.
- [Tor: Hidden Services and Deanonymisation - 2014](https://www.youtube.com/watch?v=oZdeRmlj8Gw) - This talk presents the results from what we believe to be one of the largest studies into Tor Hidden Services (The Darknet) to date.

# Development and research tools

- [Chutney](https://www.torproject.org/getinvolved/volunteer.html.en#project-chutney) - Integration test suite that spawns a local tor network, checking the interactions of its components.
- [Compass](https://www.torproject.org/getinvolved/volunteer.html.en#project-compass) - Web and command line application that filters and aggregates the Tor relays based on various attributes.
- [DocTor](https://www.torproject.org/getinvolved/volunteer.html.en#project-doctor) - Notification service that monitors newly published descriptor information for issues. This is primarily a service to help the tor directory authority operators, but it also checks for a handful of other issues like sybil attacks.
- [ExitMap](https://www.torproject.org/getinvolved/volunteer.html.en#project-exitmap) - Scanner for the Tor network by Philipp Winter to detect malicious and misconfigured exits.
- [Fingerprint Central](https://fpcentral.tbb.torproject.org/) - Website aimed at studying the diversity of browser fingerprints and providing developers with data to help them design good defenses.
- [Metrics](https://www.torproject.org/getinvolved/volunteer.html.en#project-metrics) - Processing and analytics of consensus data, provided to users via the metrics portal. This has been under active development for several years by Karsten Loesing.
- [OnionScan](https://onionscan.org/) - Help operators of Onion services find and fix operational security issues with their location-hidden services.
- [Onionoo](https://www.torproject.org/getinvolved/volunteer.html.en#project-onionoo) - JSON based protocol to learn information about currently running Tor relays and bridges.
- [Relay Search ("Atlas")](https://metrics.torproject.org/rs.html) - Web application to discover Tor relays and bridges, providing useful information on how relays are configured along with graphics about their past usage, formerly "Atlas." ([Source code](https://gitweb.torproject.org/atlas.git))
- [Shadow](https://www.torproject.org/getinvolved/volunteer.html.en#project-shadow) - Discrete-event network simulator that runs the real Tor software as a plug-in. Shadow is open-source software that enables accurate, efficient, controlled, and repeatable Tor experimentation.
- [Tor Bulk Exitlist (TorBEL)](https://www.torproject.org/getinvolved/volunteer.html.en#project-torbel) - Provides a method of identifying if IPs belong to exit nodes or not. This is a replacement for TorDNSEL which is a stable (though unmaintained) Haskell application for this purpose. The initial version of TorBEL was started in GSOC 2010 but since then the project has been inactive.
- [TorFlow](https://www.torproject.org/getinvolved/volunteer.html.en#project-torflow) - Library and collection of services for actively monitoring the Tor network. These include the Bandwidth Scanners (measuring throughput of relays) and SoaT (scans for malicious or misconfigured exit nodes).
- [Tor Path Simulator (TorPS)](https://www.torproject.org/getinvolved/volunteer.html.en#project-torps) - Tool for efficiently simulating path selection in Tor. It chooses circuits and assigns user streams to those circuits in the same way that Tor does. TorPS is fast enough to perform thousands of simulations over periods of months.
- [TorBot](https://github.com/DedSecInside/TorBot) - Python web crawler for Dark and Deep Web. Actively maintained and can be used in Docker container (dockerfile provided).

# End-user tools

- [GetTor](https://www.torproject.org/getinvolved/volunteer.html.en#project-gettor) - E-mail autoresponder providing Tor's packages over SMTP. This has been relatively unchanged for quite a while.
- [multitor](https://github.com/trimstray/multitor) - Shell scripts to automate creation of multiple Tor instances, load-balanced with HAProxy.
- [Ooni Probe](https://www.torproject.org/getinvolved/volunteer.html.en#project-ooni) - Censorship scanner, checking your local connection for blocked or modified content.
- [Tor2web](https://www.torproject.org/getinvolved/volunteer.html.en#project-tor2web) - Allows Internet users to browse websites running in Tor hidden services. It trades user anonymity for usability by allowing anonymous content to be distributed to non-anonymous users.
- [TorBirdy](https://www.torproject.org/getinvolved/volunteer.html.en#project-torbirdy) - Torbutton for Thunderbird and related Mozilla mail clients.
- [TorCheck](https://www.torproject.org/getinvolved/volunteer.html.en#project-torcheck) - Site for determining if the visitor is using Tor or not.

# File sharing

- [OnionShare](https://onionshare.org/) - Open source tool that lets you securely and anonymously share a file of any size.
- [ZeroNet](https://zeronet.io/) - Decentralized Web site and Web application platform based on the BitTorrent protocol with Bitcoin-like blockchain that has built-in support for anonymization through Tor.

# Funding

- [OnionTip](https://github.com/DonnchaC/oniontip) - Web app which parses Tor relay data to allow users to tip volunteers in cryptocurrency for running relay(s) in a fair and open way.

# Messaging

- [Briar](https://briarproject.org/) - Peer-to-peer encrypted messaging and forums over various transports, including Bluetooth, clearnet Wi-Fi, or the Tor network.
- [Ricochet](https://ricochet.im/) - Jabber-based client that creates an Onion service used to rendezvous with your contacts without revealing your location or IP address.
- [TorChat-Mac](https://github.com/javerous/TorChat-Mac) - Mac OS X native TorChat client.
- [TorChat](https://github.com/prof7bit/TorChat) - Decentralized anonymous instant messenger on top of Tor Hidden Services.

# Offensive tools

- [ToRat](https://github.com/lu4p/ToRat) - Cross-platform remote administration tool written in Go using Tor as a transport mechanism.
- [dos-over-tor](https://github.com/skizap/dos-over-tor) - Proof of concept denial of service over Tor stress test tool.
- [oregano](https://github.com/nametoolong/oregano) - Python module that runs as a machine-in-the-middle (MITM) accepting Tor client requests.

# Onion service tools

- [Enterprise Onion Toolkit](https://github.com/alecmuffett/eotk) - Tool for assisting in large-scale deployments of HTTP(S) Onion sites as an official Onionspace presence for existing clearnet websites.
- [OnionBalance](https://github.com/DonnchaC/onionbalance) - Load-balancing and redundancy for Tor hidden services.
- [Stormy](https://github.com/glamrock/stormy) - Easy creation of Tor Onion services ("Location-Hidden Services"), currently under heavy development.
- [Vanguards](https://github.com/mikeperry-tor/vanguards) - Version 3 Onion service guard discovery attack mitigation script (intended for eventual inclusion in Tor core).

# Operating System distributions

- [The Amnesic Incognito Live System (TAILS)](https://www.torproject.org/getinvolved/volunteer.html.en#project-tails) - Live CD/USB distribution preconfigured so that everything is safely routed through Tor and leaves no trace on the local system.
- [Whonix](https://whonix.org/) - Desktop operating system that can be run in various configurations, which routes the entire user's desktop environment and OS through Tor.
- [tor-ramdisk](https://www.torproject.org/getinvolved/volunteer.html.en#project-torramdisk) - uClibc-based micro Linux distribution whose sole purpose is to securely host a Tor server purely in RAM.

# Pluggable transports

- [Flash Proxy](https://www.torproject.org/getinvolved/volunteer.html.en#project-flash-proxy) - Pluggable transport using proxies running in Web browsers to defeat address-based blocking.
- [Obfsproxy](https://www.torproject.org/getinvolved/volunteer.html.en#project-obfsproxy) - Obfuscating proxy that shapes Tor traffic, making it harder for censors to detect and block Tor, with implementations in C and Python.

# Relay operator tools

- [Anonymizing Relay Monitor (Arm)](https://www.torproject.org/getinvolved/volunteer.html.en#project-arm) - `top`-like terminal status monitor for Tor, intended for command-line aficionados, SSH connections, and anyone with a TTY terminal.
- [Weather](https://www.torproject.org/getinvolved/volunteer.html.en#project-weather) - Provides automatic notification to subscribed relay operators when their relay's unreachable.
- [ansible-relayor](https://github.com/nusenu/ansible-relayor) - An Ansible role for Tor Relay Operators.
- [tor-relay-bootstrap](https://github.com/micahflee/tor-relay-bootstrap) - Script to bootstrap a Debian server to be a set-and-forget Tor relay.
- [tor_box](https://github.com/CMoncur/tor_box) - An all-inclusive Tor configuration for Raspberry Pi, serves as both a relay and personal Tor network.

# Tor controller interfaces

- [Bine](https://github.com/cretz/bine) - Go library for accessing and embedding Tor clients and servers.
- [PHP TorControl](https://github.com/dunglas/php-torcontrol) - PHP library to control a Tor server.
- [Stem](https://www.torproject.org/getinvolved/volunteer.html.en#project-stem) - TorProject's official Python controller library for scripts and controller applications using Tor.
- [tor.rb](https://github.com/dryruby/tor.rb) - Ruby library for interacting with the Tor anonymity network.
- [txtorcon](https://txtorcon.readthedocs.io/) - TorProject's official implementation of the control-spec for Tor using the Twisted networking library for Python (supports Py2, PyPy and Py3).

# Tor server hardening tools

- [Tlsdate](https://www.torproject.org/getinvolved/volunteer.html.en#project-tlsdate) - Secure parasitic rdate replacement maintained by the Tor Project that sets the local clock by securely connecting with TLS to remote servers and extracting the remote time out of the secure handshake.
- [onion-grater](https://github.com/Whonix/onion-grater) - Whitelisting filter for dangerous Tor control protocol commands.

# Tunneling tools

- [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy) - DNS proxy server supporting arbitrary DNS, DNSCrypt v2, DNS-over-TLS, and DNS-over-HTTPS queries that can be torified with a two-line configuration change (`force_tcp = true` and `proxy = socks5://127.0.0.1:9050` or similar).
- [tor_ssh.sh](https://gitlab.com/grownetics/devops/blob/master/tor_ssh.sh) - One command to enable SSH access via Tor to any server. 
- [Torsocks](https://www.torproject.org/getinvolved/volunteer.html.en#project-torsocks) - Utility for adapting other applications to work with Tor.
- [Tortilla](https://www.crowdstrike.com/resources/community-tools/tortilla-tool/) - Open source tool that allows users of Windows OS devices to securely, anonymously, and transparently route all TCP/IP and DNS traffic through Tor.
- [tun2tor](https://github.com/iCepa/tun2tor) - Rust library to provide a virtual `utun` (userspace tunnel) interface to Tor.

# Web browser-based tools

- [HTTPS Everywhere](https://www.eff.org/https-everywhere) - Firefox and Chrome extension that automatically switches to HTTPS connections with many major websites if those are available that ships in Tor Browser.
- [NoScript](https://noscript.net/) - Javascript execution blocking Firefox extension that ships in Tor Browser.
- [Tor Browser](https://www.torproject.org/getinvolved/volunteer.html.en#project-torbrowser) - Easy-to-use, portable package of Tor, HTTPS-Everywhere, NoScript, TorLauncher, Torbutton, and a Firefox fork, all preconfigured to work together out of the box.

# Tor protocol implementations

- [haskell-tor](https://github.com/GaloisInc/haskell-tor) - Haskell implementation of the Tor protocol.
- [node-Tor](https://github.com/Ayms/node-Tor) - Javascript implementation of the Tor (or Tor like) anonymizer project.

# Whistleblowing

- [GlobaLeaks](https://www.globaleaks.org/) - Free software intended to enable secure and anonymous whistleblowing initiatives.
- [SecureDrop](https://github.com/freedomofpress/securedrop) - Open-source whistleblower submission system that media organizations can use to securely accept documents from and communicate with anonymous sources.

# License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
