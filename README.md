# Kubernetes KubeSpy

[KubeSpy](https://github.com/pulumi/kubespy) is small tool to see the changes in Kubernetes Resources dynamically.

## Installation

Installation is straight forward step.

Get the [KubeSpy binary](https://github.com/pulumi/kubespy/releases) and start using it.

## Issues

Please go through the [KubeSpy Issues](https://github.com/pulumi/kubespy/issues) as you might not get the same output as you want.

Many Issues will be resolved soon, for example to get pod details with small letter *p* and not capital *P*.

`kubespy status v1 Pod nginx-deployment-69d5f5d494-hzp7d`

## Commands

```
[slamba ◯  WHM0005395  ~ ] ☘   kubespy status extensions/v1beta1 Deployment nginx-deployment
[slamba ◯  WHM0005395  ~ ] ☘   kubespy status v1 Pod nginx-deployment-5fccc6f8d5-mtf9m   
[slamba ◯  WHM0005395  ~ ] ☘   kubespy trace svc nginx-terraform-pod
[slamba ◯  WHM0005395  ~ ] ☘   
```

## Demo

<p align="center">
  <a href="https://asciinema.org/a/X1gb1JS4zPtCmmmkQtDjp4axo?speed=2&amp;autoplay=1">
  <img src="https://asciinema.org/a/X1gb1JS4zPtCmmmkQtDjp4axo.png" width="585"></image>
  </a>
</p>
