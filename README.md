# pod-racer

A containerized, single-node [OKD cluster](https://github.com/openshift/origin/).

oc cluster up --public-hostname='rat-10.ratchet.cc' --base-dir='/opt/conf' --routing-suffix='apps' --enable=* --write-config=true



automation-service-broker, centos-imagestreams, persistent-volumes, registry, rhel-imagestreams, router, sample-templates, service-catalog, template-service-broker, web-console


Disabled-by-default components: 

automation-service-broker, rhel-imagestreams, service-catalog, template-service-broker


oc cluster up --base-dir='./conf' --routing-suffix='apps' --enable=* --write-config=true