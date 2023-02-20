# puppet with hiera example
 
1. Install Puppet and Hiera on the master node:
   You can use your package manager to install Puppet and Hiera. For example, on a CentOS-based system, you can use the following command:
   sudo yum install puppet hiera
   
2. Configure Hiera:
   Create a hiera.yaml file in your Puppet configuration directory (/etc/puppetlabs/puppet for Puppet Enterprise, or /etc/puppet for open-source Puppet) and specify the    location of your Hiera data files. For example:
