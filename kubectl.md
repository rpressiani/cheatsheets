# kubectl

## Upgrade kubectl[^1]
```
brew update
brew upgrade kubernetes-cli
brew link --overwrite kubernetes-cli
```

## kubectl context
**Set namespace context[^2]**
```
kubectl config set-context --current --namespace=ggckad-s2
```
[^1]: [How to upgrade kubectl client version](https://stackoverflow.com/questions/53701151/how-to-upgrade-kubectl-client-version)
[^2]: [kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
