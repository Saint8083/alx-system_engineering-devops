## **An Introduction to Configuration Management**

Introduction
As a broader subject, configuration management (CM) refers to the process of systematically handling changes to a system in a way that it maintains integrity over time. Even though this process was not originated in the IT industry, the term is broadly used to refer to server configuration management.

Automation plays an essential role in server configuration management. It’s the mechanism used to make the server reach a desirable state, previously defined by provisioning scripts using a tool’s specific language and features. Automation is, in fact, the heart of configuration management for servers, and that’s why it’s common to also refer to configuration management tools as Automation Tools or IT Automation Tools.

Another common term used to describe the automation features implemented by configuration management tools is Server Orchestration or IT Orchestration, since these tools are typically capable of managing one to hundreds of servers from a central controller machine.

There are a number of configuration management tools available in the market. Puppet, Ansible, Chef and Salt are popular choices. Although each tool will have its own characteristics and work in slightly different ways, they are all driven by the same purpose: to make sure the system’s state matches the state described by your provisioning scripts.

Benefits of Configuration Management for Servers
Although the use of configuration management typically requires more initial planning and effort than manual system administration, all but the simplest of server infrastructures will be improved by the benefits that it provides. To name a few:

Quick Provisioning of New Servers
Whenever a new server needs to be deployed, a configuration management tool can automate most, if not all, of the provisioning process for you. Automation makes provisioning much quicker and more efficient because it allows tedious tasks to be performed faster and more accurately than any human could. Even with proper and thorough documentation, manually deploying a web server, for instance, could take hours compared to a few minutes with configuration management/automation.

Quick Recovery from Critical Events
With quick provisioning comes another benefit: quick recovery from critical events. When a server goes offline due to unknown circumstances, it might take several hours to properly audit the system and find out what really happened. In scenarios like this, deploying a replacement server is usually the safest way to get your services back online while a detailed inspection is done on the affected server. With configuration management and automation, this can be done in a quick and reliable way.

No More Snowflake Servers
At first glance, manual system administration may seem to be an easy way to deploy and quickly fix servers, but it often comes with a price. With time, it may become extremely difficult to know exactly what is installed on a server and which changes were made, when the process is not automated. Manual hotfixes, configuration tweaks, and software updates can turn servers into unique snowflakes, hard to manage and even harder to replicate. By using a configuration management tool, the procedure necessary for bringing up a new server or updating an existing one will be all documented in the provisioning scripts.
