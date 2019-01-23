# Apache Storm (Experimental)


### Info:

 This template creates, scale in and scale out a multinodes broker (storm) cluster on top of Rancher. The configuration is generated with confd from Rancher metadata. 
 Cluster size are variable after deployment, and get reconfigured if refresh interval > 0.
 
 
### Usage:

 Select Apache Storm from catalog. 
 
 Enter the number of nodes, mem, refresh interval broker cluster and zookeeper service to connect. (set refresh data to 0 to disable dinamic config)

 Note: When you scale the cluster, zero downtime is not guaranteed..yet..
 
 Click deploy.
 
 Storm can now be accessed over the Rancher network. 

