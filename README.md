### Provisioning software defined storage infrastructure at cloud scale with Cisco Intersight Terraform provider

#### Examples to show how to use the Cisco Intersight Terraform provider to automate zero touch infrastructure deployment required for a generic Cloud-Scale software defined storage on Cisco Unified Computing System(Cisco UCS). 

The deployment of the whole solution consists of several main steps:
1.	Create an account in Intersight and claim all storage nodes
2.	Create Terraform configuration environment for Intersight.
3.	Apply Terraform configurations for 
      	Firmware Update on all storage nodes
      	Create server policies 
      	Create server profiles
      	Deploy server profiles for all nodes
      	Install Operating System on nodes
4.	Deploy software defined storage software

