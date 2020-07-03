# swarm-infra
Stack that houses the base infrastructure of swarm hosts

## Manual Deployment

### Secrets
The environment variables can be filled in via the .env files. For a template, you can copy the `.example.env*` files and naming the copies by removing the `example` portion from the prefix and filling in the values.

### Deploy
```bash
docker stack deploy -c stack.yml swarm-infra
```
