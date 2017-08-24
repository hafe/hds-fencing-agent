# hds-fencing-agent
Pacemaker style fencing agent for Ericsson HDS 

## Introduction

A fencing agent is a command line utility placed in /usr/sbin with a prefix of *fence_*

The API requirements are described by:
https://web-beta.archive.org/web/20160616205032/https://fedorahosted.org/cluster/wiki/FenceAgentAPI

A fencing agent ususally does power fencing using IPMI but with Redfish based platform managment a new type of agent is needed.

Source code examples can be found in:
https://github.com/ClusterLabs/fence-agents

One example:
https://github.com/ClusterLabs/fence-agents/blob/master/fence/agents/drac5/fence_drac5.py
