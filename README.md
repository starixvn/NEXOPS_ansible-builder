```
pip3 install ansible-builder
ansible-builder build -t my-ee-image --container-runtime docker
docker tag  my-ee-image:latest hub.nexdev.net/base/ansible-runner:2.16.14-iis
docker push hub.nexdev.net/base/ansible-runner:2.16.14-iis
```