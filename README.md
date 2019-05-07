# ![LOGO](logo.png) NFL v3 Scores **flow**ground Connector

## Description

A generated **flow**ground connector for the NFL v3 Scores API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/fantasydata.net/nfl-v3-scores/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:37+03:00

## API Description

NFL schedules, scores, odds, weather, and news API.

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Teams (All)

> Gets all teams, including pro bowl teams.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Are Games In Progress

> Returns <code>true</code> if there is at least one game being played at the time of the request or <code>false</code> if there are none.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Bye Weeks

> Get bye weeks for the teams during a specified NFL season.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - 
          Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        

### Season Current

> Year of the current NFL season. This value changes on July 1st. The earliest season for Fantasy data is 2001. The earliest season for Team data is 1985. The earliest season for Fantasy data is 2001. The earliest season for Team data is 1985.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Week Current

> Number of the current week of the NFL season. This value usually changes on Tuesday nights or Wednesday mornings at midnight EST. Week number is an integer between 1 and 21 or the word current. Weeks 1 through 17 are regular season weeks. Weeks 18 through 21 are post-season weeks.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Player Details by Free Agents

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Game Stats by Season (Deprecated, use Team Game Stats instead)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        

### Game Stats by Week (Deprecated, use Team Game Stats instead)

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - 
          Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - 
          Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        

### Season Last Completed

> Year of the most recently completed season. this value changes immediately after the Super Bowl. The earliest season for Fantasy data is 2001. The earliest season for Team data is 1985.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Week Last Completed

> Number of the last completed week in the current NFL season. This value changes immediately after the last game of the week is completed and the data is available. This usually happens right after the Monday night game.<br/>
>         Week number is an integer between 1 and 21 or the word current. Weeks 1 through 17 are regular season weeks. Weeks 18 through 21 are post-season weeks.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### News

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### News by Date

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `date` - _required_ - The date of the news.
<br>Examples: <code>2017-JUL-31</code>, <code>2017-SEP-01</code>.

### News by Player

#### Input Parameters
* `format` - _required_ - 
          Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
        
    Possible values: XML, JSON.
* `playerid` - _required_ - Each NFL player has a unique ID assigned by FantasyData. Player IDs can be determined by pulling player related data. Example:<code>14257</code>.

### News by Team

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `team` - _required_ - Abbreviation of the team. Example: <code>WAS</code>.

### X Ping

> Ping NFL API

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Player Details by Player

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `playerid` - _required_ - Each NFL player has a unique ID assigned by FantasyData. Player IDs can be determined by pulling player related data. Example:<code>732</code>.

### Player Details by Available

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Player Details by Team

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `team` - _required_ - Abbreviation of the team. Example: <code>WAS</code>.

### Player Details by Rookie Draft Year

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season.<br>Examples: <code>2018</code>, <code>2019</code>, etc.

### Schedule

> Game schedule for a specified season.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season (with optional season type).<br>Examples: <code>2018</code>, <code>2018PRE</code>, <code>2018POST</code>, <code>2018STAR</code>, <code>2019</code>, etc.

### Scores by Season

> Game scores for a specified season.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - Year of the season (with optional season type).<br>Examples: <code>2018</code>, <code>2018PRE</code>, <code>2018POST</code>, <code>2018STAR</code>, <code>2019</code>, etc.

### Scores by Week

> Get game scores for a specified week of a season.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - 
          Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - 
          Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        

### Scores by Week Simulation

> Gets simulated live scores of NFL games, covering the Conference Championship games on January 21, 2018.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `numberofplays` - _required_ - The number of plays to progress in this NFL live game simulation. Example entries are <code>0</code>, <code>1</code>, <code>2</code>, <code>3</code>, <code>150</code>, <code>200</code>, etc.

### Stadiums

> This method returns all stadiums.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Standings

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - 
          Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        

### Team Game Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - 
          Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        
* `week` - _required_ - 
          Week of the season. Valid values are as follows: Preseason 0 to 4, Regular Season 1 to 17, Postseason 1 to 4.
          Example: <code>1</code>
        

### Team Season Stats

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - 
          Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        

### Teams (Active)

> Gets all active teams.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Teams by Season

> List of teams playing in a specified season.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `season` - _required_ - 
          Year of the season and the season type. If no season type is provided, then the default is regular season.
          <br>Examples: <code>2015REG</code>, <code>2015PRE</code>, <code>2015POST</code>.
        

### Timeframes

> Get detailed information about past, present, and future timeframes.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.
* `type` - _required_ - The type of timeframes to return.  Valid entries are <code>current</code> or <code>upcoming</code> or <code>completed</code> or <code>recent</code> or <code>all</code>.
    Possible values: current, upcoming, completed, recent, all.

### Season Upcoming

> Year of the current NFL season, if we are in the mid-season. If we are in the off-season, then year of the next upcoming season. This value changes immediately after the Super Bowl. The earliest season for Fantasy data is 2001. The earliest season for Team data is 1985.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

### Week Upcoming

> Number of the upcoming week of the NFL season. This value changes immediately after the final game of the week is completed. We consider upcoming week to be the current week, until current week is over. Week number is an integer between 1 and 21 or the word current. Weeks 1 through 17 are regular season weeks. Weeks 18 through 21 are post-season weeks.

#### Input Parameters
* `format` - _required_ - Desired response format. Valid entries are <code>XML</code> or <code>JSON</code>.
    Possible values: XML, JSON.

## License

**flow**ground :- Telekom iPaaS / fantasydata-net-nfl-v-3-scores-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
