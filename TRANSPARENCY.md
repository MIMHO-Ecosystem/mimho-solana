# MIMHO Transparency Statement

## Overview

MIMHO is committed to transparency across its launch phases, contract versions and ecosystem development.

This repository documents the Solana-side launch preparation.

The BSC/EVM smart contract development is maintained separately under MIMHO Labs.

## V1 BSC Presale Status

The previous BSC Presale V1 flow is deprecated.

During the 2026-04-20 presale flow, the V1 presale contract suffered a critical fund-lock incident.

The issue involved a failure where internal state was updated before all critical fund movement was safely completed.

As a result, BNB became locked in the V1 contract without a safe recovery path.

## V1 Policy

MIMHO does not hide the V1 history.

V1 is preserved as historical reference and transparency material.

V1 contracts are not recommended for production use.

## V2 Direction

MIMHO V2 is being rebuilt with stronger security practices.

The V2 process includes:

- explicit failure simulation
- transfer failure tests
- transferFrom failure tests
- reentrancy tests
- broken token tests
- malicious token tests
- invariant handler tests
- Foundry test suites
- Slither triage
- Aderyn triage
- Mythril testing
- Echidna testing
- Medusa or Halmos when necessary

## Solana Launch Separation

The Solana launch is separate from the deprecated BSC Presale V1 contracts.

The initial Solana launch uses a standard public launchpad flow and does not deploy custom Solana/Rust contracts.

## What This Means

The Solana launch is not a continuation of the failed V1 presale contract.

The Solana launch is a separate community-focused launch phase.

The BSC/EVM V2 ecosystem will only be activated through tested and documented contracts.

## Public Accountability

MIMHO will maintain public documentation for:

- official links
- token identity
- launch status
- risk disclosures
- security notes
- roadmap updates
- cross-chain development status

## No False Claims

MIMHO will not claim:

- guaranteed profit
- guaranteed migration
- guaranteed listing
- active bridge before deployment
- active staking before deployment
- custom Solana program audit when no custom program exists
- completed BSC V2 audit before security review is complete

## Current Transparency Position

MIMHO V1 is deprecated.

MIMHO V2 is under security hardening.

MIMHO Solana is preparing for a public community launch.
