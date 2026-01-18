# iGaming-SQL-Analytics-Portfolio
This repository simulates real daily analytical work for an iGaming Data Analyst working with Product, Marketing, and CRM teams.
My goal was not having complex SQL, The goal is clear thinking, correct KPIs, and business-driven insights as i am coming from 7 years of dealing with stakeholders and HM so i know how they need the candidate to understand the hidden goals nehinde the business.
##
Tables used across all projects:
	•	players
	•	player_sessions
	•	transactions
	•	game_events
	•	campaign_attribution

  Tables Overview:

| Table Name             | Column Name         | Description |
|------------------------|---------------------|-------------|
| players                | player_id           | Unique player identifier |
|                        | registration_date   | Player signup date |
|                        | country             | Player country |
|                        | vip_level           | Loyalty / VIP tier |

| player_sessions        | session_id          | Unique session identifier |
|                        | player_id           | Player foreign key |
|                        | session_start       | Session login timestamp |
|                        | session_end         | Session logout timestamp |

| transactions           | transaction_id      | Unique transaction ID |
|                        | player_id           | Player foreign key |
|                        | transaction_time    | Deposit timestamp |
|                        | amount              | Deposit amount |

| game_events            | event_id            | Unique event identifier |
|                        | player_id           | Player foreign key |
|                        | event_time          | Event timestamp |
|                        | event_type          | Bet / Win / Loss |

| campaign_attribution   | player_id           | Player foreign key |
|                        | campaign_name       | Campaign identifier |
|                        | channel             | Acquisition channel |





  
