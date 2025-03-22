# Lab3Grafana by Andrew Brown

## Summary of steps
First I started by creating a VM on the Azure portal; Using the public IP I SSH into the VM and downloaded the needed Grafana server on the VM. Next we set up a inbound security rule allowing access to the server hosted on the VM. Next we turned on managed identity on the Azure portal followed by using the nano command changing the "managed_identity_enabled = true" where I ran into my only problem where I didn't notice the ; at the beginning which acted as a comment not making it work originally but figured out later. Then finally after a reset of the server it allowed me to authenticate with Azure using managed identity. Finally I made a quick dashboard showing both CPU and available memory.
