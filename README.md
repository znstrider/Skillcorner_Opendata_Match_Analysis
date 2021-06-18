<h1>Analyis of games with open sourced Skillcorner broadcast tracking data</h1>
<br>

[@SkillCorner](https://twitter.com/SkillCorner) released nine games worth of broadcast tracking data for the top games of the 2019/2020 season in [this repository](https://github.com/SkillCorner/opendata) as part of the [Friends of Tracking](https://www.youtube.com/channel/UCUBFJYcag8j2rm_9HkrrA7w) Initiative.  

<br>

This repository aims to provide an overview into resources for analyzing the games, working with the data and showcasing applications of the broadcast tracking data.  
<br>

It would be especially nice if this could spark a collaboration of people with different strengths and backgrounds like analyzing the games and singling out key tactical ideas important in a specific game, people with the technical skills needed to implement those very ideas and people whose strength lie in the communication of those ideas via words, graphics and videos.  
<br>

If you create something based on the SkillCorner data, please let [@SkillCorner](https://twitter.com/SkillCorner) know on Twitter and if you want to have it linked to or showcased in this repository, open an issue or mention / DM me on my twitter handle [@danzn1](https://twitter.com/danzn1).

If you know of further existing analysis about those games, please let me know, and I will add links to this repository.
<br>
<br>
<h2>Games:</h2>

<h3>ID: 2417 - Bayern Munchen vs Dortmund on 2019-11-09</h3>

- [Watch The Game On Footballia](https://footballia.net/matches/bayern-munchen-borussia-dortmund-bundesliga-2019-2020)
- [WhoScored MatchCentre](https://www.whoscored.com/Matches/1388229/Live/Germany-Bundesliga-2019-2020-Bayern-Munich-Borussia-Dortmund)  
- [Miasanrot Game Review (DEU)](https://miasanrot.de/bayern-bvb-analyse-bundesliga/)

<br>
<h3>ID: 3749 - Dortmund vs Bayern Munchen on 2020-05-26</h3>

- [Watch The Game On Footballia](https://footballia.net/matches/borussia-dortmund-bayern-munchen-bundesliga-2019-2020)
- [WhoScored MatchCentre](https://www.whoscored.com/Matches/1388424/Live/Germany-Bundesliga-2019-2020-Borussia-Dortmund-Bayern-Munich)  
- [Miasanrot Game Review (DEU)](https://miasanrot.de/10-bayern-schlaegt-dortmund-im-spiel-um-deutsche-meisterschaft/)  
- [@cc_eckner Game Preview Video Blog on Spielverlagerung (DEU)](https://spielverlagerung.de/2020/05/24/dortmund-gegen-bayern-welche-faktoren-entscheiden-das-duell/)  

<br>
<h3>ID: 2440 - Liverpool vs Manchester City on 2019-11-10</h3>

- [Watch The Game On Footballia](https://footballia.net/matches/liverpool-fc-manchester-city-premier-league-2019-2020)
- [WhoScored MatchCentre](https://www.whoscored.com/Matches/1376001/Live/England-Premier-League-2019-2020-Liverpool-Manchester-City)

<br>
<h3>ID: 4039 - Manchester City vs Liverpool on 2020-07-02</h3>

- [Watch The Game On Footballia](https://footballia.net/matches/manchester-city-liverpool-fc-premier-league-2019-2020)
- [WhoScored MatchCentre](https://www.whoscored.com/Matches/1376248/Live/England-Premier-League-2019-2020-Manchester-City-Liverpool)

<br>
<h3>ID: 2841 - FC Barcelona vs Real Madrid on 2019-12-18</h3>

- [Watch The Game On Footballia](https://footballia.net/matches/fc-barcelona-real-madrid-liga-1-division-2019-2020)
- [WhoScored MatchCentre](https://www.whoscored.com/Matches/1394515/Live/Spain-LaLiga-2019-2020-Barcelona-Real-Madrid)

<br>
<h3>ID: 3442 - Real Madrid vs FC Barcelona on 2020-03-01</h3>

- [Watch The Game On Footballia](https://footballia.net/matches/real-madrid-fc-barcelona-liga-1-division-2019-2020)
- [WhoScored MatchCentre](https://www.whoscored.com/Matches/1394360/Live/Spain-LaLiga-2019-2020-Real-Madrid-Barcelona)

<br>
<h3>ID: 2068 - Inter vs Juventus on 2019-10-06</h3>

- [Watch The Game On Footballia](https://footballia.net/matches/fc-internazionale-juventus-fc-serie-a-2019-2020)
- [WhoScored MatchCentre](https://www.whoscored.com/Matches/1415759/Live/Italy-Serie-A-2019-2020-Inter-Juventus)

<br>
<h3>ID: 3518 - Juventus vs Inter on 2020-03-08</h3>

- [Watch The Game On Footballia](https://footballia.net/matches/juventus-fc-fc-internazionale-serie-a-2019-2020)
- [WhoScored MatchCentre](https://www.whoscored.com/Matches/1415944/Live/Italy-Serie-A-2019-2020-Juventus-Inter)

<br>
<h3>ID: 2269 - Paris vs Marseille on 2019-10-27</h3>

- [Watch The Game On Footballia](https://footballia.net/matches/paris-saint-germain-olympique-de-marseille-ligue-1-2019-2020)
- [WhoScored MatchCentre](https://www.whoscored.com/Matches/1376701/Live/France-Ligue-1-2019-2020-Paris-Saint-Germain-Marseille)

<br>

<h2>Working with the data:</h2>

[PySport's](https://twitter.com/PySportOrg) [kloppy](https://github.com/PySport/kloppy) is a python package that standardizes the handling of various event and tracking data providers and supports SkillCorner data. [Look here](https://kloppy.pysport.org/quickstart/broadcast_tracking_data/) for a quickstart.

[Lars Maurath](https://twitter.com/thesignigame) has released a [First Look at SkillCorner's Open Source Tracking Dataset](https://www.thesignificantgame.com/portfolio/first-look-at-skillcorner-s-free-tracking-dataset/) using R.