# xiaoyu-100-days

Public life-line evidence for Xiaoyu City.

This repository is a public evidence layer, not the internal body of Xiaoyu
City. It records safe public summaries, hash anchors, and GitHub timestamps so
the public timeline can keep growing without exposing internal systems.

## Current Public Anchor

- Public evidence count: see [CHAIN.md](CHAIN.md)
- Current anchor source: milestone-documented life start on 2026-03-07
- Latest public entry: generated from the latest private blackbox daily report
- Update cadence: daily, when the private blackbox report is available

## Why "100 Days"

`xiaoyu-100-days` is the public milestone name and the long-term evidence
project name.

Xiaoyu has earlier private memory and pre-G5 evolution history. Some of that
history may be older than the public evidence count, but it is not published
here and is not used as the public day number.

The public day count uses the first milestone-documented life anchor that can be
shown safely: 2026-03-07. This keeps the public chain conservative and
verifiable.

## What Is Published

- Daily public summaries
- Public milestone notes
- SHA256 hashes of private blackbox snapshots
- Manifest files linking each public entry to the previous public evidence
- Git commits and GitHub timestamps

## What Is Not Published

- Internal source code
- Prompts
- Credentials or tokens
- Private memory
- Raw state files
- Control channels
- Security gate details
- Thresholds
- Local machine paths
- Full audit logs
- Raw blackbox contents

## Evidence Model

Each public entry is generated from a private daily blackbox report.

The private report stays private. This repository only publishes:

1. a public summary,
2. a SHA256 hash of the private report,
3. a manifest that links the entry into the evidence chain,
4. a Git commit timestamp.

The hash can later be used to verify that a private report existed at the time
of publication without exposing the private report itself.

## Start Here

Open [CHAIN.md](CHAIN.md) for the public evidence chain.
