# -*- mode: Python -*-

docker_build('idiotoflinux/ldomadm2-image', '.')
k8s_yaml('kubernetes.yaml')
k8s_resource('ldomadm2', port_forwards=5000)
allow_k8s_contexts('default')