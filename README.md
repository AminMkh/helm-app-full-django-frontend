~~~
helm package .
helm repo index .
# git commit / push

helm dep udpate; helm package .; helm repo index .; git add . ; git commit ; git push origin
~~~
