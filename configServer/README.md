<h1>Config Server</h1>

Config server is responsible to give configuration files to the calling service. 
It expect 2 parameters  profile name and application name. 
These 2 proeprties shouold be set in the bootstrap.properties of calling component 
spring.application.name=service
spring.profiles.active=dev

but one has to set the location of config server also in property file.
spring.cloud.config.uri=http://localhost:8888
