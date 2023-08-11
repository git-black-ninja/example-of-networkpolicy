## example-of-networkpolicy

![image](https://github.com/git-black-ninja/example-of-networkpolicy/assets/141961610/c87c80de-da7e-4023-a3b9-3b122f5d53c7)


A NetworkPolicy is a Kubernetes object that allows you to control the traffic flow between pods and namespaces in your cluster. It is a powerful tool that can be used to implement security policies, isolate applications, and control how pods communicate with each other.

In that example, I created three pods with different labels. I created a NetworkPolicy that allows pods with the labels app=bookstore and app=api to only communicate with pods with the label app=dev.

only use that command to deploy all things


```bash
  $ kubectl apply -f .
```
