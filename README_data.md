# Data Summary

## SUMMARY

- **143,195** Player Injury Histories
- **901,457** Player Market Values
- **92,701** Player National Team Performances
- **1,878,719** Player Performances
- **92,671** Player Profiles
- **1,257,342** Player Teammates Played With
- **1,101,440** Player Transfer Histories
- **7,695** Teams Children
- **196,378** Teams Competitions Seasons
- **2,175** Teams Details

**Players Total Count:** 5,467,525
**Teams Total Count:** 206,248
**All Total Count:** 5,673,773

---

## player_injury_histories
- **Full Path**: `/datalake/transfermarkt/raw/player_injury_histories/player_injury_histories`
- **Row Count**: 143,195

**Preview (first 5 rows):**

|   player_id | season   | injury_reason    | from_date   | end_date   | days_missed   | games_missed   |
|------------:|:---------|:-----------------|:------------|:-----------|:--------------|:---------------|
|          10 | 15/16    | Hand injury      | 19.04.2016  | 29.04.2016 | 11 days       | 2              |
|          10 | 15/16    | Thigh problems   | 18.12.2015  | 31.12.2015 | 14 days       | 1              |
|          10 | 15/16    | Capsular injury  | 11.11.2015  | 21.11.2015 | 11 days       | -              |
|          10 | 15/16    | Rest             | 04.11.2015  | 06.11.2015 | 3 days        | 1              |
|          10 | 15/16    | Hamstring injury | 20.08.2015  | 08.10.2015 | 50 days       | 10             |

---

## player_market_values
- **Full Path**: `/datalake/transfermarkt/raw/player_market_values/player_market_values`
- **Row Count**: 901,457

**Preview (first 5 rows):**

|   player_id | date_unix   |   value |
|------------:|:------------|--------:|
|     1000135 | 2023-09-10  |   25000 |
|     1000135 | 2023-10-12  |   50000 |
|     1000135 | 2023-12-19  |  100000 |
|     1000135 | 2024-06-23  |  100000 |
|     1000135 | 2024-12-17  |  100000 |

---

## player_national_team_performances
- **Full Path**: `/datalake/transfermarkt/raw/player_national_team_performances/player_national_team_performances`
- **Row Count**: 92,701

**Preview (first 5 rows):**

|   player_id |   team_id |   matches |   goals |   shirt_number | debut      |   coach_id |   debut_game_id | career_state           |
|------------:|----------:|----------:|--------:|---------------:|:-----------|-----------:|----------------:|:-----------------------|
|           1 |      9067 |         1 |       0 |              0 |            |            |         2633677 | FORMER_NATIONAL_PLAYER |
|           1 |     17368 |         8 |       3 |              0 |            |            |                 | FORMER_NATIONAL_PLAYER |
|           1 |     17662 |        14 |       8 |             18 |            |       4275 |         2359032 | FORMER_NATIONAL_PLAYER |
|       10001 |      3509 |         1 |       0 |              0 | 2003-11-18 |       2693 |         3540763 | FORMER_NATIONAL_PLAYER |
|       10001 |     21103 |        11 |       0 |              0 |            |            |                 | FORMER_NATIONAL_PLAYER |

---

## player_performances
- **Full Path**: `/datalake/transfermarkt/raw/player_performances/player_performances`
- **Row Count**: 1,878,719

**Preview (first 5 rows):**

