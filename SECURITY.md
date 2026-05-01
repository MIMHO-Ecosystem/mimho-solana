# MIMHO Solana Security Notes

## Overview

This repository documents the Solana-side launch preparation for MIMHO.

The initial Solana launch does not deploy a custom Solana/Rust program.

## Initial Solana Launch

The initial launch is planned through a standard public launchpad flow.

Because no custom Solana program is deployed for this first phase, there is no custom Rust/Anchor contract audit for the Solana launch.

## User Verification

Users should verify:

- official mint address
- official launchpad link
- official explorer link
- official website
- official social links

Final official links will be published in this repository after launch.

## No Custom Program Claim

MIMHO does not claim that the initial Solana launch uses a custom audited Solana program.

The initial launch is intentionally simple and follows the public launch platform flow.

## BSC/EVM Security

BSC/EVM contracts are maintained separately under MIMHO Labs.

The MIMHO V2 EVM security-hardening process includes:

- Foundry unit tests
- Foundry fuzz tests
- invariant handler tests
- broken token tests
- malicious token tests
- reentrancy tests
- Slither analysis
- Aderyn analysis
- Mythril analysis
- Echidna testing
- Medusa or Halmos when necessary

## Deprecated V1 Notice

The previous BSC Presale V1 flow is deprecated after a critical fund-lock incident.

V1 contracts are not recommended for production use.

MIMHO V2 is being rebuilt with stronger security requirements.

## Reporting Issues

If you find a suspicious link, fake token, fake account or security concern, report it through official MIMHO communication channels.

Do not share private keys, seed phrases or wallet passwords with anyone.

## Security Principles

MIMHO follows these principles:

- do not hide deprecated versions
- do not claim completed audits before completion
- do not promise risk-free contracts
- separate Solana launch documentation from BSC/EVM contract security
- publish official links clearly
- document known risks honestly
