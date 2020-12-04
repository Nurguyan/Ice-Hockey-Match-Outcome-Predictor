# Ice hockey match outcome predicting model
A prediction model of matches' outcome for Ice Hockey Junior League of Québec.

## Dataset
The dataset contains 1008 data points (504 matches) from September 2018 to March 2020 of Regular Season. Teams that quit the league were excluded from the dataset namely STG (MONTAGNARDS de ST-GABRIEL-DE-BRANDON) and MTN (Arctic de Montréal-Nord Junior AAA).
Each data point is a set of statistical data as shown on the table below.

| Column | Description |
| --- | --- |
| Date | Date of the match | 
| Location | Home or Away | 
| Team | Shortcut of team name | 
| GF | Total number of goals team scored in season (so far) | 
| GA | Total number of goals scored against the team in season (so far) |
| GF% | GF percentage | 
| GA% | GA percentage | 
| Sh% | Ratio of goals team scored compared to shots taken |
| Sv% | Ratio of goals allowed compared to shots stopped by goalie | 
| PP% | Power Play Success Rate. Ratio where team scored a goal while opposing team had one less man on the ice | 
| PK% | Power Kill Success Rate. Ratio of times team stopped opposing team from scoringwhile they were down a man due to a penalty | 
| Class | Win or Loss | 

### Parser
The data was obtained by parsing official website of Ice Hockey Junior League of Québec: https://www.lhjaaaq.com/. If you want to check the parser, see here: https://github.com/Nurguyan/LHJAAAQ-Horaire-Parser
