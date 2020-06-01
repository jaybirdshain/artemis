# artemis
Artemis chart from youtube.com video

Currently it doesn't run. 

```
helm install artemis .
```

Results in
```
Error: unable to build kubernetes objects from release manifest: error validating "": error validating data: ValidationError(Ingress.spec.rules[0].http): missing required field "paths" in io.k8s.api.networking.v1beta1.HTTPIngressRuleValue
```
