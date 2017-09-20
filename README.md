# awesome-tor [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome Tor related projects, articles, papers, etc


### Contents
- [Awesome Tor](#awesome-tor)
    - [The Tor Project](#the-tor-project)
        - [Tor Project's Projects](#tor-projects-projects)
    - [Implementation of the Tor Protocol in Other Languages](#implementation-of-the-tor-protocol-in-other-languages)
    - [Tools](#tools)
        - [Hidden Service](#hidden-service)
            - [Running Hidden Services](#running-hidden-services)
        - [Relay](#relay)
        - [Using Tor](#using-tor)
    - [Resources](#resources)
        - [Conference Talks](#conference-talks)
        - [Articles](#articles)
        - [Websites](#websites)
    - [Donate](#donate)



# The Tor Project

#### [torproject.org](http://torproject.org/)
#### [blog.torproject.org](https://blog.torproject.org/blog/)

## Tor Project's Projects

This is a listing directly taken from The Tor Project's [Projects table](https://www.torproject.org/getinvolved/volunteer.html.en#projects) on their Volunteer page.

* [Tor](https://www.torproject.org/getinvolved/volunteer.html.en#project-tor) - Central project, providing the core software for using and participating in the Tor network. Numerous people contribute to the project to varying extents, but the chief architects are Nick Mathewson and Roger Dingledine.
* [Tor Browser](https://www.torproject.org/getinvolved/volunteer.html.en#project-torbrowser) - Tor Browser is an easy-to-use, portable package of Tor, HTTPS-Everywhere, NoScript, TorLauncher, Torbutton, and a Firefox fork, all preconfigured to work together out of the box. The modified copy of Firefox aims to resolve the privacy and security issues in mainline version.
* [HTTPS Everywhere](https://www.torproject.org/getinvolved/volunteer.html.en#project-httpseverywhere) - HTTPS Everywhere is a Firefox and Chrome extension that encrypts your communications with many major websites, making your browsing more secure.
* [Arm](https://www.torproject.org/getinvolved/volunteer.html.en#project-arm) -The anonymizing relay monitor (arm) is a terminal status monitor for Tor, intended for command-line aficionados, ssh connections, and anyone with a tty terminal. This works much like top does for system usage, providing real time statistics for bandwidth, resource usage, connections, and quite a bit more.
* [Orbot](https://www.torproject.org/getinvolved/volunteer.html.en#project-orbot) - Provides Tor on the Android platform. The project is under active development, updates to latest Tor releases, and working to stay up to date with all changes in Android and mobile threats.
* [Tails](https://www.torproject.org/getinvolved/volunteer.html.en#project-tails) - The Amnesic Incognito Live System is a live CD/USB distribution preconfigured so that everything is safely routed through Tor and leaves no trace on the local system. This is a merger of the Amnesia and Incognito projects, and still under very active development.
* [tor-ramdisk](https://www.torproject.org/getinvolved/volunteer.html.en#project-torramdisk) - Tor-ramdisk is a uClibc-based micro Linux distribution whose sole purpose is to securely host a Tor server purely in RAM.
* [Torsocks](https://www.torproject.org/getinvolved/volunteer.html.en#project-torsocks) - Utility for adapting other applications to work with Tor. Development has slowed and compatibility issues remain with some platforms, but it's otherwise feature complete.
* [TorBirdy](https://www.torproject.org/getinvolved/volunteer.html.en#project-torbirdy) - TorBirdy is Torbutton for Thunderbird and related Mozilla mail clients.
* [Obfsproxy](https://www.torproject.org/getinvolved/volunteer.html.en#project-obfsproxy) - A proxy that shapes Tor traffic, making it harder for censors to detect and block Tor. This has both a C and python implementation.
* [Flash Proxy](https://www.torproject.org/getinvolved/volunteer.html.en#project-flash-proxy) - Pluggable transport using proxies running in web browsers to defeat address-based blocking.
* [Shadow](https://www.torproject.org/getinvolved/volunteer.html.en#project-shadow) - Shadow is a discrete-event network simulator that runs the real Tor software as a plug-in. Shadow is open-source software that enables accurate, efficient, controlled, and repeatable Tor experimentation.
* [Chutney](https://www.torproject.org/getinvolved/volunteer.html.en#project-chutney) - Integration test suite that spawns a local tor network, checking the interactions of its components.
* [Stem](https://www.torproject.org/getinvolved/volunteer.html.en#project-stem) - Python controller library for scripts and controller applications using Tor.
* [Txtorcon](https://www.torproject.org/getinvolved/volunteer.html.en#project-txtorcon) - Twisted-based asynchronous Tor control protocol implementation. Includes unit-tests, examples, state-tracking code and configuration abstraction. Used by OONI and APAF.
* [Tlsdate](https://www.torproject.org/getinvolved/volunteer.html.en#project-tlsdate) - tlsdate: secure parasitic rdate replacement. tlsdate sets the local clock by securely connecting with TLS to remote servers and extracting the remote time out of the secure handshake. Unlike ntpdate, tlsdate uses TCP, for instance connecting to a remote HTTPS or TLS enabled service, and provides some protection against adversaries that try to feed you malicious time information.
* [Metrics](https://www.torproject.org/getinvolved/volunteer.html.en#project-metrics) - Processing and analytics of consensus data, provided to users via the metrics portal. This has been under active development for several years by Karsten Loesing.
* [Atlas](https://www.torproject.org/getinvolved/volunteer.html.en#project-atlas) - Atlas is a web application to discover Tor relays and bridges. It provides useful information on how relays are configured along with graphics about their past usage.
* [Globe](https://www.torproject.org/getinvolved/volunteer.html.en#project-globe) - Globe is a web application that allows you to search for Tor relays and bridges. It gives you a detailed overview of properties and configurations of a relay or bridge.
* [Compass](https://www.torproject.org/getinvolved/volunteer.html.en#project-compass) - Compass is a web and command line application that filters and aggregates the Tor relays based on various attributes.
* [Onionoo](https://www.torproject.org/getinvolved/volunteer.html.en#project-onionoo) - Onionoo is a JSON based protocol to learn information about currently running Tor relays and bridges.
* [ExitMap](https://www.torproject.org/getinvolved/volunteer.html.en#project-exitmap) - Scanner for the Tor network by Philipp Winter to detect malicious and misconfigured exits.
* [DocTor](https://www.torproject.org/getinvolved/volunteer.html.en#project-doctor) - DocTor is a notification service that monitors newly published descriptor information for issues. This is primarily a service to help the tor directory authority operators, but it also checks for a handful of other issues like sybil attacks.
* [Weather](https://www.torproject.org/getinvolved/volunteer.html.en#project-weather) - Provides automatic notification to subscribed relay operators when their relay's unreachable
* [GetTor](https://www.torproject.org/getinvolved/volunteer.html.en#project-gettor) - E-mail autoresponder providing Tor's packages over SMTP. This has been relatively unchanged for quite a while.
* [TorCheck](https://www.torproject.org/getinvolved/volunteer.html.en#project-torcheck) - Site for determining if the visitor is using Tor or not.
* [BridgeDB](https://www.torproject.org/getinvolved/volunteer.html.en#project-bridgedb) - Backend bridge distributor, handling the various pools they're distributed in. This was actively developed until Fall of 2010.
* [Ooni Probe](https://www.torproject.org/getinvolved/volunteer.html.en#project-ooni) - Censorship scanner, checking your local connection for blocked or modified content.
* [TorPS](https://www.torproject.org/getinvolved/volunteer.html.en#project-torps) - The Tor Path Simulator (TorPS) is a tool for efficiently simulating path selection in Tor. It chooses circuits and assigns user streams to those circuits in the same way that Tor does. TorPS is fast enough to perform thousands of simulations over periods of months.
* [TorFlow](https://www.torproject.org/getinvolved/volunteer.html.en#project-torflow) - Library and collection of services for actively monitoring the Tor network. These include the Bandwidth Scanners (measuring throughput of relays) and SoaT (scans for malicious or misconfigured exit nodes).
* [TorBEL](https://www.torproject.org/getinvolved/volunteer.html.en#project-torbel) - The Tor Bulk Exitlist provides a method of identifying if IPs belong to exit nodes or not. This is a replacement for TorDNSEL which is a stable (though unmaintained) Haskell application for this purpose. The initial version of TorBEL was started in GSOC 2010 but since then the project has been inactive.
* [Tor2web](https://www.torproject.org/getinvolved/volunteer.html.en#project-tor2web) - Tor2web allows Internet users to browse websites running in Tor hidden services. It trades user anonymity for usability by allowing anonymous content to be distributed to non-anonymous users.
* [Anonbib](https://www.torproject.org/getinvolved/volunteer.html.en#project-anonbib) - Anonbib is a list of important papers in the field of anonymity. It's also a set of scripts to generate the website from Latex (bibtex). If we're missing any important papers, please let us know!

# Implementation of the Tor Protocol in Other Languages

* [haskell-tor](https://github.com/GaloisInc/haskell-tor) - A Haskell implementation of the Tor protocol.
* [node-Tor](https://github.com/Ayms/node-Tor) - Javascript implementation of the Tor (or Tor like) anonymizer project (The Onion Router).

# Tools

## Hidden Service

### Running Hidden Services

* [OnionBalance](https://github.com/DonnchaC/onionbalance) - Load-balancing and redundancy for Tor hidden services
* [Stormy](https://github.com/glamrock/stormy) -  Easy creation of Tor Hidden Services (Stormy is currently under heavy development, and only usable by developers.)

## Relay
* [tor-relay-bootstrap](https://github.com/micahflee/tor-relay-bootstrap) - Script to bootstrap a debian server to be a set-and-forget Tor relay
* [ansible-relayor](https://github.com/nusenu/ansible-relayor) - An Ansible role for Tor Relay Operators
* [tor_box](https://github.com/CMoncur/tor_box) - An all-inclusive Tor configuration for Raspberry Pi, serves as both a relay and personal Tor network


## Using Tor

* [TorChat](https://github.com/prof7bit/TorChat) -  Decentralized anonymous instant messenger on top of Tor Hidden Services.
* [TorChat-Mac](https://github.com/javerous/TorChat-Mac) -  Mac OS X native TorChat client
* [SecureDrop](https://github.com/freedomofpress/securedrop) - SecureDrop is an open-source whistleblower submission system that media organizations can use to securely accept documents from and communicate with anonymous sources. It was originally created by the late Aaron Swartz and is currently managed by Freedom of the Press Foundation.
* [OnionShare](https://onionshare.org/) - OnionShare is an open source tool that lets you securely and anonymously share a file of any size.


# Resources

## Conference Talks

* [State Of The Onion - 2014](https://www.youtube.com/watch?v=fOwYgAS4TXE) - The State of the Onion covers technical, social, economic, political and cultural issues pertaining to anonymity, the Tor Project and the ecosystem surrounding our communities.
* [Tor: Hidden Services and Deanonymisation - 2014](https://www.youtube.com/watch?v=oZdeRmlj8Gw) - This talk presents the results from what we believe to be one of the largest studies into Tor Hidden Services (The Darknet) to date.
* [The Tor Network - 2013](https://www.youtube.com/watch?v=CJNxbpbHA-I) - Roger Dingledine and Jacob Appelbaum will discuss contemporary Tor Network issues related to censorship, security, privacy and anonymity online.
* [How governments have tried to block Tor - 2011](https://www.youtube.com/watch?v=GwMr8Xl7JMQ) - (*Oldy but goody*) Iran blocked Tor handshakes using Deep Packet Inspection (DPI) in January 2011 and September 2011. Bluecoat tested out a Tor handshake filter in Syria in June 2011. China has been harvesting and blocking IP addresses for both public Tor relays and private Tor bridges for years. Roger Dingledine and Jacob Appelbaum will talk about how exactly these governments are doing the blocking, both in terms of what signatures they filter in Tor (and how we've gotten around the blocking in each case), and what technologies they use to deploy the filters -- including the use of Western technology to operate the surveillance and censorship infrastructure in Tunisia (Smartfilter), Syria (Bluecoat), and other countries.
* [How Tor Users Got Caught - Defcon 22](https://www.youtube.com/watch?v=7G1LjQSYM5Q) -  4 examples of people who have used Tor for illegal activities and how they were caught. Multiple de-anonymization attacks are shown at the end of the video.

## Articles
* [Scaling Tor hidden services](https://www.benthamsgaze.org/2015/11/17/scaling-tor-hidden-services)

## Websites
* [torproject.org](http://torproject.org/)
* [blog.torproject.org](https://blog.torproject.org/blog/)

# Donate

* [Oniontip](https://oniontip.com) - Donate to volunteers who are running Tor relays using Bitcoin.
