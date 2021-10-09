# Checking your environment

The first thing you want to do is see if you have a configuration file defined. See if there is an envioronment variable defined with a value for **KUBECONFIG**.  If the echo command returns nothing then we know this variable is not defined.  

```shell
echo $KUBECONFIG
```

Next we can make sure we have .kube folder in our home directory and then copy the admin.conf into that folder from /etc/kubernetes


```shell
ls -la /etc/kubernetes/admin.conf
cp /etc/kubernetes/admin.conf ~/.kube/config
kubectl get nodes
```

Next lets see what over details we can find in our configuration file.

