# FHIR R5 Invariant test cases

## How to register test cases

1. Create an instance in either xml or json format
2. fill it with the content that either passes or fails according to the invariant (doesn't matter whether the rest of the resource is valid or not)
3. Whether the example demonstrates that the invariant is correct or not, we'd like it submitted here
4. Submit it here by maing a PR that puts the instance in the right folder for it's resource type, with the name ```[key].pass|fail][desc].[xml|json]```. where key identifies the invariant e.g. pat-1.pass.grahame1.json checks pat-1 and passes it, and it's in json format. The description does't really matter, it just makes the filenames unique, but your name and a number will do that
5. in the PR comments, put the output from the FHIR validator or the invariant tester you're using 
6. Thanks for submitting the PR

