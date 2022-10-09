# iobroker-k8s

This repo describe basic topics for getting [iobroker](https://www.iobroker.net/) application (and tools around) into [kubernetes](https://kubernetes.io) (k8s).
Keep in mind, iobroker is not developed running within k8s and may need many many many future releases for a smooth operation within k8s.

scenarios:
- single (everything)
- master/slave (only iobroker)
- master/slave (iobroker and redis)

All examples are based on the following:
- nginx-ingress
- nfs persistent storage

tools:
- influxdb
- redis
- grafana

Feel free reaching out to me on twitter: [@otih__](https://twitter.com/otih__)
