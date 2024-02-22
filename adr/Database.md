
# Database

## Status
Accepted


## Context
We want to be able to store searches done in a session by our users. These searches will not be uploaded

## Decision
We will be using a local database.

## Consequences
In choosing a local database, we can store past searches or calculations from the user. Since we will be using a local database, it will not be possible for other users to access this data.