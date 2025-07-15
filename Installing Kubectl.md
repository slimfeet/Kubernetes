## Installing Kubectl  
1. Pull kubectl file from k8s official website. This step is for installing kubectl on Linux.   
```curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"  ```
2. Install Kubectl   
```sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl  ```
3. Check to confirm if kubectl has been installed  
```kubectl version --client  ```
