#  V1

- Create database
- use football-API and store players
- Create dashboard including: top brighton fit, list of players w/ filters, graph (age vs G/A)
- Create a brighton-scout formula
- Show a list of players who meet the brighton-score fomula

## What each row should have
**Identity**

* `player_id`
* `name`
* `photo_url`
* `age`
* `date_of_birth`
* `nationality`
* `position`
* `height_cm`
* `weight_kg`

**Club Context**

* `team`
* `league`
* `country`
* `season`
* `contract_end`

**Market Data**

* `market_value_eur`
* `market_value_last_year`
* `value_change_pct`

**Playing Time**

* `appearances`
* `starts`
* `minutes`
* `minutes_per_match`

**International Recognition**

* `national_team`
* `senior_caps`
* `senior_goals`
* `u21_caps`
* `u21_goals`

**Attacking**

* `goals`
* `assists`
* `shots`
* `shots_on_target`
* `goal_contributions`

**Creativity**

* `key_passes`
* `big_chances_created`
* `crosses_completed`

**Ball Progression**

* `dribbles_attempted`
* `dribbles_completed`
* `dribble_success_rate`
* `pass_accuracy`

**Defensive**

* `tackles`
* `interceptions`
* `blocks`
* `recoveries`

**Physical**

* `duels_total`
* `duels_won`
* `duel_win_pct`
* `aerial_duels_won`

**Discipline**

* `yellow_cards`
* `red_cards`
* `fouls_committed`

**Derived Metrics**

* `age_score`
* `production_score`
* `creativity_score`
* `possession_score`
* `defensive_score`
* `international_score`
* `value_score`

**Final Outputs**

* `brighton_fit_score`
* `predicted_market_value`
* `value_gap`
* `recruitment_score`
