# Sleeper-API-Tutorial

[<img align="left" alt="Sleeper" width="50px" src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fsleepercdn.com%2Fimages%2Flogos%2Fog_logo-66ee2f04c1dc70ba8cb5ec9f780990d1.png%3Fvsn%3Dd&f=1&nofb=1" />][Sleeper] 
[<img align="left" alt="Python" width="50px" src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcode.fb.com%2Fwp-content%2Fuploads%2F2016%2F05%2F2000px-Python-logo-notext.svg_.png&f=1&nofb=1" />][Python]

[Sleeper]: https://sleeper.app/
[Python]: https://www.python.org/

<br />
<br />

## This repository consists of two files

 - [`Sleeper-API-Tutorial.ipynb`](https://github.com/maxbolger/Sleeper-API-Tutorial/blob/master/Sleeper-API-Tutorial.ipynb)
    - This tutorial walks users through Sleeper's API for data retrieval purposes to run analyses on their league.<br />
    It utilizes the [sleeper-api-wrapper](https://pypi.org/project/sleeper-api-wrapper/).<br />
    Note: Sleeper removed the `Stats` endpoint from their API per the request of their data provider, so it no longer works.
 
 - [`nfl-player-data.csv`](https://github.com/maxbolger/Sleeper-API-Tutorial/blob/master/nfl-player-data.csv)
    - This is a cleaned dataframe of nearly every active player in Sleeper's player database.<br /> 
     ***Note all information in this file is as of 08/17/20***
    - `full_name`: the player's full name (`object`)
    - `team`: the player's current team (`object`)
    - `position`: the player's current position(s) (`object`)
    - `height`: the player's height (`object`)
    - `inches`: the player's height in inches (`int64`)
    - `weight`: the player's current weight (`int64`)
    - `birth_date`: the player's birth date *(YYYY-MM-DD)* (`object`)
    - `age`: the player's current age (`float64`)
    - `years_exp`: the player's years of experience (`float64`)
    - `college`: the player's alma mater (`object`)
    - `number`: the player's current number (`int64`)
    - `nflfastr_name`: the player's name in the format [nflfastR](https://mrcaseb.github.io/nflfastR/) uses (`object`)
    
### Thanks for checking out the repository, and I hope you find these files useful!
    

