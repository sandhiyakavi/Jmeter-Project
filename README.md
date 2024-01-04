# Jmeter-Project
This project has used the Config elements User Defined Variables and HTTP Request Defaults to avoid test data duplication and make test data more easily maintainable.
Data Parameterization using CSV Data Set Config element.
Used constant timer to add fixed delays before execution of samplers.
Used listeners to display the results.
Used assertions to check the response.


Can run the code in command line using: jmeter -n -t { .jmx file location} -l {Results folder location} -e -o {Reports folder location}
