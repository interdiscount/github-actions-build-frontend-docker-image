# Build Docker image from frontend
Builds a Docker image of the frontend repository.

## Inputs

### `image-name`

**Required** Name of the docker image.

### `interdiscount-coop-user-pw`

**Required** Coop user password to access private GitHub npm registry

## Example usage

```
uses: interdiscount/github-actions-build-frontend-docker-image@v1
with:
    image-name: microspot-frontend
    interdiscount-coop-user-pw: ${{ secrets.INTERDISCOUNT_COOP_USER_PW }}
```
