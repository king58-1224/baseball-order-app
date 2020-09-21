# README

## teams テーブル

| Column        | Type   | Options     |
| ------------- | ------ | ----------- |
| team_name     | string | null: false |
| email         | string | null: false |
| password      | string | null: false |

### Association
- has_many :players


## players テーブル

| Column           | Type   | Options     |
| ---------------- | ------ | ----------- |
| player_name      | string | null: false |
| uniform_number   | string | null: false |

### Association

- belong_to :team
