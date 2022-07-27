*I can't guarrantee that all the info I conclude are right. It's just my personal understanding. If there is any problem or confusion, please contact with me.*

## Introduction
Simply understand the k8s as a platform for the cloud service management.
Before we started, we have to know that there is a tech called docker. Docker evolved from the concept of virtualization. We can simply understand it as a light-weight VM. If we just wanna run a simple process, obviously we don't have to create a VM for it. This might remind you of JVM. But JVM said, 'Compile once, run anywhere.' while docker said, 'build once, run anywhere.'. Simply we can get a relation between this two techs like the docker includes the JVM, because the concept of build is larger than compilation. The virtualization of JVM is only at runtimes while the dockers is more like a independent OS to manage the resources for those applications.

When we create a VM, the system distribute the resources at infrastructural level. But when we create a docker application, it remains at process level. The docker is responsible for the manipulation the resource distribution between docker applications.

But the original methods to deploy and manage docker is complicated or even trivial. Especailly when you are managing a large amount of docker application. So this is what the k8s came for. It offers a platform to help us manage the docker application in a better way with less effort.
