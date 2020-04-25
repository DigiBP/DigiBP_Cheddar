# DigiBP - Team Cheddar - Documentation

## Introduction: Tenant Damage Report Process
In the following the current as-is process for the tenant damage report is described. In the existing process, the Property Owner, Tenant, Property Manager and Various Maintenance Service Partner are involved. The process starts as soon as the Property Manager receives the tenant damage report from the tenant. After receiving the tenant damage report, the Prop-erty Manager's first task is to record and categorize this request in the system. As soon as this is done, the Property Manager prepares a request for offer to various maintenance Service Partners. Once the Maintenance Service Partners have received the request for offer from the Property Manager and subsequently submitted an offer, the Property Manager processes the offers received and classifies them according to the amount.

In the following the current as-is process for the tenant damage report is described. In the existing process, the Property Owner, Tenant, Property Manager and Various Maintenance Service Partner are involved. The process starts as soon as the Property Manager receives the tenant damage report from the tenant. After receiving the tenant damage report, the Prop-erty Manager's first task is to record and categorize this request in the system. As soon as this is done, the Property Manager prepares a request for offer to various maintenance Service Partners. Once the Maintenance Service Partners have received the request for offer from the Property Manager and subsequently submitted an offer, the Property Manager processes the offers received and classifies them according to the amount.

If the amount of the offer is less than 5000 Swiss francs, the supervisor of the Property Man-ager has to approve the offer make the decision whether the amount of the offer is acceptable. As soon as the Property Manager's supervisor has approved the amount of the offer, the order is placed. The Property Manager is notified by the Maintenance Service Provider as soon as the order is finished. Then the Tenant is going to be notified by the Property Manager with a specified deadline to pay the invoice. The Maintenance Service Provider prepares an invoice and hands it over to the Property Manager. Having received the invoice from the Tenant, the Property Manager processes the invoice. The Tenant has two weeks the possibility to give a feedback to process. Once the invoice has been processed and the problem has been solved, the Property Manager authorizes the payment. However, if the invoice was processed by the Property Manager, but the problem could not be solved, an incident case is created and esca-lated to the next higher level.

If the amount is higher than or equal to 5000 Swiss francs, the Property Owner notifies the Property Owner and informs him about the current situation. After the Property Owner sends the Tenant's Feedback to the Property Owner, the Property Manager processes the decision of the Property Owner. Then the order is placed and the Maintenance Service Provider in-formed. Once the order is finished, the Maintenance Service Provider notifies the Property Manager about the status. Subsequently, the Tenant is going to be notified by the Property Manager with a specified deadline to pay the invoice. The Maintenance Service Provider pre-pares an invoice and hands it over to the Property Manager. Having received the invoice from the Tenant, the Property Manager processes the invoice. The Tenant has two weeks the pos-sibility to give a feedback to the process. Once the invoice has been processed and the prob-lem has been solved, the Property Manager authorizes the payment. However, if the invoice was processed by the Property Manager, but the problem could not be solved, an incident case is created and escalated to the next higher level.

### [3.4.0](https://github.com/DigiBP/digibp-camunda-template/tree/3.4.0)
- Updating Camunda to 7.12.0
- Updating Camunda Spring Boot to 3.4.0
- Updating Spring Boot to 2.2.1.RELEASE

### [3.3.0](https://github.com/DigiBP/digibp-camunda-template/tree/3.3.0)
- Updating Camunda to 7.11.0
- Updating Camunda Spring Boot to 3.3.4
- Updating Spring Boot to 2.1.6.RELEASE
- Removing Maven Wrapper
- Removing Camunda Modeler Templates

### 3.2.3
- Adding `spring-boot-starter-jdbc` dependency, otherwise `spring:datasource` is ignored.

### 3.2.2
- Use of Camunda deployment procedure (embedded:deployment) instead of Spring Boot (embedded:app)
- Change of resource folder structure due to the use deployment procedure  

### 3.2.1
- Rearrange the order of the REST and Web Apps dependencies

### 3.2.0
- Updating Camunda Spring Boot to 3.2.0
- Updating Spring Boot to 2.1.1.RELEASE

### 3.1.0
- Updating Camunda to 7.10.0
- Updating Camunda Spring Boot to 3.1.0

### 3.0.0
- Updating Camunda to 7.9.0
- Updating Camunda Spring Boot to 3.0.0
- Updating Spring Boot to 2.0.2.RELEASE

### 2.0.7
- Default Maven goal `clean spring-boot:run`
- Camunda Modeler Element Template (not in archetype)

### 2.0.6
- A much nicer `deploy to Heroku` shield.

### 2.0.5
- Adding 'authorization: enabled: false' to application.yaml

### 2.0.4
- Adding application-local.yaml to .gitignore
- Updating application.yaml and application-heroku.yaml

### 2.0.3
- Adding a README.md file

### 2.0.2
- Adding a .gitignore file

### 2.0.1
- Adding a .gitignore template file

### 2.0.0
- Updating Camunda Spring Boot to 2.3.0
- Updating Spring Boot to 1.5.8.RELEASE

### 1.0.6

- Updating Camunda Spring Boot to 2.1.0
- Updating Spring Boot to 1.5.3.RELEASE
- Adding to application.yaml: `camunda:bpm:authorization:enabled:true`

### 1.0.5

- Updating Camunda Enterprise Edition to 7.6.4
- Uncommenting Camunda REST API
- Adding (uncommented) Spring Boot Data
- Adding (uncommented) Hibernate configuration to application.yaml

### 1.0.4

- Adding Camunda Enterprise Edition

### 1.0.3

- Fixing the Maven issue

### 1.0.2

- Fixing the Eclipse issue

### 1.0.1

- Fixing the basic package

### 1.0.0

- Initial version

## Maintainer
- [Andreas Martin](https://github.com/andreasmartin)

## License
- [Apache License, Version 2.0](https://github.com/DigiBP/digibp-archetype-camunda-boot/blob/master/LICENSE)