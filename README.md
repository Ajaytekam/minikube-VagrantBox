# Ubuntu minikube, kubectl Setup  

Sets up the ubuntu VM with minikube, kubectl and docker  

* minikube : minikube is local Kubernetes, focusing on making it easy to learn and develop for Kubernetes.      
* kubectl : The Kubernetes command-line tool, kubectl, allows you to run commands against Kubernetes clusters.   
* docker : software platform that allows you to build, test, and deploy applications quickly.   


__How to use :__   

* Install virtualbox and vagrant
* Run `vagrant up` command in the working directory and make sure the [vagrantfile](Vagrantfile) is there.  

> Note: The vagrantfile allocates 6GB ram and 4 cores to vm, so make sure that your system will acomodate that.   

__Example :__  

* After provision run `vagrant ssh` command
* To start minikube run command `minikube start` and if it doesn't  detect docker then run `minikube start --driver=docker`

