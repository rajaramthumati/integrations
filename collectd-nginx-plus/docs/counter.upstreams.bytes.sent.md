---
title: Upstream Peer Bytes Sent
brief: Total number of bytes sent to an upstream server
metric_type: cumulative_counter
---
### Upstream Bytes Sent
The total number of bytes sent to a single upstream server. This metric is reported
with dimensions `stream.upstream.name` and `stream.upstream.peer.name` to indicate the name of the upstream group
and name of the individual server, respectively.
