# ci-newman-postman-reporter
Simple Continuous Integration with Travis CI

### Description
Every time a Pull request or a push to master is done, Travis CI will automatically run the job. 
In this case with Newman (Postman CLI) will run the collection with their collection environment and the given data (in a .csv file).
Also it generates an html report.
