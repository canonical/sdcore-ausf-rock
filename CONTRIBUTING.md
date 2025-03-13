# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-ausf_1.6.2_amd64.rock docker-daemon:sdcore-ausf:1.6.2
docker run sdcore-ausf:1.6.2
```
