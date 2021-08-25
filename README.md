# Analytics Engineer Challenge

## Things You Should Know

### negotiations.csv
- id
- created_at
- buyer_entity_id
- claims

### negotiation_events.csv
- id
- created_at
- negotiation_id
- legal_entity_id
- action

### Notes
- You can *assume* the negotiation event with the highest ID is the most recent
- `buyer_entity_id` and `legal_entity_id` are from the same `legal_entities` table
- Seller actions/events are any event not made by the initial `buyer_entity_id` and may for the purposes of conversion, include only: offer, accept, and decline
- Warning: this data represents real world data and may have some inconsistencies.

## Your Task
Please dedicate no more than four hours to this challenge. Clone this repository and submit a link to your repository when you are done.

### Create Visualizations
1. Number of buyers (y) with an offer per month (x).
2. Number of claims with an offer (y) per month (x).

### Answer Questions
1. What percent of total negotiations have a seller action/event?
2. Does seller conversion change based on receiving an offer from more than one buyer (`buyer_entity_id`)?
