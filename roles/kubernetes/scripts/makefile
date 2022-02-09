install:
	echo "Downloading and install k3s"
	curl -sfL https://get.k3s.io | sh -s - --write-kubeconfig-mode 644

validate:
	echo "Get k3s version"
	k3s --version
    
get_token:
	echo "Get Node Token"
	cat /var/lib/rancher/k3s/server/node-token