|   player_id | season   | competition_url                                                      | competition_name   | team_url                                                           | team_name                   |   nb_in_group | nb_on_pitch   | goals   | assists   | own_goals   | subed_in   | subed_out   | yellow_cards   | second_yellow_cards   | direct_red_cards   | penalty_goals   | minutes_played   | goals_conceded   | clean_sheets   |
|------------:|:---------|:---------------------------------------------------------------------|:-------------------|:-------------------------------------------------------------------|:----------------------------|--------------:|:--------------|:--------|:----------|:------------|:-----------|:------------|:---------------|:----------------------|:-------------------|:----------------|:-----------------|:-----------------|:---------------|
|           1 | 08/09    | /nofv-oberliga-sud/startseite/wettbewerb/OBLG/saison_id/2008         | NOFV-Oberliga Süd  | /fc-eilenburg/startseite/verein/4825/saison_id/2008                | FC Eilenburg                |             9 | 9             | -       | -         | -           | -          | 2           | -              | -                     | 1                  | -               | -                |                  |                |
|           1 | 07/08    | /regionalliga-sud-bis-07-08-/startseite/wettbewerb/RS/saison_id/2007 | Regionalliga Süd   | /fsv-ludwigshafen-oggersheim/startseite/verein/1526/saison_id/2007 | FSV Ludwigshafen Oggersheim |            22 | 22            | 1       | -         | -           | 3          | 8           | 1              | -                     | -                  | -               | 1.580'           |                  |                |
|           1 | 06/07    | /2-bundesliga/startseite/wettbewerb/L2/saison_id/2006                | 2. Bundesliga      | /tus-koblenz/startseite/verein/996/saison_id/2006                  | TuS Koblenz                 |            10 | 4             | -       | -         | -           | 4          | -           | -              | -                     | -                  | -               | -                |                  |                |
|           1 | 06/07    | /dfb-pokal/startseite/pokalwettbewerb/DFB/saison_id/2006             | DFB-Pokal          | /tus-koblenz/startseite/verein/996/saison_id/2006                  | TuS Koblenz                 |             1 | -             | -       | -         | -           | -          | -           | -              | -                     | -                  | -               | -                |                  |                |
|           1 | 05/06    | /2-bundesliga/startseite/wettbewerb/L2/saison_id/2005                | 2. Bundesliga      | /spvgg-unterhaching/startseite/verein/66/saison_id/2005            | SpVgg Unterhaching          |            26 | 14            | 1       | 1         | -           | 12         | 1           | 1              | -                     | -                  | -               | 388'             |                  |                |

---

## player_profiles
- **Full Path**: `/datalake/transfermarkt/raw/player_profiles/player_profiles`
- **Row Count**: 92,671

**Preview (first 5 rows):**

