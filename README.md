# Demo Spring Cloud Configuration Server 

This demo spring cloud configuration server connects github using ssh protocol.  

SSH private key is generated using PuTTy Key Generator on windows. 
Public key is added as deployment key on gitHub. 
Private key is used Configuration Server to connect Demo Github configuration repo. 

Configuration servers resolve configuration files using searchPaths spring variable. 
This enables client to load properties using application name & profile (can be used as environment Name)

**Below Are Related Projects:** 

[Demo Application Configuration](https://github.com/himorithm/demo-configuration-repo)

[Demo Application client](https://github.com/himorithm/spring-configuration-client-demo)



