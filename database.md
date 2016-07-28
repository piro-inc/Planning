# Database Layout

## Tables

| Tables      |
|-------------|
| Users       |
| Games       |
| Comments    |
| Join Tables |

- Users
- Games
- Join Tables

## Users

| Field Name | Data Type|
| -----------|----------|
| id         | Integer  |
| username   | String   |
| password   | String   |
| email      | String   |

- id [int]
- username [str]
- password [str]
- email [str]

## Games

| Field Name   | Data Type |
|--------------|-----------|
| id           | Integer   |
| user_id      | Integer   |
| date / time  | Timestamp |
| location^    | String    |
| team_a_name  | String    |
| team_b_name  | String    |
| is_complete  | Boolean   |
| team_a_score | Integer   |
| team_b_score | Integer   |
| sport_name   | String    |

^ eg; 'Fraser Park 1'

- id [int]
- user_id [int]
- date/ start time [timestamp]
- location ('Fraser Park 1') [str]
- team_a_name [str]
- team_b_name [str]
- is_complete [boolean]
- team_a_score [int]
- team_b_score [int]
- sport_name [str]

## Comments

| Field Name | Data Type |
|------------|-----------|
| id         | Integer   |
| game_id    | Integer   |
| comment    | String    |

- id [int]
- game_id [str]
- comment [str]
