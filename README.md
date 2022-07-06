# vpc-taurus-perf
Need to create a quick load test against the VPC API

### Setup
Start by installing the Taurus tool on your system following the [main documentation](https://gettaurus.org/docs/Installation/).

Once Taurus is installed, create a file named `apikey.csv` in the project home directory; this is a CSV file of API keys, so there should be at least one entry in the file.

### Runnint the test
To run the tests, just enter `bzt test-vpc.yaml`

The default region (`eu-de`) can be overridden via `bzt -o settings.env.RIAS_REGION=us-south test-vpc.yaml`
