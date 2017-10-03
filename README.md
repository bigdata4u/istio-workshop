## Setup for the workshop
[Setup Instructions](setup/instructions.md)

## Credits

These workshop exercises are built with the help from a number of amazing Kubernetes and Istio Experts from Google and Grand Cloud.

The Kubernetes Exercises are dervied from the work of Ray Tsang  [@saturnism](https://twitter.com/saturnism) and these repositories:

[https://github.com/saturnism/spring-boot-docker](https://github.com/saturnism/spring-boot-docker)

[https://github.com/saturnism/istio-by-example-java](https://github.com/saturnism/istio-by-example-java)

Zach Butcher [@ZachButcher](https://twitter.com/ZackButcher) was insturmental in helping write the Istio tutorials.

The Istio Ingress Tutorial is largely based on the work of Kelsey Hightower [@kelseyhightower](https://twitter.com/kelseyhightower) and this repository:

[https://github.com/kelseyhightower/istio-ingress-tutorial](https://github.com/kelseyhightower/istio-ingress-tutorial)

Kelsey's tutorial uses more advance features of Kubernetes to taint some of the nodes so that the ingress controller runs on dedicated nodes.  The ingress controller is then deployed as a daemonset.