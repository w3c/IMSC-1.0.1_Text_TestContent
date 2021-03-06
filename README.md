# IMSC-1.0.1_Text_TestContent

**Note: While this reel is still a valid suite of tests, it is recommended that the newer [IMSC-1.1_Text_TestContent](https://github.com/w3c/IMSC-1.1_Text_TestContent) is used.**

This repository was forked from https://github.com/FoxMediaServices/IMSC-1.0.1_Text_TestContent with the intent to increase the reach of the materials provided, per https://www.w3.org/2019/02/21-tt-minutes.html#item07

This reel was created to address early IMSC decoding issues by providing manufacturers with a reference IMSC 1.0/1.0.1 text implementation. The included tests are all pertinent to subtitles produced for production content.

This test content includes the following assets:

- IMSC1-0-1_TEXT_Test-Reel_FMS_v2-1_2018-01-23.xml
- IMSC1-0-1_TEXT_Test-Reel_FMS_v2-1_2018-01-23_Backplate.mov*
- IMSC1-0-1_TEXT_Test-Reel_FMS_v2-1_2018-01-23_CompositedProxy.mov*

  **Please note that these media files are hosted at https://media.w3.org/, and are linked to via .URL internet shortcut files.*

The IMSC XML file is to be rendered over the Backplate ProRes HQ file. If the IMSC decoding is accurate, it will look approximately the same as the Composited Proxy file. It is acceptable for there to be slight differences in text rendering, since the proportionalSansSerif font chosen by the renderer may be different than what was used for the proxy.

The backplate includes the following:
- Frame counter and Media Time counter
- Grid with lines every 5%
- Yellow crosses at each corner of the region
- Red arrows which show the X and Y text flow direction
- Sync counter at the beginning and end of each event
