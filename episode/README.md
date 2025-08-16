# alx-graphql-0x00


# Character Query by ID

This module demonstrates how to query a specific character from a GraphQL API using their ID.

## Objective
Learners will write GraphQL queries to retrieve a specific character’s information by ID.

## Fields retrieved:
- `id`
- `name`
- `status`
- `species`
- `type`
- `gender`

## Example Usage
Each `.graphql` file contains the query for a character ID (1–4).
Each `.json` file contains the expected output from the GraphQL API.

Example (character with ID = 1):
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
