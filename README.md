![MIKES DATA WORK GIT REPO](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_01.png "Mikes Data Work")        

# Force Protocol Encryption Error
**Post Date: May 20, 2006**        



## Contents    
- [About Process](##About-Process)  
- [SQL Logic](#SQL-Logic)  
- [Build Info](#Build-Info)  
- [Author](#Author)  
- [License](#License)       

## About-Process    <div>
I get amazed some times with how long one can be doing sql administraiton, and yet still get blindsided by the strange and unusual. i get this error message one day just starting up my machine. apparently i can't connect to any of the SQL Servers i have registered in enterprise manager. the situation will drive you nuts cause you don't know what 'changed' to create such a problem. never mind looking over documents about 'microsoft certificates' about security and so forth…[more] [Microsoft][ODBC SQL Server Driver][Shared Memory]Encryption not supported on SQL Server [Microsoft][ODBC SQL Server Driver][Shared Memory]ConnectionOpen (PreLoginHandshake())
here's a quick solution.just go to: start -> run -> type in: cliconfg.execheck to see if this is enabled: "Force protocol encryption"it should NOT be enabled.once this is unchecked you should be able to connect to all your sql servers again. this issue is just plain crazy. thats it. by the way this option should be disabled by default. however; i've noticed that it 'might' be enabled after installation. possibly due to some other cooperative install config setting for your workstation, or servers. hope this is useful.



[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

[![Gist](https://img.shields.io/badge/Gist-MikesDataWork-<COLOR>.svg)](https://gist.github.com/mikesdatawork)
[![Twitter](https://img.shields.io/badge/Twitter-MikesDataWork-<COLOR>.svg)](https://twitter.com/mikesdatawork)
[![Wordpress](https://img.shields.io/badge/Wordpress-MikesDataWork-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)





---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Mikes Data Work](https://raw.githubusercontent.com/mikesdatawork/images/master/git_mikes_data_work_banner_02.png "Mikes Data Work")

