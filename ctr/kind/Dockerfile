FROM kindest/node:v1.19.0

RUN curl -sL https://dl.k8s.io/v1.19.1-rc.0/bin/linux/amd64/kubectl > /usr/local/bin/kubectl; chmod +x /usr/local/bin/kubectl
RUN curl -sL https://dl.k8s.io/v1.19.1-rc.0/bin/linux/amd64/kubeadm > /usr/local/bin/kubeadm; chmod +x /usr/local/bin/kubeadm
RUN curl -sL https://dl.k8s.io/v1.19.1-rc.0/bin/linux/amd64/kubelet > /usr/local/bin/kubelet; chmod +x /usr/local/bin/kubelet