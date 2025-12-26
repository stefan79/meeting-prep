# Meeting Prep

This is a project which traverses various data sources and creates a meeting cheat sheet with suggestions for topics to discuss or descriptions of demo agents to build.

## Backend (FalkorDB)

Start the backend:

```sh
docker-compose -f ./docker/docker-compose-falkordb.yml up
```

Stop the backend:

```sh
docker-compose -f ./docker/docker-compose-falkordb.yml down
```

Test the MCP server with the inspector:

```sh
npx @modelcontextprotocol/inspector
```
