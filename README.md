# k8s logging: Fluentd-ElasticSearch-Kibana

Important: for successful deployment you need to have
<b>'json-text'</b> as default log-driver for Docker on each
nodes. Most probably will work with some other drivers,
but not working with <b>'jurnald'</b>.

In this setup we using NodePort approach to access Kibana portal.
In your browser open Kubernetes master's IP on port 30560.

