# K3d volume mount example
```bash
# If you have multiple server mean master and want to apply volume to all then use server:* and if there are separate agent then add agent along with server like `server:0;agent:*` which refers volume mount for server-0 and all agent. Agent is worker
k3d cluster create  --volume '/tmp/k3dvol:/tmp/k3dvol@server:0'

# example https://blog.ruanbekker.com/blog/2020/02/21/persistent-volumes-with-k3d-kubernetes/

kubectl create k3d-volume-mounted-app.yaml
```
# [K3d - How to run Kubernetes cluster locally using Rancher k3s](https://youtu.be/mCesuGk-Fks)

```bash
k3d cluster create --config k3d.yaml
```
