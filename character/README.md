# GraphQL Character Queries

This repository contains GraphQL queries to fetch character information from the Rick and Morty API.

## Files

For each character ID (1 through 4), there are two files:

- `character-id-X.graphql` - The GraphQL query
- `character-id-X-output.json` - Expected response

## How to Use

1. Run any query file against the GraphQL endpoint
2. Compare your results with the corresponding output file

## Queried Fields

All queries request:

- id
- name
- status
- species
- type
- gender
