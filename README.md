# spring-configuration-server-demo

Example Spring Cloud Configuration Server Application.  This spring cloud configuration server connects github using ssh private key.  Ssh private key is generated using PuTTy Key Generator on windows. 

Below steps followed

1) Create ssh public & private keys using PuTTy Key Generator
2) Export public key 
3) Add public key to your gitHub account using setting --> ssh keys ( https://github.com/settings/keys)
3) Add private key to server's application.yml. privateKey property

Configuration servers search properties using searchPaths properties. This enables client to load properties using application name & enviroment name ( using profile)

Demo Application Configuration: https://github.com/himorithm/configuration
Demo Application client : 
