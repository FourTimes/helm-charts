create the helm charts and their commands

    1. helm create charts

create the namespece
    
    1. kubectl create ns raw

install the packages with name of cuckoo

    1. helm install -f values.yaml cuckoo . -n raw

