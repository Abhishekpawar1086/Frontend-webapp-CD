# Frontend-webapp-CD
This Repo for deploying Frontend-webapp To K8s Using Helm
# Script to install Kune and Helm On your Jenkins Server 
 # Install kubectl
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
chmod +x kubectl
sudo mv kubectl /usr/local/bin/

# Install Helm
curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash
