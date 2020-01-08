API

java | rails |
:-: | :-: |
/api/public/sunpeople/payslip/ldap_auth | /json_web_token |
fff | ggg|

RabbitMQ

java | message | rails worker |
:-: | :-: | :-: |
/api/v2/annual_bonus/{year}/grant | OccupationTaxCalculateMessage  | EmolumentOccupationTaxCalculateWorker |
/api/v2/annual_bonus/double_pay/{id}/batch_can_grant/{canGrant} | OccupationTaxCalculateMessage  | EmolumentOccupationTaxCalculateWorker |
/api/v2/annual_bonus/double_pay/{id}/cancel_grant | OccupationTaxCalculateMessage  | EmolumentOccupationTaxCalculateWorker |
/api/v2/annual_bonus/incentive_pay/{id}/batch_can_grant/{canGrant} | OccupationTaxCalculateMessage  | EmolumentOccupationTaxCalculateWorker |
/api/v2/annual_bonus/incentive_pay/{id}/cancel_grant | OccupationTaxCalculateMessage  | EmolumentOccupationTaxCalculateWorker |
/api/v2/annual_bonus/year_end_pay/{id}/batch_can_grant/{canGrant} | OccupationTaxCalculateMessage  | EmolumentOccupationTaxCalculateWorker |
/api/v2/annual_bonus/year_end_pay/{id}/cancel_grant | OccupationTaxCalculateMessage  | EmolumentOccupationTaxCalculateWorker |
