# orcaviz
Gallery of data visualizations using Orcasound data. There is a growing suite of raw data and data products which could be visualized, including (as of April, 2022):

1. Raw audio data (HLS for all nodes; FLAC experimentally, intermittently)
2. Human detections (labels from the [Orcasound web app](live.orcasound.net)
3. Machine detections (candidates and expert annotation within the [OrcaHello real-time inference system](https://ai4orcas.net/portfolio/orcahello/))
4. Bioacoustic bouts (see [Google sheet of Orcasound annotation candidates](https://docs.google.com/spreadsheets/d/1Js1CgbmK0Vbe3m0DfiFim1BE4lXMzC75S7GN-7QEE7Y/edit#gid=0) some of which have been labled to various degrees as described in the [orcadata wiki](https://github.com/orcasound/orcadata/wiki))
5. Subscriber list (Google form survey responses via notification banner at top of v2 [live.orcasound.net](live.orcasound.net))
6. User feedback (e.g. Google form survey responses via Feedback button at bottom of v2 [live.orcasound.net](live.orcasound.net))
7. Analytics (for the orcasound.net 2017 Wordpress site, the web aap at live.orcasound.net, social media channels, email lists, and open source community tools like Slack and Github)
8. Other user research data (user interviews, usability tests, A/B tests...)


## Programmatic access to data sources

* [OrcaHello REST API](https://aifororcasdetections.azurewebsites.net/index.html) (machine detection candidates, raw and moderated; Azure-hosted CosmosDB)
* [Acartia data cooperative API](https://github.com/Typehuman/SSEMMI) for human and machine detections (acoustic and visual) that have been validated by domain experts across the range of the Southern Resident Killer Whales (SRKWs) and the Salish Sea:
* Orcasound general detection API (on the drawing board)
