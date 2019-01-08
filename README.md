# spring configuration server demo

Example Spring Cloud Configuration Server Application.  This spring cloud configuration server connects github using ssh private key.  Ssh private key is generated using PuTTy Key Generator on windows. 

Below steps followed

1) Create ssh public & private keys using PuTTy Key Generator.  [demo](https://www.ssh.com/ssh/putty/windows/puttygen)
2) Export public key 
3) Add public key to your gitHub account using setting --> ssh keys [GitHub setup ssh Keys](https://github.com/settings/keys)
4) Add private key to server's application.yml --> privateKey property
5) Server also creates local directory D:\config_data to clone demo configuration repo.  You can change the path in application.yml --> basedir.

Configuration servers search properties using searchPaths properties. This enables client to load properties using application name & enviroment name ( using profile)

[Demo Application Configuration](https://github.com/himorithm/demo-configuration-repo)

[Demo Application client](https://github.com/himorithm/spring-configuration-client-demo)


