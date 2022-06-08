# kube-news

observação quando eu fiz o portforward
no windows deu um erro que eu não tinha acesso
a porta 5432, ai eu simplesmente deixei
o k8s escolher uma porta aleatória

````
$ kubectl port-forward service/postgre :5432
```
