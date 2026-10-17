# Awesome JavaScript Network [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Kikobeats/awesome-network-js) [![Build Status](https://img.shields.io/travis/Kikobeats/awesome-network-js/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/awesome-network-js) [![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://paypal.me/kikobeats)

> A 🎩 list of network layer resources written pure JS.

## High level

> Based, at least, in a CLI interface.

* [airpaste](https://github.com/mafintosh/airpaste) – 1-1 network pipe that auto discovers other peers using mdns.
* [blecat](https://github.com/mafintosh/blecat) – 1-1 pipe over bluetooth low energy.
* [deejay](https://github.com/mafintosh/deejay) – Music player that broadcasts to everyone on the same network.
* [dhtkv](https://github.com/maxogden/dhtkv) – CLI for storing arbitrary key/value data in the bittorrent mainline DHT.
* [gun](https://github.com/amark/gun) – A realtime, decentralized, offline-first, graph database engine.
* [hyperpipe](https://github.com/mafintosh/hyperpipe) – Distributed input/output pipe.
* [hypervision](https://github.com/mafintosh/hypervision) – P2P Television.
* [instant.io](https://github.com/webtorrent/instant.io) – Streaming file transfer over WebTorrent.
* [ipp-printer](https://github.com/watson/ipp-printer) – Create a printer on your network.
* [peercast](https://github.com/mafintosh/peercast) – Like peerflix but for Chromecast.
* [peerflix](https://github.com/mafintosh/peerflix) – Streaming torrent client.
* [peervisionary](https://github.com/mafintosh/peervisionary) – Stream p2p content over your local network.
* [peerwiki](https://github.com/mafintosh/peerwiki) – browse all of wikipedia using bittorrent.
* [screencat](https://github.com/maxogden/screencat) – WebRTC screensharing app.
* [signalhub](https://github.com/mafintosh/signalhub) – Simple signalling server that can be used to coordinate handshaking with webrtc or other fun stuff.
* [torrent-mount](https://github.com/mafintosh/torrent-mount) – Mount a torrent (or magnet link) as a filesystem in real time using torrent-stream and fuse.
* [webcat](https://github.com/mafintosh/webcat) – pipe across the web using WebRTC.
* [websocketd](https://github.com/joewalnes/websocketd) – Turn any program that uses stdin/stdout into a WebSocket server.
* [webtorrent](https://github.com/webtorrent/webtorrent) – BitTorrent over WebRTC.
* [wifi-triangulate](https://github.com/watson/wifi-triangulate) – Finds your current position on planet earth using the wifi access point.

## Modules

> Do one thing well.

* [airplay-server](https://github.com/watson/airplay-server) – A low level AirPlay server.
* [chromecast-player](https://github.com/xat/chromecast-player) – simple chromecast player.
* [discovery-swarm](https://github.com/mafintosh/discovery-swarm) – A network swarm that uses [discovery-channel](https://github.com/maxogden/discovery-channel) to find peers. Also check [webrtc-swarm](https://github.com/mafintosh/webrtc-swarm).
* [dns-packet](https://github.com/mafintosh/dns-packet) – Abstract-encoding compliant module for encoding / decoding DNS packets. Also see [dns-socket](https://github.com/mafintosh/dns-socket).
* [etcdjs](https://github.com/mafintosh/etcdjs) – Low level etcd v2 client written in Javascript with failover support.
* [geocode-wifi](https://github.com/watson/geocode-wifi) – Get yours latitude/longitude based on your wifi access point.
* [hash-to-port](https://github.com/mafintosh/hash-to-port) – Hash a value to a valid port.
* [hyperdb](https://github.com/mafintosh/hyperdb) – Distributed scalable database.
* [ip-packet](https://github.com/mafintosh/ip-packet) – Encode/decode raw ip packets.
* [magnet-uri](https://github.com/webtorrent/magnet-uri) – Parse a magnet URI and return an object of keys/values.
* [mutex-server](https://github.com/samchon/mutex-server) - Critical section controllers, like mutex and semaphore, in the network level.
* [network-address](https://github.com/mafintosh/network-address) – Get the local network address of your machine.
* [network-simulator](https://github.com/substack/network-simulator) – Simulate a low-level computer network.
* [rtsp-stream](https://github.com/watson/rtsp-stream) - A transport agnostic RTSP serial multiplexer module for Node.
* [simple-peer](https://github.com/feross/simple-peer) – Simple WebRTC video/voice and data channels.
* [simple-websocket](https://github.com/feross/simple-websocket) – Simple, EventEmitter API for WebSockets.
* [torrent-discovery](https://github.com/webtorrent/torrent-discovery) – Discover BitTorrent and WebTorrent peers.
* [torrent-stream](https://github.com/mafintosh/torrent-stream) – The low level streaming torrent engine that peerflix uses.
* [udp-packet](https://github.com/substack/udp-packet) – Encode/decode raw udp packets.
* [rpc-websockets](https://github.com/elpheria/rpc-websockets) - JSON-RPC 2.0 implementation over WebSockets for Node.js and JavaScript.

## Protocols

> Implementation of protocols specs in pure javascript.

* [airswarm](https://github.com/mafintosh/airswarm) – Network swarm that automagically discovers other peers on the network using multicast dns.
* [bittorrent-dht](https://github.com/webtorrent/bittorrent-dht) – BitTorrent DHT protocol implementation.
* [bittorrent-protocol](https://github.com/webtorrent/bittorrent-protocol) – BitTorrent peer wire protocol implementation.
* [bittorrent-tracker](https://github.com/webtorrent/bittorrent-tracker) – BitTorrent tracker (client & server) implementation
* [bonjour](https://github.com/watson/bonjour) – A Bonjour/Zeroconf protocol implementation.
* [castv2](https://github.com/thibauts/node-castv2) – An implementation of the Chromecast CASTV2 protocol.
* [dht-rpc](https://github.com/mafintosh/dht-rpc) – Make RPC calls over a [Kademlia](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf) based DHT.
* [dns-discovery](https://github.com/mafintosh/dns-discovery) – Discovery peers in a distributed system using regular dns and multicast dns.
* [hypercore](https://github.com/mafintosh/hypercore) – A p2p network for distributing and replicating static feeds of binary data.
* [ipfs](https://github.com/ipfs/js-ipfs-api) – The InterPlanetary File System, a new peer-to-peer hypermedia protocol.
* [k-bucket](https://github.com/tristanls/k-bucket) – Kademlia DHT K-bucket implementation as a binary tree.
* [k-rpc](https://github.com/mafintosh/k-rpc) – Implementation of the k-rpc protocol used the BitTorrent DHT. Also see [k-rpc-socket](https://github.com/mafintosh/k-rpc-socket).
* [mdns](https://github.com/agnat/node_mdns) – mdns/zeroconf/bonjour service discovery.
* [multicast-dns](https://github.com/mafintosh/multicast-dns) – Low level multicast-dns implementation.
* [peervision](https://github.com/mafintosh/peervision) – Live p2p streaming protocol.
* [polo](https://github.com/mafintosh/polo) – A zero configuration service discovery module.
* [rtsp-server](https://github.com/watson/rtsp-server) – A low level module for creating RTSP servers.
* [utp-native](https://github.com/mafintosh/utp-native) – micro transport protocol, a network protocol similar to tcp that runs on top of udp.
