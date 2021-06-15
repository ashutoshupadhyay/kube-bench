# kube-bench

### Description

Periodic scan of EKS cluster via aquasec/kube-bench

### Anatomy
- [x] Hourly scheduled job with retention of 23 occurrences (i.e. 23 hours)
- [x] Daily scheduled job with retention of 7 occurrences (i.e. 7 days) 

### Implementaion steps
- Clone the repo or download the folder github.com/eks-charts/stable/kube-bench
- Execute the following command: `helm install kube-bench --debug`
- Monitored for the successful execution of hourly and daily pods

### Testing
- Implemented the helm chart
- Monitored for the successful execution
