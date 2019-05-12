### install fluentd

```
source <(kubectl completion bash)
echo "source <(kubectl completion bash)"
alias k=kubectl
complete -F __start_kubectl k
k apply -f fluent.yaml
k logs -f -n kube-system fluentd<tab>
```
