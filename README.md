### curl http://192.168.49.2:31158/ -H "host: e.es.asians.cloud" -v
```bash
*   Trying 192.168.49.2:31158...
* Connected to 192.168.49.2 (192.168.49.2) port 31158
> GET / HTTP/1.1
> Host: e.es.asians.cloud
> User-Agent: curl/8.5.0
> Accept: */*
> 
< HTTP/1.1 200 OK
< X-elastic-product: Elasticsearch
< Warning: 299 Elasticsearch-7.16.3-4e6e4eab2297e949ec994e688dad46290d018022 "Elasticsearch built-in security features are not enabled. Without authentication, your cluster could be accessible to anyone. See https://www.elastic.co/guide/en/elasticsearch/reference/7.16/security-minimal-setup.html to enable security."
< content-type: application/json; charset=UTF-8
< content-length: 540
< 
{
  "name" : "es-cluster-0",
  "cluster_name" : "k8s-logs",
  "cluster_uuid" : "1fIec6amRCafSkP0tgeZCw",
  "version" : {
    "number" : "7.16.3",
    "build_flavor" : "default",
    "build_type" : "docker",
    "build_hash" : "4e6e4eab2297e949ec994e688dad46290d018022",
    "build_date" : "2022-01-06T23:43:02.825887787Z",
    "build_snapshot" : false,
    "lucene_version" : "8.10.1",
    "minimum_wire_compatibility_version" : "6.8.0",
    "minimum_index_compatibility_version" : "6.0.0-beta1"
  },
  "tagline" : "You Know, for Search"
}
* Connection #0 to host 192.168.49.2 left intact
```
