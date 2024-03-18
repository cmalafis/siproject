run the following steps
 $ oc create -f image-registry-deployment.yaml openshift-image-registry
 $ oc create -f registry-svc.yaml -n openshift-image-registry