# Home Assistant Omada Add-On
This add-on brings the Omada Controller directly into Home Assistant running on a Raspberry Pi.

The stable is based on jkunczik's build
While beta is updated to the latest version


# Contribution 
This add-on is a fork of Matt Bentleys [docker-omada-cotroller](https://github.com/mbentley/docker-omada-controller) and jkunczik [home-assistant-omada](https://github.com/jkunczik/home-assistant-omada) would not have been possible without thier excellent work. Other than in the original docker omada controller, this add-on stores all persistent data in the /data directory, so that it is compatible with Home assistant. My fork updates it to the latest 5.5.6 build and fixes persistant storage related to that