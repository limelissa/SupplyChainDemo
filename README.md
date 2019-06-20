Supply Chain IRIS Demo
==============
IRIS SupplyChain demonstration

## Prerequisites
Install **Docker**  

## Installation
At the root of the project, run :  
`./build.sh`

Then, to launch containers :  
`./run.sh`

To restart containers :  
`docker-compose start`

To stop containers :  
`docker-compose stop`

To remove permanently containers :  
`docker-compose stop`  
`docker-compose rm`

## Access the Management Portal
On a web browser :  

Management portal at : http://localhost:9204/csp/sys/UtilHome.csp  
Workflow UI at : http://localhost:9204/csp/workflow/index.html

Rest at : http://localhost:9204/api/v1/calcul/prevision
Python dashboard at : http://localhost:8050/demo/historical

Spark :
Spark master : http://0.0.0.0:8090/
Zepplin : http://0.0.0.0:9097/#/notebook/2E5USDMXY
