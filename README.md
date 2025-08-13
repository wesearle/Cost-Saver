# Cost-Saver
Cost Savings Calculated from Odigos Deployments

Deploy the cost-saver-full.yaml into your kubernetes cluster

Configure an OTLP HTTP destination in Odigos and use this for an address: 
http://ebpf-cost-saver.ebpf-cost-saver.svc.cluster.local:80

Use the port-forward command below to viw the cost saver UI: 
kubectl -n ebpf-cost-saver port-forward svc/ebpf-cost-saver 8080:80
