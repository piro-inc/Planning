# Database Layout

## Tables

| Tables      |
|-------------|
| Users       |
| Games       |
| Comments    |
| Join Tables |

## Users

| Field Name | Data Type|
| -----------|----------|
| id         | Integer  |
| username   | String   |
| password   | String   |
| email      | String   |

## Games

| Field Name   | Data Type |
|--------------|-----------|
| id           | Integer   |
| user_id      | Integer   |
| date_time    | Timestamp |
| location     | String    |
| team_a_name  | String    |
| team_b_name  | String    |
| is_complete  | Boolean   |
| team_a_score | Integer   |
| team_b_score | Integer   |
| sport_name   | String    |

^ eg; 'Fraser Park 1'

## Comments

| Field Name | Data Type |
|------------|-----------|
| id         | Integer   |
| game_id    | Integer   |
| comment    | String    |
