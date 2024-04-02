[![Community Extension](https://img.shields.io/badge/Community%20Extension-An%20open%20source%20community%20maintained%20project-FF4700)](https://github.com/camunda-community-hub/community)
![Compatible with: Camunda Platform 8](https://img.shields.io/badge/Compatible%20with-Camunda%20Platform%208-0072Ce)
[![](https://img.shields.io/badge/Lifecycle-Incubating-blue)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#incubating-)

# Unqork Outbound Camunda Connector

Camunda Outbound Connector to call the [Unqork Customer API](https://developers.unqork.io/)

Based on the [Camunda REST Protocol](https://docs.camunda.io/docs/components/connectors/protocol/rest/)

## Element Template Generator

The [Element Template Generator](https://github.com/camunda/connectors/tree/main/element-template-generator) was used to generate json which was used as a starting point. To use the Element Template Generator, clone the [https://github.com/camunda/connectors](https://github.com/camunda/connectors) project and then run the following commands: 

```shell
mvn clean install

./element-template-generator/congen-cli/target/appassembler/bin/congen -e ServiceTask -e IntermediateThrowEvent generate openapi-outbound https://developers.unqork.io/api/1.0/openapi.yml
```

# Unqork Inbound Camunda Connector

Connector to start process instances from Unqork Modules. This connector is based on inbound webhooks.

