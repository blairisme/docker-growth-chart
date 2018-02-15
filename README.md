# Docker Environment for SMART Pediatric Growth Chart

Docker environment for [SMART Pediatric Growth Chart](https://github.com/smart-on-fhir/growth-chart-app), an open source application for displaying patient growth data.

## Setup

1. Install the latest version of [Docker](https://www.docker.com). Docker Compose version 2 is required.
2. Clone the repository.
3. Open a terminal in the directory where you cloned the repo.
4. Run `docker-compose up`.
5. Find the ip of your Docker environment:
  * If you are using Docker toolbox this tends to be `192.168.99.100`.
  * If you are using a native Docker installation it will be `localhost`.
6. You can now launch the growth chart application using the following URL, given the URL of a running FHIR instance and the id of a patient. `{docker-ip}:9000/launch.html?fhirServiceUrl={fhir-service-url}&patientId={patient}`.

## Notes

* The SMART Pediatric Growth Chart is still in active development. If you encounter any issues please use the [SMART Pediatric Growth Chart issue tracker](https://github.com/smart-on-fhir/growth-chart-app/issues).

## License

* The SMART Growth Chart is licensed under the Apache License v2.0. A copy of the license can be found in the [SMART Pediatric Growth Chart subfolder](https://github.com/smart-on-fhir/growth-chart-app/blob/master/license.txt).
* All other code is licensed under the MIT License.
