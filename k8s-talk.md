## k8s itself
 * [general structure](https://kubernetes.io/images/blog/2018-06-05-11-ways-not-to-get-hacked/kubernetes-control-plane.png)
   * https://kubernetes.io/docs/concepts/overview/components/
 * containers, pods, deployments, services, etc
 * API server, APIs
 * kubectl
 * compared to docker / swarm

## setting up a cluster
 * [the hard way](https://github.com/kelseyhightower/kubernetes-the-hard-way)
 * kubeadm, kubespray, kops, etc.
 * local (minikube, etc)
 * cloud / managed services
 * [the easy way](https://www.youtube.com/watch?v=kOa_llowQ1c)

## using k8s - mostly overview, in-depth left for a workshop - like thing
 * persistence - configMaps, secrets, PVs
 * deploying with kubectl
 * [yaml](https://github.com/gctools-outilsgc/Kubernetes-config)
 * [helm](https://github.com/helm/charts/tree/master/stable)
   * https://github.com/gctools-outilsgc/helm-charts
   * [random example](https://asciinema.org/a/163484) with a jenkins deployment
 * RBAC
 * hpa / vpa / autoscaling
 * automation
