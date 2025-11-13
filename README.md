# 📘 Kubernetes CKA Practice Labs Tracker

A comprehensive list of 50+ hands-on labs and troubleshooting scenarios to help prepare for the **Certified Kubernetes Administrator (CKA)** exam.

---

## 📅 Start Date
`November 14, 2025`

## 📊 Progress Tracker

## ✅ CKA Progress Tracker (50 Labs)

- [ ] 1. Create a Cluster with Kind (1 Control Plane + 4 Workers)  
- [ ] 2. Verify Nodes and Cluster Info  
- [ ] 3. Create and Delete a Namespace  
- [ ] 4. Deploy a Pod and Verify its Status  
- [ ] 5. Create a Deployment with 3 Replicas  
- [ ] 6. Update a Deployment (Rolling Update)  
- [ ] 7. Rollback a Deployment  
- [ ] 8. Expose Deployment using ClusterIP  
- [ ] 9. Expose Deployment using NodePort  
- [ ] 10. Expose Deployment using LoadBalancer (Simulated via MetalLB or Ingress)  
- [ ] 11. Create a ConfigMap and Use it in a Pod  
- [ ] 12. Create a Secret and Mount it in a Pod  
- [ ] 13. Use Liveness and Readiness Probes  
- [ ] 14. Create PersistentVolume and PersistentVolumeClaim  
- [ ] 15. Use PVC in a Pod (Volume Mount)  
- [ ] 16. Deploy StatefulSet with PVC  
- [ ] 17. Setup and Use DaemonSet  
- [ ] 18. Schedule Pods using NodeSelector  
- [ ] 19. Schedule Pods using Affinity & Anti-Affinity  
- [ ] 20. Use Taints and Tolerations  
- [ ] 21. Limit CPU and Memory using Resource Requests/Limits  
- [ ] 22. Use LimitRange and ResourceQuota  
- [ ] 23. Manage RBAC: Roles, RoleBindings, ServiceAccounts  
- [ ] 24. Create a Job and Monitor Completion  
- [ ] 25. Create a CronJob  
- [ ] 26. Backup and Restore etcd  
- [ ] 27. Configure NetworkPolicy to Restrict Traffic  
- [ ] 28. Install Metrics Server and View Pod Metrics  
- [ ] 29. Horizontal Pod Autoscaler (HPA) Demo  
- [ ] 30. Cluster Upgrade with kubeadm (Simulated)  
- [ ] 31. Certificate Management in Kubernetes  
- [ ] 32. Static Pod Creation and Management  
- [ ] 33. Pod Lifecycle: Init Containers and Lifecycle Hooks  
- [ ] 34. Configure Ingress Controller (e.g., NGINX)  
- [ ] 35. Create an Ingress Resource for Web Apps  
- [ ] 36. Troubleshoot CrashLoopBackOff Pod  
- [ ] 37. Debug ImagePullBackOff Issue  
- [ ] 38. Diagnose Failed Scheduling (Insufficient Resources)  
- [ ] 39. Inspect Node NotReady State  
- [ ] 40. Test kube-proxy and CoreDNS  
- [ ] 41. Check Logs and Exec into Containers  
- [ ] 42. Use Ephemeral Containers for Debugging  
- [ ] 43. Restart kubelet and Validate Node Recovery  
- [ ] 44. Simulate Control Plane Failure (Stop kind-control-plane)  
- [ ] 45. Simulate Worker Node Failure and Recover  
- [ ] 46. Investigate Service Connectivity Issues  
- [ ] 47. NetworkPolicy Misconfig Troubleshooting  
- [ ] 48. Pod Disruption Budget (PDB) Use Case  
- [ ] 49. Quota Conflict Resolution  
- [ ] 50. Cleanup: Delete Cluster and Volumes  


## ✅ How to Use

- Check each box `[x]` as you complete a lab.
- Feel free to fork this repo and personalize it.
- Use `kubectl cluster-info dump`, `kubectl logs`, `describe`, and `exec` for troubleshooting practice.

---

## 📂 Repository Structure (Optional)

```
cka-labs/
├── README.md
├── lab-01-create-cluster.md
├── lab-02-namespaces.md
├── lab-03-deployment.md
├── ...
└── assets/
    └── diagrams, YAMLs, etc.
```

---

## 🤝 Connect With Me

Feel free to follow my learning journey on [LinkedIn](https://linkedin.com) or [GitHub](https://github.com).

---

## 📌 License

This repo is free to use and modify under [MIT License](LICENSE).

Happy Learning and Good Luck with your CKA! 🚀
