# nba-playoff-analysis
This project examines NBA playoff offensive performance by first analyzing scoring efficiency against shot volume, then expanding the model to include playmaking and turnover data to better measure overall offensive impact.

The goal is to compare pure scorers with players who take on broader offensive responsibilities as primary creators for their teams

## Data Source
All data used in this project was collected from publicly available NBA box score statistics via NBA.com. It includes player-level playoff performance metrics such as points, field goal attempts, shooting percentages, assists, turnovers, and other standard efficiency indicators.

## Methodology
This analysis is structured in two stages:
### Scoring Efficiency vs. Volume

The first model explores the relationship between shot volume (FGA), scoring efficiency (FG%), and total scoring output (PTS).

This helps identify high-usage players who maintain efficiency under playoff pressure.

### Expanded Offensive Impact Model

The second model adds additional variables such as assists (AST), Turnovers (TOV), and efficency metrics (TS%), providing a more expansive of offensive responsibility beyond scoring.

## Key Findings

High-volume scorers such as Shai Gilgeous-Alexander and Jalen Brunson maintain strong efficiency despite heavy offensive workloads

Playmakers such as Tyrese Haliburton contribute more through creation than scoring, leading dataset in assists

Expanding the model demonstrates that offensive impact can be further defined by a player’s ability to generate offense for others.

## Key Insights

The analysis shows a clear distinction between two offensive roles:

Scorers - players who generate consistent offense through shot creation and isolated scoring

Offensive Engines - players who drive team offense through passing, tempo control, and decision-making

Neither is superior. They represent different ways of producing offensive value in a playoff environment

## Limitations

Field goal percentage does not account for shot values (2PT vs 3PT vs FT)

Defensive context and matchups are not included

Player role and team system effects are not controlled for

Total production may be infleunced by minutes and games played

## Future Improvements

Player clustering for offensive archetypes

Defensive adjustment factors

Advanced impact metrics (on/off, lineup data)

## Author Note

This project was completed as part of a sports analytics portfolio exploring NBA playoff performance through data-driven modeling.
