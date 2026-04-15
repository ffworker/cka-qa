# Current Focus

## Weak
- Deployments
- Scheduler Profiles

## Improving
- Kubernetes Components
- Core Principles
- Pods
- Services
- NodePort
- ClusterIP
- Labels / Selectors
- Static Pods
- Admission Controllers
- Multiple Schedulers

## Stable
- ReplicaSets
- DaemonSets
- Resource Limits
- Priority Classes

## Unstable Concepts
- scheduler vs kubelet
- current replicas vs available replicas
- Service -> Endpoints -> Pod
- precise Pod definition under pressure
- multiple schedulers vs scheduler profiles

## Practical recommendations sent to lab
- trace Deployment -> ReplicaSet -> Pods
- debug a Service with no endpoints
- differentiate scheduler vs kubelet from symptom patterns
- compare ClusterIP vs NodePort with exact troubleshooting chain
- compare static Pods vs DaemonSets
- compare multiple schedulers vs scheduler profiles
- contrast admission controllers with normal controllers
