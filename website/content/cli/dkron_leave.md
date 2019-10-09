---
date: 2019-08-26
title: "dkron leave"
slug: dkron_leave
url: /cli/dkron_leave/
---
## dkron leave

Force an agent to leave the cluster

### Synopsis

Stop stops an agent, if the agent is a server and is running for election
	stop running for election, if this server was the leader
	this will force the cluster to elect a new leader and start a new scheduler.

```
dkron leave [flags]
```

### Options

```
  -h, --help              help for leave
      --rpc-addr string   gRPC address of the agent (default "127.0.0.1:6868")
```

### Options inherited from parent commands

```
      --config string   config file path
```

### SEE ALSO

* [dkron](/cli/dkron/)	 - Open source distributed job scheduling system

###### Auto generated by spf13/cobra on 26-Aug-2019