



## Allow jenkins to run docker
> sudo groupadd docker
> sudo usermod -aG docker jenkins
> chmod 777 /var/run/docker.sock


## Jenkins server is configured to connect with Kubeernetes cluster using command line 'kubectl' binary.
Switch to jenkins user and copy Kube config file into .kube/config folder.

$ sudo -i -u jenkins
$ cp /home/ubuntu/.kube/config ~/.kube/config

