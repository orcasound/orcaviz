# orcaviz
A gallery of open data visualizations using Orcasound data. Browse the topical galleries for other precedents and innovative ideas. There you can find links to catalytic code and other resources that may be helpful.

**Can you create something better than these pioneering best visualizations yet of Orcasound's ecosystem and user data?**

Value 1 | Value 2 &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
Top ecosystem viz | Top user data viz
:----------------:|:----------------:
<img alt="Screen Shot 2022-10-30 at 8 07 10 PM" src="https://user-images.githubusercontent.com/14044595/199586546-f3bc9a1a-9539-4ed8-8482-d395cd2f44d6.png"> | <img alt="Screen Shot 2022-11-02 at 12 38 08 PM" src="https://user-images.githubusercontent.com/14044595/199587686-cc1fab07-8037-4885-9e0e-5748cf32f7d0.png">
Last 7 days of animal locations in the [Acartia.io](https://acartia.io) data cooperative. <br> By [Peter Ince](https://github.com/peterdouglas).  | Last month of daily traffic within the [Orcasound web app](live.orcasound.net). <br> By [Adrian MacDonald](linkedin.com/in/adrian-macdonald). 

## Ecoystem viz caption
Most of these markers are J pod of the Southern Resident Killer Whales coming in from the Pacific to San Juan Island (upper left blue dots), entering Puget Sound (blue and purple dots), deciding to swim up towards the Skagit river on the inside of Whidbey Island (pink dots), presumably circumnavigating Whidbey and re-entering Puget Sound as far as Seattle vicinity and then exiting towards Pacific again (red dots). Mapbox UI implemented by Peter Ince et al. of  TypeHuman via the [SSEMMI open source repo on Github](https://github.com/Typehuman/SSEMMI). Screenshot by Scott Veirs.

## User data viz caption
Embedded within the [Orcasound Wordpress site's UX-Dashboard page](https://www.orcasound.net/orcasound-user-data-dashboard/) for transparency. andeasy access during weekly standups, these are Google Analytics events visualized via [Google Looker Studio](https://cloud.google.com/looker-studio).

# Open data sources

There is a [growing suite of raw data and data products which could be visualized](https://github.com/orcasound/orcadata/wiki/Data-visualization-opportunities), including (as of November, 2022):

## Ecosystem data sources

1. Raw audio data (HLS for all nodes; FLAC experimentally, intermittently)
2. Human detections (labels from community scientists listening live via the [Orcasound web app](live.orcasound.net))
3. Machine detections (un/moderated candidates within the [OrcaHello real-time inference system](https://ai4orcas.net/portfolio/orcahello/))
4. Bioacoustic bouts (see [Google sheet of Orcasound annotation candidates](https://docs.google.com/spreadsheets/d/1Js1CgbmK0Vbe3m0DfiFim1BE4lXMzC75S7GN-7QEE7Y/edit#gid=0) some of which have been labled to various degrees as described in the [orcadata wiki](https://github.com/orcasound/orcadata/wiki))
5. Marine animal location data (presence and sometimes track data, inferred from sightings, hearings, etc) via the [Acartia data cooperative](https://acartia.io)

## Orcasound user data sources
1. Subscriber list (Google form survey responses via notification banner at top of v2 [live.orcasound.net](live.orcasound.net))
2. User feedback (e.g. Google form survey responses via Feedback button at bottom of v2 [live.orcasound.net](live.orcasound.net))
3. Analytics (for the orcasound.net 2017 Wordpress site, the web app at live.orcasound.net, social media channels, email lists, and open source community tools like Slack and Github)
4. Other user research data (user interviews, usability tests, A/B tests...)


## Programmatic access to data sources

* [OrcaHello REST API](https://aifororcasdetections.azurewebsites.net/index.html) (machine detection candidates, raw and moderated; Azure-hosted CosmosDB)
* [Acartia data cooperative API](https://github.com/Typehuman/SSEMMI) for human and machine detections (acoustic and visual) that have been validated by domain experts across the range of the Southern Resident Killer Whales (SRKWs) and the Salish Sea
* Orcasound general detection API (on the drawing board)