|   player_id | player_slug    | player_name            | player_image_url                                                                      | Date of birth URL                                      | Date of birth   | Place of birth Country   | Place of birth     | Height URL           | Height   | Citizenship Country   | Citizenship   | Position                | Foot URL             | Foot   | Current club URL                               | Current club          | Joined     | Contract expires   | player_main_position   | player_sub_position             | Full name                     | Player agent URL                                                         | Player agent         | Name in home country   | Social-Media URL                   | Social-Media   | Contract option   | Outfitter   | On loan from URL   | On loan from   | Contract there expires   | Last contract extension   | 2nd club URL   | 2nd club   | Citizenship URL   | 3nd club URL   | 3nd club   | Date of death   | Place of birth URL   | 4nd club URL   | 4nd club   |
|------------:|:---------------|:-----------------------|:--------------------------------------------------------------------------------------|:-------------------------------------------------------|:----------------|:-------------------------|:-------------------|:---------------------|:---------|:----------------------|:--------------|:------------------------|:---------------------|:-------|:-----------------------------------------------|:----------------------|:-----------|:-------------------|:-----------------------|:--------------------------------|:------------------------------|:-------------------------------------------------------------------------|:---------------------|:-----------------------|:-----------------------------------|:---------------|:------------------|:------------|:-------------------|:---------------|:-------------------------|:--------------------------|:---------------|:-----------|:------------------|:---------------|:-----------|:----------------|:---------------------|:---------------|:-----------|
|           1 | silvio-adzic   | Silvio Adzic (1)       | https://img.a.transfermarkt.technology/portrait/header/1-1465832419.jpg?lm=1          | /aktuell/waspassiertheute/aktuell/new/datum/1980-09-23 | 23.09.1980      | Germany                  | Grünstadt          | /intern/faq/#ds_info | N/A      | Germany               | Germany       | Attack - Right Winger   | /intern/faq/#ds_info | N/A    | /retired/startseite/verein/123                 | Retired               | 01.07.2017 | -                  | Right Winger           | Left Winger, Attacking Midfield |                               |                                                                          |                      |                        |                                    |                |                   |             |                    |                |                          |                           |                |            |                   |                |            |                 |                      |                |            |
|      100011 | everton-silva  | Éverton Silva (100011) | https://img.a.transfermarkt.technology/portrait/header/s_100011_15172_2010_1.jpg?lm=1 | /aktuell/waspassiertheute/aktuell/new/datum/1988-08-04 | 04.08.1988      | Brazil                   | São João de Meriti |                      | 1,71 m   | Brazil                | Brazil        | Defender - Right-Back   |                      | right  | /vereinslos/startseite/verein/515              | Without Club          | 01.03.2025 | -                  | Right-Back             | Right Midfield, Left-Back       | Éverton José Modesto da Silva | /romulo-noronha-agenciamento-esportivo-eirelli/beraterfirma/berater/8373 | RN Sports            |                        |                                    |                |                   |             |                    |                |                          |                           |                |            |                   |                |            |                 |                      |                |            |
|          10 | miroslav-klose | Miroslav Klose (10)    | https://img.a.transfermarkt.technology/portrait/header/10-1448468291.jpg?lm=1         | /aktuell/waspassiertheute/aktuell/new/datum/1978-06-09 | 09.06.1978      | Germany                  | Opole              |                      | 1,84 m   | Germany               | Germany       | Attack - Centre-Forward |                      | right  | /retired/startseite/verein/123                 | Retired               | 01.07.2016 | -                  | Centre-Forward         |                                 |                               | /asbw-sport-marketing-gmbh/beraterfirma/berater/1126                     | ASBW Sport Marketing | Miroslav Josef Klose   | http://miroslavklose.de/           |                |                   |             |                    |                |                          |                           |                |            |                   |                |            |                 |                      |                |            |
|       10001 | john-thompson  | John Thompson (10001)  | https://img.a.transfermarkt.technology/portrait/header/default.jpg?lm=1               | /aktuell/waspassiertheute/aktuell/new/datum/1981-10-12 | 12.10.1981      | Ireland                  | Dublin             |                      | 1,83 m   | Ireland               | Ireland       | Defender - Right-Back   |                      | both   | /retired/startseite/verein/123                 | Retired               | 01.07.2013 | -                  | Right-Back             | Centre-Back, Right Midfield     |                               |                                                                          |                      | John Paul Thompson     |                                    |                |                   |             |                    |                |                          |                           |                |            |                   |                |            |                 |                      |                |            |
|      100001 | carlos-auzqui  | Carlos Auzqui (100001) | https://img.a.transfermarkt.technology/portrait/header/100001-1604497657.jpg?lm=1     | /aktuell/waspassiertheute/aktuell/new/datum/1991-03-16 | 16.03.1991      | Argentina                | Longchamps         |                      | 1,80 m   | Argentina             | Argentina     | Attack - Right Winger   |                      | right  | /club-atletico-tucuman/startseite/verein/14554 | Club Atlético Tucumán | 30.01.2025 | 31.12.2025         | Right Winger           | Left Winger                     |                               | /oller-group/beraterfirma/berater/5240                                   | OLLER GROUP          | Carlos Daniel Auzqui   | http://www.instagram.com/auzqui91/ |                |                   |             |                    |                |                          |                           |                |            |                   |                |            |                 |                      |                |            |

---

## player_teammates_played_with
- **Full Path**: `/datalake/transfermarkt/raw/player_teammates_played_with/player_teammates_played_with`
- **Row Count**: 1,257,342

**Preview (first 5 rows):**

|   player_id | player_with_url                          | player_with_name   |   ppg_played_with | joint_goal_participation   |   minutes_played_with |
|------------:|:-----------------------------------------|:-------------------|------------------:|:---------------------------|----------------------:|
|      100001 | /leonardo-jara/profil/spieler/116163     | Leonardo Jara      |              1.69 | 2                          |                 4.975 |
|      100001 | /guido-carrillo/profil/spieler/184672    | Guido Carrillo     |              1.74 | 4                          |                 4.106 |
|      100001 | /gaston-gil-romero/profil/spieler/222052 | Gastón Gil Romero  |              1.64 | 1                          |                 4.297 |
|      100001 | /rafael-perez/profil/spieler/117874      | Rafael Pérez       |              1.65 | -                          |                 3.766 |
|      100001 | /nahuel-tenaglia/profil/spieler/533568   | Nahuel Tenaglia    |              1.77 | 1                          |                 3.527 |

---

## player_transfer_histories
- **Full Path**: `/datalake/transfermarkt/raw/player_transfer_histories/player_transfer_histories`
- **Row Count**: 1,101,440

**Preview (first 5 rows):**

