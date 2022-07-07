# simple-node-app
A simple node application to demonstrate dockerization &amp; deployment in kubernetes using helm

## Test - Hardcode the limit range & Resource Quota

kubectl apply -f resourceQuota.yaml --namespace=test-lr
kubectl apply -f limitRanges.yaml --namespace=test-lr

![image](https://user-images.githubusercontent.com/58381187/177785340-93ea5e1f-ed52-4fc0-82be-c1f712efd6ba.png)

## It works!

![image](https://user-images.githubusercontent.com/58381187/177785535-aa013d5d-7ada-4118-a52b-11d00a5316af.png)
