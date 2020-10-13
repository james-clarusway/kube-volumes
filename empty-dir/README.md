### RESTART A POD

```bash
kubectl exec -it <pod-name> -- bash
root@<pod-name>:/# apt-get update
root@<pod-name>:/# apt-get install procps
root@<pod-name>:/# ps aux
root@<pod-name>:/# kill <pid> # or kill 1 
```