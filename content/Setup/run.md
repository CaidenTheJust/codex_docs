---
title: "Run"
titleIcon: "fa-solid fa-terminal"
categories: ["Setup"]
date: 2023-07-03T14:12:32-06:00
draft: false
weight: 5
---

# Prerequisites

ServX relies on the .Net 6.0 Runtime. If this is not installed, upon run you will be prompted with a link to install.

# Run

Open a new Command Prompt or Powershell and navigate to your *rundir*, from there run the command:

    ..\servx\ServX.exe

---

### Specific Instance by Id

If there is more than one Instance defined in [Config.xml](/config) a specific instance can be started by passing the Id:

    ..\servx\ServX.exe MyCluster.Stones