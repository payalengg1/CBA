# CBA
Codility Task for CBA : API testing with Postman

**CBATest.postman_collection.json**
This is the postman collection 

Sequence of APIs tested:
1. AddPet

**TestEnv.postman_environment.json**
This is the Test environment variables

**CBATest.yml**
This is the github workflow (CI pipeline) which installs all the depencencies such as node.js, newman and so on. Further, executes the postman collection and generates the html report as well.
NOTE: it is configured for feature/Payal-CBATest git branch for now.
