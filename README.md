### Deploy a high-availability web app using CloudFormation
Through this code we have succesfully deployed Infrastructure and Udagram application.


### The Files Included with this repo are:-
* /screenshots-project2--> It contains various screenshots capture end to end while creating and deleting stack.
* /Udagram App ---> Index.html file which is in S3 bucket
* create.sh : Cloudformation create stack script to execute in shell
* update.sh : Cloudformation update stack script to execute in shell
* create.bat : Cloudformation create stack script to execute in Powershell
* update.bat : Cloudformation update stack script to execute in Powershell
* udagraminfra-config.yml :- Contains code to deploy Udagram Infrastrucutre
* udagram-parameters.json :- Contains various parameters
* High Availability WebApp.jpeg :- Architecture

### Instruction to deploy

./create.bat MohitUdagramDemo udagraminfra-config.yml udagram-parameters.json
