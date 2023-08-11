![image](https://github.com/git-black-ninja/example-of-networkpolicy/assets/141961610/e17a0992-54a4-4fb5-90e4-9aa3e74dca27)


## example-of-networkpolicy
A NetworkPolicy is a Kubernetes object that allows you to control the traffic flow between pods and namespaces in your cluster. It is a powerful tool that can be used to implement security policies, isolate applications, and control how pods communicate with each other.

In that example, I created three pods with different labels. I created a NetworkPolicy that allows pods with the labels app=bookstore and app=api to only communicate with pods with the label app=dev.

only use that command to deploy all things


```bash
  $ kubectl apply -f .
```