|   player_id | season   | date       | date_unformatted   | from_team_url                                         | from_team_name   | to_team_url                                          | to_team_name    | value_at_transfer   | transfer_fee   |   transfer_id |
|------------:|:---------|:-----------|:-------------------|:------------------------------------------------------|:-----------------|:-----------------------------------------------------|:----------------|:--------------------|:---------------|--------------:|
|        1000 | 11/12    | 01.07.2011 | 2011-07-01         | /a-ludwigshafen/transfers/verein/3496/saison_id/2011  | A. Ludwigshafen  | /retired/transfers/verein/123/saison_id/2011         | Retired         | EUR200k             | -              |        597199 |
|        1000 | 10/11    | 01.01.2011 | 2011-01-01         | /w-mannheim/transfers/verein/85/saison_id/2010        | W. Mannheim      | /a-ludwigshafen/transfers/verein/3496/saison_id/2010 | A. Ludwigshafen | EUR200k             | free transfer  |        505685 |
|        1000 | 07/08    | 01.07.2007 | 2007-07-01         | /saarbrucken/transfers/verein/1/saison_id/2007        | Saarbrücken      | /w-mannheim/transfers/verein/85/saison_id/2007       | W. Mannheim     | EUR125k             | free transfer  |        121657 |
|        1000 | 00/01    | 01.07.2000 | 2000-07-01         | /fk-pirmasens/transfers/verein/726/saison_id/2000     | FK Pirmasens     | /saarbrucken/transfers/verein/1/saison_id/2000       | Saarbrücken     | -                   | free transfer  |          2850 |
|           1 | 17/18    | 01.07.2017 | 2017-07-01         | /tus-niederkir-/transfers/verein/58701/saison_id/2017 | TuS Niederkir.   | /retired/transfers/verein/123/saison_id/2017         | Retired         | -                   | -              |       2864036 |

---

## teams_children
- **Full Path**: `/datalake/transfermarkt/raw/teams_children/teams_children`
- **Row Count**: 7,695

**Preview (first 5 rows):**

|   parent_team_id | parent_team_name      |   child_team_id | child_team_name         | _last_modified_at   |
|-----------------:|:----------------------|----------------:|:------------------------|:--------------------|
|            10370 | Racing Club Harelbeke |           10370 | Racing Club Harelbeke   | 2025-09-13 13:11:27 |
|            10370 | Racing Club Harelbeke |           81362 | Racing Harelbeke U21    | 2025-09-13 13:11:27 |
|            10370 | Racing Club Harelbeke |           78589 | Racing Harelbeke Jugend | 2025-09-13 13:11:27 |
|             1060 | Colchester United     |            1060 | Colchester United       | 2025-09-13 10:18:58 |
|             1060 | Colchester United     |           45633 | Colchester United U21   | 2025-09-13 10:18:58 |

---

## teams_competitions_seasons
- **Full Path**: `/datalake/transfermarkt/raw/teams_competitions_seasons/teams_competitions_seasons`
- **Row Count**: 196,378

**Preview (first 5 rows):**

