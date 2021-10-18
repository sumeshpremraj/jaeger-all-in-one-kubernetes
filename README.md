# Jaeger all-in-one Kubernetes manifest

This is a fork of the now deprecated https://github.com/jaegertracing/jaeger-kubernetes/blob/master/all-in-one/jaeger-all-in-one-template.yml with fixes for the latest Kubernetes API.
I wanted something to test my app's traces locally, and the full Jaeger install (with the operator or Helm chart) does not work on low resource environments like a laptop.

Install it with the following command:
```sh
$ kubectl apply -f https://raw.githubusercontent.com/sumeshpremraj/jaeger-all-in-one-kubernetes/main/jaeger-all-in-one.yml
```

## Contributing
If you find any problems using this, create an issue.

If you have any improvements or fixes to contribute, fork this repo, make your changes in a branch and open a PR to this repo.