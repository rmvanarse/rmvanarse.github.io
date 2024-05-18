---
title: "Bio-inspired Robot Swarms"
excerpt: "_Automation of a swarm of decentralized mobile robots that perform tasks through swarm intelligence algorithms_"
header:
  teaser: /assets/images/projects/swarmbots_dp.jpeg
gallery:
  - url: /assets/images/projects/area_cov.gif
    image_path: /assets/images/projects/area_cov.gif
    alt: "placeholder image 1"
  - url: /assets/images/projects/contam_remov.gif
    image_path: /assets/images/projects/contam_remov.gif
    alt: "placeholder image 2"
  - url: /assets/images/projects/foraging.gif
    image_path: /assets/images/projects/foraging.gif
    alt: "placeholder image 3"
---
**Swarmbots** is a project on development of algorithms for automation of a swarm of autonomous mobile robots. The robots perform various tasks through ‘collective decision making’.
Multi-robot systems become increasingly complex with an increase in the number of robots. In this project, a swarm of robots is entirely decentralized and each robot knows only the approximate relative position of its neighbours. Furthermore, the bots do not rely on inter-robot communication, localization or memory, and possess only minimal local sensing & processing capabilities. They perform tasks collectively through 'swarm intelligence' algorithms.

{% include gallery caption="**Swarmbots:** All tasks are decentralized, i.e. each robot takes its own decisions. The images show the emergent collective behaviours of **Area coverage/ exploration** _(Left)_, **Contamination removal** _(Centre)_ and **Foraging** _(Right)_"%}
The project attempts to break down complex coordinated tasks into simpler sub-tasks such as **Agregation**, **Line-formation**, **Shape-formation**, **Area-Coverage**, **Flocking**, **Following**, etc. The project was started in 2019 with RasPi-controlled differential drive robots, and was moved to simulations in 2020.

The project implemented the following tasks:
1. **Area Search:** The robots disperse and collectively explore an area.
2. **Foraging/ Resource Gathering:** The robots search for & collectively transport resources to a ‘nest’ at an unknown location. 
3. **Contamination Removal:** The robots create a perimeter around gradually growing contaminations and neutralize them

These tasks were implemented weighted combinations of basic swarm-behaviours such as aggregation, dispersion, exploration, line formation, shape formation, surrounding items and consensus.


_**Role in  Project:** Project Lead. Developed the Algorithms, Simulation_

\[[**GitHub Repo**](http://github.com/rmvanarse/swarm_tasks)\]

\[[**Talk YouTube link**](https://www.youtube.com/watch?v=HZjE_zC4Yek&ab_channel=ElectronicsandRoboticsClub%2CBITSGoa)\]

\[[Nature Scientific Reports submission]()\]