| club_division   |   club_id | competition_id   | competition_name   |   season_draws |   season_goal_difference |   season_goals_against |   season_goals_for |   season_id | season_is_two_point_system   | season_league_competition_id   | season_league_league_name   | season_league_league_slug   | season_league_level_level_name   |   season_league_level_level_number |   season_league_season_id |   season_losses |   season_manager |   season_manager_manager_id | season_manager_manager_name   | season_manager_manager_slug   |   season_points |   season_points_against |   season_points_for |   season_rank | season_season   |   season_total_matches |   season_wins | team_name        |
|:----------------|----------:|:-----------------|:-------------------|---------------:|-------------------------:|-----------------------:|-------------------:|------------:|:-----------------------------|:-------------------------------|:----------------------------|:----------------------------|:---------------------------------|-----------------------------------:|--------------------------:|----------------:|-----------------:|----------------------------:|:------------------------------|:------------------------------|----------------:|------------------------:|--------------------:|--------------:|:----------------|-----------------------:|--------------:|:-----------------|
| Third Tier      |         1 | L3               | 3. Liga            |              4 |                        5 |                     16 |                 21 |        2025 | False                        | L3                             | 3. Liga                     | 3-liga                      | Third Tier                       |                                  3 |                      2025 |               2 |              nan |                       19170 | Alois Schwartz                | alois-schwartz                |              19 |                     nan |                 nan |             3 | 25/26           |                     11 |             5 | 1.FC Saarbrücken |
| Third Tier      |         1 | L3               | 3. Liga            |             11 |                       12 |                     47 |                 59 |        2024 | False                        | L3                             | 3. Liga                     | 3-liga                      | Third Tier                       |                                  3 |                      2024 |               9 |              nan |                       19170 | Alois Schwartz                | alois-schwartz                |              65 |                     nan |                 nan |             3 | 24/25           |                     38 |            18 | 1.FC Saarbrücken |
| Third Tier      |         1 | L3               | 3. Liga            |             15 |                       17 |                     43 |                 60 |        2023 | False                        | L3                             | 3. Liga                     | 3-liga                      | Third Tier                       |                                  3 |                      2023 |               8 |              nan |                       26513 | Rüdiger Ziehl                 | rudiger-ziehl                 |              60 |                     nan |                 nan |             5 | 23/24           |                     38 |            15 | 1.FC Saarbrücken |
| Third Tier      |         1 | L3               | 3. Liga            |              9 |                       25 |                     39 |                 64 |        2022 | False                        | L3                             | 3. Liga                     | 3-liga                      | Third Tier                       |                                  3 |                      2022 |               9 |              nan |                       26513 | Rüdiger Ziehl                 | rudiger-ziehl                 |              69 |                     nan |                 nan |             5 | 22/23           |                     38 |            20 | 1.FC Saarbrücken |
| Third Tier      |         1 | L3               | 3. Liga            |             11 |                        6 |                     44 |                 50 |        2021 | False                        | L3                             | 3. Liga                     | 3-liga                      | Third Tier                       |                                  3 |                      2021 |              11 |              nan |                        4688 | Uwe Koschinat                 | uwe-koschinat                 |              53 |                     nan |                 nan |             7 | 21/22           |                     36 |            14 | 1.FC Saarbrücken |

---

## teams_details
- **Full Path**: `/datalake/transfermarkt/raw/teams_details/teams_details`
- **Row Count**: 2,175

**Preview (first 5 rows):**

|   club_id | club_slug           | club_name                   | logo_url                                                                 | country_name   |   season_id | competition_id   | competition_slug              | competition_name              | club_division                 | source_url                                                                               | _last_modified_at   |
|----------:|:--------------------|:----------------------------|:-------------------------------------------------------------------------|:---------------|------------:|:-----------------|:------------------------------|:------------------------------|:------------------------------|:-----------------------------------------------------------------------------------------|:--------------------|
|    100335 | cd-mafra-sub-23     | CD Mafra U23 (100335)       | https://tmssl.akamaized.net//images/wappen/head/100335.png?lm=1724075828 | Portugal       |        2023 |                  |                               |                               |                               | https://www.transfermarkt.com/cd-mafra-sub-23/startseite/verein/100335/saison_id/2023    | 2025-09-11 20:20:19 |
|    100431 | napoli-under-18     | Napoli Under 18 (100431)    | https://tmssl.akamaized.net//images/wappen/head/100431.png?lm=1753167643 | Italy          |        2021 | ITJ7             | campionato-nazionale-under-18 | Campionato Under 18           | Campionato Under 18           | https://www.transfermarkt.com/napoli-under-18/startseite/verein/100431/saison_id/2021    | 2025-09-13 09:55:03 |
|    101416 | venezia-under-18    | Venezia Under 18 (101416)   | https://tmssl.akamaized.net//images/wappen/head/101416.png?lm=1660032623 | Italy          |        2022 |                  |                               |                               |                               | https://www.transfermarkt.com/venezia-under-18/startseite/verein/101416/saison_id/2022   | 2025-09-13 09:37:05 |
|    100461 | lecce-under-18      | Lecce Under 18 (100461)     | https://tmssl.akamaized.net//images/wappen/head/100461.png?lm=1689169528 | Italy          |        2015 | ITJ7             | campionato-nazionale-under-18 | Campionato Under 18           | Campionato Under 18           | https://www.transfermarkt.com/lecce-under-18/startseite/verein/100461/saison_id/2015     | 2025-09-13 09:52:59 |
|     10010 | esporte-clube-bahia | Esporte Clube Bahia (10010) | https://tmssl.akamaized.net//images/wappen/head/10010.png?lm=1412879423  | Brazil         |        2006 | BRA1             | campeonato-brasileiro-serie-a | Campeonato Brasileiro Série A | Campeonato Brasileiro Série A | https://www.transfermarkt.com/esporte-clube-bahia/startseite/verein/10010/saison_id/2006 | 2025-09-13 11:59:31 |

---

