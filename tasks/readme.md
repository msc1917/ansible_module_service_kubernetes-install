# Basis-Ansible-Konfiguration fuer Baikonur-Netzwerk
Rollen-Definitionen zum Einrichten des Heimnetzwerkes

## Rolle "kube_01_kubernetes_install"
Einrichten des Kubernetes-Clusters (master und node) via k3s, rke, kubeadm oder minikube

## Verzeichnis "tasks"
Playbook-Tasks, welche in der Rolle durchgeführt werden

## Files:
* **cleanup/k3s-cleanup.yml:**
* **cleanup/kubeadm-cleanup.yml:**
* **cleanup/main.yml:**
* **cleanup/minikube-cleanup.yml:**
* **cleanup/rke-cleanup.yml:**
* **engine_k3s/k3s-create_user.yml:**
* **engine_k3s/k3s-download.yml:**
* **engine_k3s/k3s-master.yml:**
* **engine_k3s/k3s-node.yml:**
* **engine_k3s/main.yml:**
* **engine_kubeadm/kubeadm-create_user.yml:**
* **engine_kubeadm/kubeadm-master.yml:**
* **engine_kubeadm/kubeadm-node.yml:**
* **engine_kubeadm/kubeadm-user_setup.yml:**
* **engine_kubeadm/main.yml:**
* **engine_minikube/main.yml:**
* **engine_rke/main.yml:**
* **engine_rke/rke-create_config.yml:**
* **engine_rke/rke-create_user.yml:**
* **engine_rke/rke-download.yml:**
* **initial/download/download-helm.yml:**
* **initial/download/download-k3s.yml:**
* **initial/download/download-kubeadm.yml:**
* **initial/download/download-minikube.yml:**
* **initial/download/download-rke.yml:**
* **initial/initial-download.yml:**
* **initial/initial-host.yml:**
* **initial/initial-install_software.yml:**
* **initial/main.yml:**
* **main.yml:**
