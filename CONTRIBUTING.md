# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-ausf_1.4.0_amd64.rock docker-daemon:sdcore-ausf:1.4.0
docker run sdcore-ausf:1.4.0
```