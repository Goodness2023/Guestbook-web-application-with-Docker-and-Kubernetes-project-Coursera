# Guestbook Application

A simple cloud-native Guestbook application containerized with Docker and deployed on Kubernetes.  
This project demonstrates building, pushing, and running images on **IBM Cloud Container Registry** and managing workloads with **OpenShift/Kubernetes**.

---

## 🚀 Features
- Containerized Guestbook app (`guestbook:v1`)
- Built with Docker and pushed to IBM Cloud Container Registry (`us.icr.io/sn-labs-patriciaajis`)
- Deployable on Kubernetes using `Deployment` and `Service` manifests
- Demonstrates port-forwarding and cluster troubleshooting

---

## 🛠️ Prerequisites
- [Docker](https://docs.docker.com/get-docker/)
- [IBM Cloud CLI](https://cloud.ibm.com/docs/cli)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- [oc CLI](https://docs.openshift.com/container-platform/latest/cli_reference/openshift_cli/getting-started-cli.html) (for OpenShift users)

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/guestbook.git
cd guestbook/v1/guestbook
