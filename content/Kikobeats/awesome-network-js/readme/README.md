# Awesome Network Js Overview

A :tophat: list of network layer resources written pure JS.

[๐  Home](/README.md) ยท [๐ฅ Feed](https://test.trackawesomelist.com/Kikobeats/awesome-network-js/rss.xml) ยท [๐ฎ Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) ยท [๐บ Kikobeats/awesome-network-js](https://github.com/Kikobeats/awesome-network-js) ยท โญ 517 ยท ๐ท๏ธ Programming Languages

[ [Daily](/content/Kikobeats/awesome-network-js/README.md) / [Weekly](/content/Kikobeats/awesome-network-js/week/README.md) / Overview ]

---

# Awesome JavaScript Network [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Kikobeats/awesome-network-js) [![Build Status](https://img.shields.io/travis/Kikobeats/awesome-network-js/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/awesome-network-js) [![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/kikobeats)

> A ๐ฉ list of network layer resources written pure JS.

## High level

> Based, at least, in a CLI interface.

*   [airpaste](https://github.com/mafintosh/airpaste) โ 1-1 network pipe that auto discovers other peers using mdns.
*   [blecat](https://github.com/mafintosh/blecat) โ 1-1 pipe over bluetooth low energy.
*   [deejay](https://github.com/mafintosh/deejay) โ Music player that broadcasts to everyone on the same network.
*   [dhtkv](https://github.com/maxogden/dhtkv) โ CLI for storing arbitrary key/value data in the bittorrent mainline DHT.
*   [gun](https://github.com/amark/gun) โ A realtime, decentralized, offline-first, graph database engine.
*   [hyperpipe](https://github.com/mafintosh/hyperpipe) โ Distributed input/output pipe.
*   [hypervision](https://github.com/mafintosh/hypervision) โ P2P Television.
*   [instant.io](https://github.com/webtorrent/instant.io) โ Streaming file transfer over WebTorrent.
*   [ipp-printer](https://github.com/watson/ipp-printer) โ Create a printer on your network.
*   [peercast](https://github.com/mafintosh/peercast) โ Like peerflix but for Chromecast.
*   [peerflix](https://github.com/mafintosh/peerflix) โ Streaming torrent client.
*   [peervisionary](https://github.com/mafintosh/peervisionary) โ Stream p2p content over your local network.
*   [peerwiki](https://github.com/mafintosh/peerwiki) โ browse all of wikipedia using bittorrent.
*   [screencat](https://github.com/maxogden/screencat) โ WebRTC screensharing app.
*   [signalhub](https://github.com/mafintosh/signalhub) โ Simple signalling server that can be used to coordinate handshaking with webrtc or other fun stuff.
*   [torrent-mount](https://github.com/mafintosh/torrent-mount) โ Mount a torrent (or magnet link) as a filesystem in real time using torrent-stream and fuse.
*   [webcat](https://github.com/mafintosh/webcat) โ pipe across the web using WebRTC.
*   [websocketd](https://github.com/joewalnes/websocketd) โ Turn any program that uses stdin/stdout into a WebSocket server.
*   [webtorrent](https://github.com/webtorrent/webtorrent) โ BitTorrent over WebRTC.
*   [wifi-triangulate](https://github.com/watson/wifi-triangulate) โ Finds your current position on planet earth using the wifi access point.

## Modules

> Do one thing well.

*   [airplay-server](https://github.com/watson/airplay-server) โ A low level AirPlay server.
*   [castnow](https://github.com/xat/chromecast-player) โ simple chromecast player.
*   [discovery-swarm](https://github.com/mafintosh/discovery-swarm) โ A network swarm that uses [discovery-channel](https://github.com/maxogden/discovery-channel) to find peers. Also check [webrtc-swarm](https://github.com/mafintosh/webrtc-swarm).
*   [dns-packet](https://github.com/mafintosh/dns-packet) โ Abstract-encoding compliant module for encoding / decoding DNS packets. Also see [dns-socket](https://github.com/mafintosh/dns-socket).
*   [etcdjs](https://github.com/mafintosh/etcdjs) โ Low level etcd v2 client written in Javascript with failover support.
*   [geocode-wifi](https://github.com/watson/geocode-wifi) โ Get yours latitude/longitude based on your wifi access point.
*   [hash-to-port](https://github.com/mafintosh/hash-to-port) โ Hash a value to a valid port.
*   [hyperdb](https://github.com/mafintosh/hyperdb) โ Distributed scalable database.
*   [ip-packet](https://github.com/mafintosh/ip-packet) โ Encode/decode raw ip packets.
*   [magnet-uri](https://github.com/webtorrent/magnet-uri) โ Parse a magnet URI and return an object of keys/values.
*   [mutex-server](https://github.com/samchon/mutex-server) - Critical section controllers, like mutex and semaphore, in the network level.
*   [network-address](https://github.com/mafintosh/network-address) โ Get the local network address of your machine.
*   [network-simulator](https://github.com/substack/network-simulator) โ Simulate a low-level computer network.
*   [rtsp-stream](https://github.com/watson/rtsp-stream) - A transport agnostic RTSP serial multiplexer module for Node.
*   [simple-peer](https://github.com/feross/simple-peer) โ Simple WebRTC video/voice and data channels.
*   [simple-websocket](https://github.com/feross/simple-websocket) โ Simple, EventEmitter API for WebSockets.
*   [torrent-discovery](https://github.com/webtorrent/torrent-discovery) โ Discover BitTorrent and WebTorrent peers.
*   [torrent-stream](https://github.com/mafintosh/torrent-stream) โ The low level streaming torrent engine that peerflix uses.
*   [udp-packet](https://github.com/substack/udp-packet) โ Encode/decode raw udp packets.
*   [rpc-websockets](https://github.com/elpheria/rpc-websockets) - JSON-RPC 2.0 implementation over WebSockets for Node.js and JavaScript.

## Protocols

> Implementation of protocols specs in pure javascript.

*   [airswarm](https://github.com/mafintosh/airswarm) โ Network swarm that automagically discovers other peers on the network using multicast dns.
*   [bittorrent-dht](https://github.com/webtorrent/bittorrent-dht) โ BitTorrent DHT protocol implementation.
*   [bittorrent-protocol](https://github.com/webtorrent/bittorrent-protocol) โ BitTorrent peer wire protocol implementation.
*   [bittorrent-tracker](https://github.com/webtorrent/bittorrent-tracker) โ BitTorrent tracker (client & server) implementation
*   [bonjour](https://github.com/watson/bonjour) โ A Bonjour/Zeroconf protocol implementation.
*   [castv2](https://github.com/thibauts/node-castv2) โ An implementation of the Chromecast CASTV2 protocol.
*   [dht-rpc](https://github.com/mafintosh/dht-rpc) โ Make RPC calls over a [Kademlia](https://pdos.csail.mit.edu/\~petar/papers/maymounkov-kademlia-lncs.pdf) based DHT.
*   [dns-discovery](https://github.com/mafintosh/dns-discovery) โ Discovery peers in a distributed system using regular dns and multicast dns.
*   [hypercore](https://github.com/mafintosh/hypercore) โ A p2p network for distributing and replicating static feeds of binary data.
*   [ipfs](https://github.com/ipfs/js-ipfs-api) โ The InterPlanetary File System, a new peer-to-peer hypermedia protocol.
*   [k-bucket](https://github.com/tristanls/k-bucket) โ Kademlia DHT K-bucket implementation as a binary tree.
*   [k-rpc](https://github.com/mafintosh/k-rpc) โ Implementation of the k-rpc protocol used the BitTorrent DHT. Also see [k-rpc-socket](https://github.com/mafintosh/k-rpc-socket).
*   [mdns](https://github.com/agnat/node_mdns) โ mdns/zeroconf/bonjour service discovery.
*   [multicast-dns](https://github.com/mafintosh/multicast-dns) โ Low level multicast-dns implementation.
*   [peervision](https://github.com/mafintosh/peervision) โ Live p2p streaming protocol.
*   [polo](https://github.com/mafintosh/polo) โ A zero configuration service discovery module.
*   [rtsp-server](https://github.com/watson/rtsp-server) โ A low level module for creating RTSP servers.
*   [utp-native](https://github.com/mafintosh/utp-native) โ micro transport protocol, a network protocol similar to tcp that runs on top of udp.

