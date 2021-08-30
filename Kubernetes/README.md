# POC - OKE

Parte de OKE da POC contendo os códigos Java e dotNet com istio implementado.

Antes de aplicar os deployments é necessário criar o namespace poc:

    kubectl create namespace poc

E habilitar o istio Injection no namespace

     kubectl label namespace poc istio-injection=enabled --overwrite
