---
title: Release Apache SkyWalking Satellite 1.1.0
date: 2023-01-06
author: SkyWalking Team
description: "Release Apache SkyWalking Satellite 1.1.0"
---

SkyWalking Satellite 1.1.0 is released. Go to [downloads](https://skywalking.apache.org/downloads) page to find release tars.

#### Features
* Support transmit the OpenTelemetry Metrics protocol.
* Upgrade to GO 1.18.
* Add Docker images for arm64 architecture.
* Support transmit Span Attached Event protocol data.
* Support dotnet CLRMetric forward.

#### Bug Fixes
* Fix the missing return data when receive metrics in batch mode.
* Fix [CVE-2022-21698](https://avd.aquasec.com/nvd/cve-2022-21698), [CVE-2022-27664](https://avd.aquasec.com/nvd/cve-2022-27664).

#### Issues and PR
- All issues are [here](https://github.com/apache/skywalking/milestone/143?closed=1)
- All and pull requests are [here](https://github.com/apache/skywalking-satellite/pulls?q=is%3Apr+milestone%3A1.1.0+is%3Aclosed)