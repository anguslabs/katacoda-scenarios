# Configuring your kubectl

The primary kubernetes configuration tool is **kubectl**.  This tool looks for a configuration file on start up. During the initial installation of Kubernetes the default Administrative configuraiton file is created and typically stored in /etc/kubernetes/admin.conf. The kubectl utility looks for a configuration file in one of 3 places.

1. use --kubeconfig flag, if specific
1. use KUBECONFIG environment variable, if specified
1. use $HOME/.kube/config file

Now let's go see if we can set this up in our new environment.
