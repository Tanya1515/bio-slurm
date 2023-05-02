# bio-slurm

Collection of configuration files for Slurm-cluster with NFS. 

### Configuration files

- Slurm: 

  - slurm.conf - main configuration file for all Slurm daemons. Describes basic settings of Slurm-cluster, such as: resource selection type, database  usage, schedulling type, characteristics and logic partitions of worker nodes and etc. Path to file: /etc/slurm-llnl/slurm.conf. More detailed    information is available -  https://slurm.schedmd.com/slurm.conf.html.

  - cgroup.conf - configuration file for setting up cgroup-plugin. It can be used for resources restriction on Slurm-cluster. Path to file: /etc/slurm-llnl/cgroup.conf More information about the additional module - https://slurm.schedmd.com/cgroups.html. 
  
 - NFS
    - exports - main configuration file for NFS-server. Path to file: /etc/exports. 
 
    - fstab - main configuration file for NFS-client. Path to file: /etc/fstab. 



