- What is `etcd`? #card
  card-last-interval:: 4
  card-repeats:: 1
  card-ease-factor:: 2.6
  card-next-schedule:: 2025-12-05T18:14:59.333Z
  card-last-reviewed:: 2025-12-01T18:14:59.335Z
  card-last-score:: 5
  collapsed:: true
	- A distributed K/V store which maintains the cluster state
- What does the API server do? #card
  collapsed:: true
	- It is the primary management endpoint, accepts and processes all [[K8s API]] requests.
- What does the Kube-Scheduler do? #card
  collapsed:: true
	- It assigns workloads to worker nodes based on resource requirements.
- What does the Controller Manager do? #card
  collapsed:: true
	- It manages various controllers which in turn handle the routine cluster operations.
- What does the Cloud Control Manager do? #card
  collapsed:: true
	- It allows the [[K8s API]] server to interact with the cloud provider, enabling management and provisioning of cloud resources.
-
-