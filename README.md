# AutoPeer
An open source system that helps network operators automate their internet peering. Facilitating secure inter-operator intent via API. AutoPeer is authored by [Antonio Faria](https://github.com/movedempackets), governed as a [benevolent dictatorship](CODE_OF_CONDUCT.md), and distributed under [license](LICENSE). 
> [!WARNING]
> AutoPeer is in construction, during this time no effort shall be afforded to migrations and backwards compatibility.

Internet peering for over a decade has typically been negotiated through email, and larger network operators have addressed its limitations through organically developed portals. In 2023 a working group comprised of Jenny Ramseyer (Meta), Matt Griswold (FullCtl) and Erica Salvaneschi (Cloudflare) proposed Peering API, their work can be found [here](https://www.ietf.org/id/draft-ramseyer-grow-peering-api-04.html). The fundamental principle, adopted as AutoPeer's mission is by each network operator employing a standardised API, bidirectional system-to-system internet peering negotiation can be facilitated. 

> [!NOTE]
> AutoPeer and Peering API schemas do not align, although its the author's intention to broach the discussion with the working group.

AutoPeer aims to address most of the technical tribulations, a few of its features are:
+ High-performance, event-driven, microservices architecture[^1].
+ Horizontally scalable[^2].
+ Reliable, stable and consistent.
+ First-class integrations.
+ Feature-packed services.[^3]

[^1]: That's a bingo!
[^2]: Not yet available for Dispatcher service.
[^3]: AutoPeer helps network operators define their internet peering policies and rules for automated resource validation.

## Installation
Our installation guide will be published soon.

## Versioning
Releases will follow semantic versioning (major.minor.patch). 

## Contributing
Suggest a [feature]() or report a [bug](). Read our developer [guide](CONTRIBUTING.md).

## License
AutoPeer is distributed under the Apache 2.0 [license](LICENSE).
