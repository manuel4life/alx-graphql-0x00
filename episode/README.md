# Episode GraphQL Queries

This directory contains GraphQL queries to fetch episode information from the Rick and Morty API.

## Files

For each episode page (1 through 4), there are two files:

- `episode-page-X.graphql` - The GraphQL query
- `episode-page-X-output.json` - Expected response

## Query Structure

All queries request these fields:

- `id`
- `name`
- `air_date`
- `episode`
