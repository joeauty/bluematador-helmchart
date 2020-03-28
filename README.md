# Install

```
helm install bluematador --namespace [namespace] \
	--set "key=[BlueMatador Key]" \
	--set "accountID=[BlueMatador Account ID]" \
	--set "cluster=[k8s cluster name]" \
	./bluematador-helmchart
```