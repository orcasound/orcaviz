# orcaviz
A gallery of open data visualizations using Orcasound data. Annual best efforts are showcased below.

You can also browse the topical directories for other precedents and innovative ideas. There you can find links to catalytic code and other resources that may be helpful.

**Can you create something better than these pioneering best visualizations yet of Orcasound's ecosystem and user data?**

If so, please join the Orcasound Slack and Github organization, and then document your best efforts in the [ecosystem data visualization sandbox](ecosystem-viz.md) or the [user data visualization sandbox](user-viz.md). These are reviewed by the community each fall to select a top contribution for display here. This friendly competition started in 2021.

Top ecosystem viz (2023) | Top user data viz (2023)
:----------------:|:----------------:
<img alt="Screenshot of the orca-salmon dashboard showing a map on the left of fish enumeration locations on the Columbia and Fraser rivers and a time-series plot of the adult Chinook salmon counts on the right" src="https://github.com/orcasound/orcaviz/assets/14044595/fc5a84e8-9c55-421c-b238-22fbc795bdb2"> | <img alt="Screenshot of Google spreadsheet with color-coded prioritation of findings from a usability study of the Acartia data cooperative" src="https://github.com/orcasound/orcaviz/assets/14044595/25cf2344-4959-4ae4-9f9b-f2fe5bdda8a6">
Default view of the [orca-salmon dashboard](https://salmonorca.fly.dev/) shows current estimates of daily adult Chinook salmon returns to the Columbia and Fraser rivers relative to the past two years and the historical mean. The "Southern Resident Orca" tab displays real time and historic orca location data with the first-ever web-based filter for pods J, K, or L.<br> By [Zoe Liu](https://www.linkedin.com/in/liuzoe/).  | Usability data for the [Acartia.io](https://acartia.io) data cooperative prioritized for the development team and mapped into a [Team Capacity view](https://github.com/orgs/salish-sea/projects/8/views/2) within the Acartia internal Github project. <br> By [Megan Rigley](https://www.linkedin.com/in/megan-rigney/) and Jill Shutian. 

Top ecosystem viz (2022) | Top user data viz (2022)
:----------------:|:----------------:
<img alt="Screenshot of a map showing the last 7 days of observation locations within the Acartia data cooperative, color-coded by age of the observation" src="https://user-images.githubusercontent.com/14044595/199586546-f3bc9a1a-9539-4ed8-8482-d395cd2f44d6.png"> | <img alt="Screenshot of a Google Analytics dashboard 2-week time-series plot showing traffic to Orcasound live-listening web app, broken down by referral source" src="https://user-images.githubusercontent.com/14044595/199587686-cc1fab07-8037-4885-9e0e-5748cf32f7d0.png">
Last 7 days of animal locations in the [Acartia.io](https://acartia.io) data cooperative. <br> By [Peter Ince](https://github.com/peterdouglas), [Ali Alaydrus](https://www.linkedin.com/in/fadliealaydrus/), and Nick Bryne.  | Last month of daily traffic within the [Orcasound web app](live.orcasound.net). <br> By [Adrian MacDonald](linkedin.com/in/adrian-macdonald). 

## Ecosystem viz caption
Most of these markers are J pod of the Southern Resident Killer Whales coming in from the Pacific to San Juan Island (upper left blue dots), entering Puget Sound (blue and purple dots), deciding to swim up towards the Skagit river on the inside of Whidbey Island (pink dots), presumably circumnavigating Whidbey and re-entering Puget Sound as far as Seattle vicinity and then exiting towards Pacific again (red dots). Mapbox UI implemented by Peter Ince et al. of  TypeHuman via the [SSEMMI open source repo on Github](https://github.com/Typehuman/SSEMMI). Screenshot by Scott Veirs.

## User data viz caption
Embedded within the [Orcasound Wordpress site's UX-Dashboard page](https://www.orcasound.net/orcasound-user-data-dashboard/) for transparency and easy access during weekly standups, these are Google Analytics events visualized via [Google Looker Studio](https://cloud.google.com/looker-studio).

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
