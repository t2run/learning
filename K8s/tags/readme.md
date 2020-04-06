Following tasks should be tried in a working K8s cluster.

Add label to a node
Remove label from a node
Add label to a pod
Remove label to a pod
Add label to a deployment
Remove label from a deployment
Use nodeSelector to schedule a pod on a particular node
Use nodeName to schedule a pod on a particular node
Use taints to prevent pods from being scheduled on a particular node
Use tolerations to ignore taints
Use nodeAffinity to schedule a pod on a particular node
Use podAntiAffinity to make sure that pods in the same deployments are not scheduled on the same node
Use podAffinity to make sure that pods from separate deployments are scheduled on the same node

Expected Outcome:- Show the list of resources(yamls) created for each scenario and how it works in the cluster in a working demo.
