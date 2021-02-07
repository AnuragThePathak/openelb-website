---
title: "Overview"
linkTitle: "Overview"
weight: 1
---

![porter-logo](/images/docs/overview/porter-logo.png)

Porter is an open-source load balancer implementation designed for bare-metal Kubernetes clusters.

## Why Porter

In cloud-based Kubernetes clusters, services are usually exposed by using load balancers provided by cloud vendors. However, cloud-based load balancers are unavailable in bare-metal environments. Porter allows users to create LoadBalancer services in bare-metal environments for external access, and provides the same user experience as cloud-based load balancers.

## Core Features

- BGP mode and Layer 2 mode
- ECMP routing and load balancing
- IP address pool management
- BGP configuration using CRDs
- Installation using Helm and KubeSphere

## Support, Discussion and Contributing

Porter is a sub-project of [KubeSphere](https://github.com/kubesphere/kubesphere).

* Join us at the [KubeSphere Slack Channel](https://kubesphere.slack.com/join/shared_invite/enQtNTE3MDIxNzUxNzQ0LTZkNTdkYWNiYTVkMTM5ZThhODY1MjAyZmVlYWEwZmQ3ODQ1NmM1MGVkNWEzZTRhNzk0MzM5MmY4NDc3ZWVhMjE#/) to get support or simply tell us that you are using Porter.
* You have code or documents for Porter? We ❤️ all sorts of contributions! You can [build the Porter project](/docs/building/) and send pull requests to the [GitHub Porter Repository](https://github.com/kubesphere/porter).

## Landscapes

<p align="center">
<br/><br/>
<img src="https://landscape.cncf.io/images/left-logo.svg" width="150"/>&nbsp;&nbsp;<img src="https://landscape.cncf.io/images/right-logo.svg" width="200"/>&nbsp;&nbsp;
<br/><br/>
Porter is a promising newcomer in service proxy, which enriches the <a href="https://landscape.cncf.io/landscape=observability-and-analysis&license=apache-license-2-0">CNCF CLOUD NATIVE Landscape.
</a>
</p>

## License

**Porter** is licensed under the Apache License, Version 2.0. See [LICENSE](https://github.com/kubesphere/porter/blob/master/LICENSE) for the full license text.