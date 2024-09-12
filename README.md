[![Community Extension](https://img.shields.io/badge/Community%20Extension-An%20open%20source%20community%20maintained%20project-FF4700)](https://github.com/camunda-community-hub/community)
![Compatible with: Camunda Platform 8](https://img.shields.io/badge/Compatible%20with-Camunda%20Platform%208-0072Ce)
[![](https://img.shields.io/badge/Lifecycle-Incubating-blue)](https://github.com/Camunda-Community-Hub/community/blob/main/extension-lifecycle.md#incubating-)

# Unqork REST Outbound Connector

Camunda Outbound Connectors that call the [Unqork Customer API](https://developers.unqork.io/)

Based on the [Camunda REST Protocol](https://docs.camunda.io/docs/components/connectors/protocol/rest/)

# Unqork Webhook Start Event Connector

Connector to start process instances from Unqork Modules. This connector is based on inbound webhooks.

We've provided a sampe BPMN Process Diagram named [Unqork Connector Demo.bpmn](models/Unqork%20Connector%20Demo.bpmn) to get started. To run the sample, you'll first need to publish both of the following [element templates](https://docs.camunda.io/docs/components/modeler/desktop-modeler/element-templates/about-templates/):  

1. [Unqork REST Oubound Connector.json](element-templates/Unqork%20REST%20Outbound%20Connector.json)
2. [Unqork Webhook Start Event Connector.json](element-templates/Unqork%20Webhook%20Start%20Event%20Connector.json)

[Launch Web Modeler](https://docs.camunda.io/docs/components/modeler/web-modeler/launch-web-modeler/) and Create new Project. Then [import](https://docs.camunda.io/docs/components/modeler/web-modeler/import-diagram/) each of the element template json files. 

Open each of the element templates, and click `Publish`. Choose whether to publish the element templates to your project, or to the entire organization. 

Now import the [Unqork Connector Demo.bpmn](models/Unqork%20Connector%20Demo.bpmn). 


