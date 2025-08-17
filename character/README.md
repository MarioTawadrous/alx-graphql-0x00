# Character Queries

This directory contains GraphQL queries and their outputs for fetching characters.

## Files for Specific Character by ID
- `character-id-*.graphql`: Queries to fetch a character by ID (1,2,3,4)
- `character-id-*-output.json`: Expected outputs for character-by-ID queries

## Files for List of Characters (Paginated)
- `characters-page-*.graphql`: Queries to fetch a page of characters (pages 1,2,3,4)
- `characters-page-*-output.json`: Expected outputs for character page queries

Note: Each page query returns 20 characters. The output examples show 3 characters per page for brevity.
