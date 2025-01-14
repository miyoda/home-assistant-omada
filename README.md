# Home Assistant Omada Add-On
This add-on brings the Omada Controller directly into Home Assistant running on an 64 bit ARM or a x64 processor.

There exist two Add-On-Versions:
- Omada Stable
- Omada Beta

Omada Stable is created from Omada Beta (both in this repository), as soon as the beta add-on is updated to the latest
stable upstream version. Omada Beta should also be fairly stable, because the Add-On is mostly consistent with the already tested [docker-omada-cotroller](https://github.com/mbentley/docker-omada-controller), but might contain some Home-Assistant related inconsistencies or bugs.

# Contribution 
This add-on is a fork of Matt Bentleys [docker-omada-cotroller](https://github.com/mbentley/docker-omada-controller) and jkunczik [home-assistant-omada](https://github.com/jkunczik/home-assistant-omada) would not have been possible without thier excellent work. Other than in the original docker omada controller, this add-on stores all persistent data in the /data directory, so that it is compatible with Home assistant. This Add-On would not be possible without the effort of other people. Pull requests for version
updates or new features are always more than welcome. Special thanks goes to DraTrav for pushing this Add-On forward!

<a href="https://github.com/jkunczik/home-assistant-omada/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jkunczik/home-assistant-omada" />
</a>

Made with [contrib.rocks](https://contrib.rocks).
