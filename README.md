# arweave-secure-snapshot
Secure Censorship-resistant Web Snapshot Creator  

## Aim

Provide an easy to use online tool for creating and storing web snapshots along all their TLS data (certificate, handshake and encrypted communication) on the Arweave ledger, and a interface to view the snapshots and its raw data.  

## Purpose

Nowadays, sites use TLS for keeping a secure end-to-end encryption and also demonstrating authority over the server responses. With this we can ensure the ownership and integrity of web responses, with this we can serve responses as proof on an anti-censorship platform with high availability.  
This is useful for attesting that some information existed, and also demonstrating the ownership, it can be used in journalism or as a personal proof to share with others.  

## Technical overview

The application is divided into two main parts, the [dApp](./dapp) responsible for the web Application, and the [scrapper](./scrapper) responsible for the raw site crawling, because this is not viable to do in a browser.

## Links

 - [User Stories](./STORIES.md)