# GraphQL Character Queries

This repository contains GraphQL queries to retrieve information about characters using their IDs.

## Query Details

The following queries fetch character details for IDs 1, 2, 3, and 4, including the fields: `id`, `name`, `status`, `species`, `type`, and `gender`.

### Query for Character with ID 1
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}

This structure adds clarity and organizes the information under different sections for each character, including the query and its sample output.
