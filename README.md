# artemis
Artemis chart from youtube.com video

Environment is an AWS EC2 t3.medium with minikube and helm installed

Currently it doesn't run. 

[Youtube Video Artemis](https://video.search.yahoo.com/yhs/search?fr=yhs-iba-1&hsimp=yhs-1&hspart=iba&p=helm+chart+tutorial+for+beginners#id=1&vid=3ec9d5ad0b7c857727d7cdafc62080d7&action=click)

```
helm install artemis .
```

Results in
```
Error: unable to build kubernetes objects from release manifest: error validating "": error validating data: ValidationError(Ingress.spec.rules[0].http): missing required field "paths" in io.k8s.api.networking.v1beta1.HTTPIngressRuleValue
```
