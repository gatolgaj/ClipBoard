# ClipBoard
Clipboard to Sync Clipboard

For Sigma1 

    sudo docker run -d --privileged --restart=unless-stopped --net=host -v /etc/kubernetes:/etc/kubernetes -v /var/run:/var/run rancher/rancher-agent:v2.4.5 --server https://13.234.102.114 --token knhbcgbgf67wvkvd9cs5694jxjl58flxfl5cl7vv5n8l7qkps4jwwf --ca-checksum 2e5bfa81ecff95ab73b527836cd1fa7a8f0b240cf0837a2fa9f447bbc523387a --etcd --controlplane --worker1
