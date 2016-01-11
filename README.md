# Awesome JavaScript Network [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Kikobeats/awesome-network-js) [![Build Status](https://img.shields.io/travis/Kikobeats/awesome-network-js/master.svg?style=flat-square)](https://travis-ci.org/Kikobeats/awesome-network-js)

> A 🎩 list of resources related with network area written in JavaScript.

## High level

> Based, at least, in a CLI interface.

* [webtorrent](https://github.com/feross/webtorrent) – BitTorrent over WebRTC.
* [instant.io](https://github.com/feross/instant.io) – Streaming file transfer over WebTorrent.
* [screencat](https://github.com/maxogden/screencat) – WebRTC screensharing app.
* [peervisionary](https://github.com/mafintosh/peervisionary) – Stream p2p content over your local network.
* [peerflix](https://github.com/mafintosh/peerflix) – Streaming torrent client.
* [peercast](https://github.com/mafintosh/peercast) – Like peerflix but for Chromecast.
* [airpaste](https://github.com/mafintosh/airpaste) – 1-1 network pipe that auto discovers other peers using mdns.
* [blecat](https://github.com/mafintosh/blecat) – 1-1 pipe over bluetooth low energy.
* [websocketd](https://github.com/joewalnes/websocketd) – Turn any program that uses stdin/stdout into a WebSocket server.
* [deejay](https://github.com/mafintosh/deejay) – Music player that broadcasts to everyone on the same network.
* [webcat](https://github.com/mafintosh/webcat) – pipe across the web using WebRTC.
* [peerwiki](https://github.com/mafintosh/peerwiki) – browse all of wikipedia using bittorrent.
* [torrent-mount](https://github.com/mafintosh/torrent-mount) – Mount a torrent (or magnet link) as a filesystem in real time using torrent-stream and fuse.
* [signalhub](https://github.com/mafintosh/signalhub) – Simple signalling server that can be used to coordinate handshaking with webrtc or other fun stuff.
* [dhtkv](https://github.com/maxogden/dhtkv) – CLI for storing arbitrary key/value data in the bittorrent mainline DHT.
* [ipp-printer](https://github.com/watson/ipp-printer) – Create a printer on your network.
* [wifi-triangulate](https://github.com/watson/wifi-triangulate) – Finds your current position on planet earth using the wifi access point.

## Protocols

> Implementation of protocols specs in pure javascript.

* [peervision](https://github.com/mafintosh/peervision) – Live p2p streaming protocol.
* [airswarm](https://github.com/mafintosh/airswarm) – Network swarm that automagically discovers other peers on the network using multicast dns.
* [polo](https://github.com/mafintosh/polo) – A zero configuration service discovery module.
* [dns-discovery](https://github.com/mafintosh/dns-discovery) – Discovery peers in a distributed system using regular dns and multicast dns.
* [multicast-dns](https://github.com/mafintosh/multicast-dns) – Low level multicast-dns implementation.
* [mdns](https://github.com/agnat/node_mdns) – mdns/zeroconf/bonjour service discovery.
* [ipfs](https://github.com/ipfs/js-ipfs-api) – The InterPlanetary File System, a new peer-to-peer hypermedia protocol.
* [castv2](https://github.com/thibauts/node-castv2) – An implementation of the Chromecast CASTV2 protocol.
* [utp](https://github.com/mafintosh/utp) – micro transport protocol, a network protocol similar to tcp that runs on top of udp.
* [k-rpc](https://github.com/mafintosh/k-rpc) – Implementation of the k-rpc protocol used the BitTorrent DHT. Also see [k-rpc-socket](https://github.com/mafintosh/k-rpc-socket).
* [k-bucket](https://github.com/tristanls/k-bucket) – Kademlia DHT K-bucket implementation as a binary tree.
* [bittorrent-dht](https://github.com/feross/bittorrent-dht) – BitTorrent DHT protocol implementation.
* [bittorrent-protocol](https://github.com/feross/bittorrent-protocol) – BitTorrent peer wire protocol implementation.
* [bittorrent-swarm](https://github.com/feross/bittorrent-swarm) – BitTorrent "swarm" implementation.
* [bittorrent-tracker](https://github.com/feross/bittorrent-tracker) – BitTorrent tracker (client & server) implementation
* [bonjour](https://github.com/watson/bonjour) – A Bonjour/Zeroconf protocol implementation.
* [rtsp-server](https://github.com/watson/rtsp-server) – A low level module for creating RTSP servers.

## Modules

> Do one thing well.

* [airplay-server](https://github.com/watson/airplay-server) – A low level AirPlay server.
* [castnow](https://github.com/xat/chromecast-player) – simple chromecast player.
* [simple-peer](https://github.com/feross/simple-peer) – Simple WebRTC video/voice and data channels.
* [simple-websocket](https://github.com/feross/simple-websocket) – Simple, EventEmitter API for WebSockets.
* [network-address](https://github.com/mafintosh/network-address) – Get the local network address of your machine.
* [torrent-stream](https://github.com/mafintosh/torrent-stream) – The low level streaming torrent engine that peerflix uses.
* [torrent-discovery](https://github.com/feross/torrent-discovery) – Discover BitTorrent and WebTorrent peers.
* [ip-packet](https://github.com/mafintosh/ip-packet) – Encode/decode raw ip packets.
* [udp-packet](https://github.com/substack/udp-packet) – Encode/decode raw udp packets.
* [network-simulator](https://github.com/substack/network-simulator) – Simulate a low-level computer network.
* [rtsp-stream](https://github.com/watson/rtsp-stream) - A transport agnostic RTSP serial multiplexer module for Node.
* [hash-to-port](https://github.com/mafintosh/hash-to-port) – Hash a value to a valid port.
* [magnet-uri](https://github.com/feross/magnet-uri) – Parse a magnet URI and return an object of keys/values.
* [geocode-wifi](https://github.com/watson/geocode-wifi) – Get yours latitude/longitude based on your wifi access point.
* [open-ssh-tunnel](https://github.com/parro-it/open-ssh-tunnel) – Easy ssh2 tunneling.
