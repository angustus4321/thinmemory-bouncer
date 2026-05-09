# ThinMemory Bouncer VIP Repository

This repository distributes signed ThinMemory Bouncer VIP payload artifacts.

## Trust Model

Artifacts in this repository are signed with the ThinMemory Bouncer Ed25519 signing key. Manager binaries verify the signature using an embedded public key before trusting any artifact contents. TLS is not load-bearing for trust — the signature is. This repository may be fetched over plain HTTP without compromising security.

## Artifact Location

The current Bouncer VIP payload is always at: bouncer/current.tmvip

## For ThinMemory Users

Your ThinMemory installation fetches this list automatically. Applications registered in the Bouncer program receive priority placement in ThinMemory's managed memory pool. No user action required.

## For Developers

Developer registration for the ThinMemory Bouncer program is available at thinmemory.com. Registered applications receive guaranteed priority memory placement on all ThinMemory-equipped machines running your application.

## For Researchers

The TMVIP binary format will be documented in the ThinMemory public specification when the Bouncer sub-phase is complete.
