# em-search-function

Firebase cloud functions that manages search indexes for [em!](https://github.com/cybersemics/em) project. [Algolia!](https://www.algolia.com) is used for search functionality.

## Functions

- `getSearchKey`: Given firebase `user.uid` returns secured search api key for using search api in the frontend. This api key returns results specific to that user.

- `addIndexOnCreateThoughtIndex`: Adds index for newly created `Lexeme`

- `deleteIndexOnThoughtIndexDelete`: Removes index of the the deleted `Lexeme`
