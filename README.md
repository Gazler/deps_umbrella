# DepsUmbrella

This application shows an issue with fetching environment specific dependencies in an umbrella app.

## Steps to reproduce

1. Run `mix deps.get` from the root - nothing happens
2. cd `apps/foo`
3. Run `mix deps.get` - the dependency is fetched
