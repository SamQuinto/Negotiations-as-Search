# Negotiations-as-Search

This repo contains three notebooks that build on each other:

1. **Step 1 – Scenario Generation**  
   Generates negotiation payoff matrices (random or manual).  
   Outputs go into `S1_OUTPUT/` and raw matrices into `S1_OUTPUT/random_raw/`.

2. **Step 2 – Agent-Based Simulations**  
   Runs negotiation simulations using the scenarios from Step 1.  
   Outputs (summaries + run files) go into `S2_OUTPUT/`.

3. **Step 3 – Analysis**  
   Analyzes simulation results from Step 2 and produces figures/tables.  
   Outputs go into `S3_OUTPUT/`.

## How to Run
- Open any notebook in Google Colab or locally.
- Run the first cell (“Project setup”) to create standard folders.
- Step 1 is optional if you already have scenarios – just place them into `S1_OUTPUT/` and `S1_OUTPUT/random_raw/`.
- Step 2 reads from Step 1 outputs.  
- Step 3 reads from Step 2 outputs.
