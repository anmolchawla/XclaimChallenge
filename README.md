# Analytics Engineer Challenge

## Things You Should Know

### negotiations.csv
- id
- buyer_id
- claims

### negotiation_events.csv
- id
- negotiation_id
- legal_entity_id
- action

### Notes
- You can *assume* the negotiation event with the highest ID is the most recent
- `buyer_entity_id` and `legal_entity_id` are from the same `legal_entities` table
- Seller actions/events are any event not made by the initial `buyer_entity_id` and may for the purposes of conversion, include only: offer, accept, and decline

## Your Task
Please dedicate no more than four hours to this challenge.

### Create Visualizations
1. Number of buyers (y) with an offer per month (x).
2. Number of claims with an offer (y) per month (x).

### Answer Questions
1. What percent of total negotiations have a seller action/event?
2. Does seller conversion change based on receiving an offer from more than one buyer (`buyer_entity_id`)?
