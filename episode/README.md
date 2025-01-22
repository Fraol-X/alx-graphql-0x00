# GraphQL Episode Queries

This repository contains GraphQL queries to retrieve information about episodes using their IDs.

## Query Details

The following query fetches details of a specific episode using the `episode(id: ID!)` field, including the fields: `id`, `name`, `air_date`, and `episode`.

### Query for Episode with ID 1
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
