# ACM Multi Tenancy dev team repo
See management repo [acm-multi-tenancy](https://github.com/tosin2013/acm-multi-tenancy).

## Enviornments

### Dev
```
oc create -f dev/metrics-app/subscription.yml
oc create -f dev/cloudprober/subscription.yml
```

### Staging
```
oc create -f staging/metrics-app/subscription.yml
oc create -f staging/cloudprober/subscription.yml
```

### Prod
```
oc create -f prod/metrics-app/subscription.yml
oc create -f prod/cloudprober/subscription.yml
```