# my-k8s-world

Welcome to **my-k8s-world**! 🚀

This repository is dedicated to exploring and demonstrating practical Kubernetes concepts, deployments, and workflows. Whether you're a beginner aiming to learn the fundamentals, or an experienced engineer looking to extend your Kubernetes expertise, you’ll find useful resources, manifests, and scripts here.

---

## Features

- **Sample Deployments:** Custom YAML files to quickly deploy sample applications
- **Best Practices:** Examples of production-grade configurations, including resource limits, network policies, health checks, and more
- **Automation:** Scripts for automating common Kubernetes tasks
- **Learning Resources:** Useful links, documentation, and notes on Kubernetes core concepts

---

## Getting Started

### Prerequisites

- A working Kubernetes cluster (e.g., Minikube, kind, EKS, AKS, GKE, or any other)
- **kubectl** installed and configured
- Optionally: Docker for building and pushing container images

### Clone the Repository

```bash
git clone https://github.com/AnirbanB13/my-k8s-world.git
cd my-k8s-world
```

### Apply Sample Manifests

Browse the relevant directories for manifest files. For example, to deploy a sample app:

```bash
kubectl apply -f path/to/sample-deployment.yaml
```

Remember to update namespaces and image URLs to fit your environment when necessary.

---

## Directory Structure

```
.
├── deployments/           # Application deployment manifests
├── services/              # Service and ingress files
├── scripts/               # Useful automation scripts
├── docs/                  # Documentation and notes
└── README.md
```

---

## Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a new branch for your feature or bugfix
3. Submit a pull request with clear descriptions and documentation

---

## License

This repository is licensed under the MIT License. See [`LICENSE`](LICENSE) for details.

---

## Resources

- [Kubernetes Official Documentation](https://kubernetes.io/docs/)
- [kubectl Reference](https://kubernetes.io/docs/reference/kubectl/)
- [Kubernetes Best Practices](https://learnk8s.io/best-practices-kubernetes)

---

Happy Containerizing! 🐳

