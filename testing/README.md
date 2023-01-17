
# Testing

## Pre-requisites
Install base testing environment as described in https://github.com/atlasH2020/testing.

## Setup
Download the [sensor_data.postman_collection.json](./sensor_data.postman_collection.json) collection and import it in postman.

## Usage
Configure the `sensor_data_url` variable in the atlas-h2020-variables environment. You may obtain this URL by executing the registry API `get service api` request after manually setting the `service_name` registry collection variable to an existing ATLAS service, or by manually entering the URL to a service you are developing, if it is not yet registered.

You will also need to obtain a refresh token which you must save in the `sensor_data_token` environment variable (see https://github.com/atlasH2020/testing#obtaining-a-service-token).

You can now experiment with the sensor_data requests.
