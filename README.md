# Durak — The Last Card Standing

A stylish, self-contained browser card game. Open `index.html` in a modern browser to play.

## Features

- Play locally with 2–4 people, passing the screen between turns.
- Create a room and invite a friend online, or join their room with a room code (PeerJS/WebRTC signaling; internet access required).
- Pick from five custom card-back designs.
- Optional bluff-challenge house rule.
- Transfer attacks are available with 3+ players, following the classic transfer rule. In a two-player game there is no next defender to transfer to.

## Run

No build step or installation is required. Open `index.html` directly, or serve this folder from any static web host. Google Fonts and PeerJS load from their public CDNs; local play still works if those services are unavailable.

## Rules note

Durak is usually played without bluffing. Bluff challenge is an optional party rule: an attacker can hide a later attack card, and the defender may challenge it. This is a casual browser game and online rooms are peer-to-peer; only share room codes with people you intend to play with.
