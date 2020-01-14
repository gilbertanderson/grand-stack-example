example graphql query

query {
  __schema {
    types {
      name
      kind
      description
      fields {
        name
      }
    }
  }
}