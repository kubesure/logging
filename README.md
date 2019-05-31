### start elasticsearch and kibana

```
set virtual memory for elastic
sudo sysctl -w vm.max_map_count=262144

```

### install fluentd as k8s object

```
source <(kubectl completion bash)
echo "source <(kubectl completion bash)"
alias k=kubectl
complete -F __start_kubectl k
k apply -f fluent.yaml
k logs -f -n kube-system fluentd<tab>
```
