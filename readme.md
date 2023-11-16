# blog
**blog** is a blockchain built using Cosmos SDK and Tendermint and created with [Ignite CLI](https://ignite.com/cli).

## Get started

```
ignite chain serve
```

`serve` command installs dependencies, builds, initializes, and starts your blockchain in development.

### Commands

***Creating a post***
```
blogd tx blog create-post hello world --from alice
```

***Listing posts***
```
blogd q blog show-post 0
```

***Updating a posts***
```
blogd tx blog update-post hello cosmos 0 --from alice
```

***Deleting a posts***
```
blogd tx blog delete-post 0 --from alice
```

