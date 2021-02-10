# gql-compare
comparing various graphql libraries in go

## thunder
 thunder uses reflection to figure out the gql schema avoiding the need to write it out.
 however you need to create functions to fetch the data anyways so IMO this adds little benefit.
 it could be good if you have a very flat simple API, and the getters are simple, but defining schema is just a hassel. 

