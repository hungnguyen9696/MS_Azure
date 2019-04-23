#### AZURE PRICING AND SUPPORT

---

##### AZURE SUBSCRIPTION

###### Azure subscriptions

- Provides authenticated and authorized access to Azure products and services and allows you to provision Azure resources.
- Azure offers free and paid subscription options
- An account can have one or more subscriptions with different billing models and access management policies applied to each subscription.
  ![alt text](https://training.future-proof.net/assets/courseware/v1/eb5ad089879be59b30a76e0b04f9dc0e/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0402-subscriptions-and-accounts.png "Logo Title Text 1")

###### Subscription Uses and Options

You can use Azure subscriptions to define boundaries around Azure products, services, and resources.

There are two types of subscription boundaries that you can use.

- A Billing boundary:

This subscription type determines how Azure account is billed for using Azure.

You can create multiple subscriptions for different types of billing requirements.

- Access control boundary:

Azure would apply access management policies at the subscription level and you can create separate subscriptions to reflect different organizational structures.

![alt text](https://training.future-proof.net/assets/courseware/v1/978a6fb467dc6a4b13c158b0e12f1cfe/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0402-customer-offers.png "Logo Title Text 1")
You can select from a range of Azure subscription options including:

- A free account: This subscription is for 30 days and includes a 200 credit. This allows you unlimited access to the free Azure products and then a limit of \$200 to spend on the paid products. Your Azure services are disabled when the trial ends or when your credit expires for paid products, unless you upgrade to a paid subscription.

- Pay As You Go: This subscription allows you to pay for what you use by attaching your credit card or a debit card to your account.

- Member offers: Your existing membership to certain Microsoft products and services affords you credits for your Azure account on reduced rates on Azure services.

###### Management Groups

- are containers for managing access, policies, and compliance across multiple Azure subscriptions.
- allow you to order your Azure resources hierarchically into collections which provides a further level of classification beyond subscriptions.
- can manage your Azure subscriptions more effectively by using Azure policy and Azure role-based access controls.
- These provide distinct governance conditions that you can apply to each management group.
- The resources and subscriptions you assigned to a management group, automatically inherit the conditions that you apply to that management group.
  ![alt text](https://training.future-proof.net/assets/courseware/v1/4259f113d139fc1bc4c53bcc3610759d/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0402-management-groups-tree.png "Logo Title Text 1")

---

##### SUPPORT OPTIONS AVAILABLE WITH AZURE

###### Support Plan Options

Every Azure subscription includes free access to the following basic support services:

- Billing and subscription support
- Azure products and services documentation
- online self-help documentation
- white papers
- community support forums

Microsoft offers four paid Azure support plans for customers who require technical and operational support.

- Developer support is appropriate for Azure use in trial and non-production environments and includes business areas access to support engineers via email, less than eight business hours for initial response time.

- Standards support is appropriate for Azure use in production environments and includes access to support engineers via email and phone, 24-7. Critical business impacts incident submission and less than one hour initial response time for severity A accidents.

- Professional direct is appropriate for organizations with business-critical dependence on Azure. This option includes all features of the standard option as well as escalation management for priority issues, proactive guidance from a team of professional direct delivery managers, onboarding services, service reviews, and Azure Advisor consultations, architectural guidance based on best practices.

- Premier is ideal for organizations with substantial dependence on Microsoft products including Azure. Dissolution includes all the features of professional direct as well as support assistance for all Microsoft products and services, less than 15 minutes initial response time with Azure Rapid Response. Service reviews and reporting delivered by a designated Technical Account Manager. Customers specific architect would support such as design reviews, performance tuning, and configuration.

###### How to open a support ticket

If you have an issue in Azure, you can request assistance from the Azure support team by creating a new support ticket.

Create a support ticket

- Log in to the Azure portal.
- Choose "Help and Support" from the left navigation menu in the portal
- open the "Help and Support Blade" and select "New support requests"
- fill out all the required section
- select create to submit your support request
  ![alt text](https://training.future-proof.net/assets/courseware/v1/2386ba70ced2253493cb72c353e96ab8/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0404-support-ticket-creation.png "Logo Title Text 1")

###### Alternative support channels

- Microsoft Developer Network Forums,
- Stack Overflow
- Server Fault
- Azure feedback forums
- Twitter: Tweet @AzureSupport to get answers and support from the official Microsoft Azure Twitter channel.

###### Knowledge center

![alt text](https://training.future-proof.net/assets/courseware/v1/f96bd28df0e19cf014f5754b7905a9da/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0404-knowledge-center.png "Logo Title Text 1")
The Azure Knowledge Center is a searchable database that contains answers to common support questions, from a community of Azure experts, developers, customers and users.

You can browse through all the answers within the Azure Knowledge Center, find specific solutions by entering keywords search terms into the text entry field, and further refine your search results by selecting products or tags from the list provided from the drop-down list.

---

##### PLANNING AND MANAGING COSTS

###### Purchasing Azure Products and Services

There are three main customer types on which the available purchasing options for Azure products and services is contingent, including:

- Enterprise
- Web direct
- Cloud Solution Provider.
  ![alt text](https://training.future-proof.net/assets/courseware/v1/3e11b37cf797768a39bb14f25391373b/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0402-subscription-options.png "Logo Title Text 1")

Products and services in Azure are arranged by category, which have various resources that you can provision. You select the Azure products and services that fit your requirements, and your account is billed according to Azure's pay-for-what-you-use model.
![alt text](https://training.future-proof.net/assets/courseware/v1/682c7c94f8e14271f85ad070d60e504d/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0403-Azure-products-overview.png "Logo Title Text 1")

Usage meters
When you provision an Azure resource, Azure creates one or more meter instances for that resource. The meters track the resources' usage, and each meter generates a usage record that is used to calculate your bill.

For example, a single virtual machine that you provision in Azure might have the following meters tracking its usage:

- Compute Hours
- IP Address Hours
- Data Transfer In
- Data Transfer Out
- Standard Managed Disk
- Standard Managed Disk Operations
- Standard IO-Disk
- Standard IO-Block Blob Read
- Standard IO-Block Blob Write
- Standard IO-Block Blob Delete

###### Azure free account

An Azure free account provides subscribers with a 200 Azure credit that they can use for paid Azure products during a 30-day trial period. Once you use that \$200 credit or reach your trial's end, Azure suspends your account unless you sign up for a paid account.

![alt text](https://training.future-proof.net/assets/courseware/v1/c25916bd2749bfc7a804d173e1eca2b9/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0403-free-account.png "Logo Title Text 1")

If you upgrade to a Pay-As-You-Go subscription within the 30-day trial period, by providing your credit or debit card details, you can use a limited selection of free services for 12 months. After 12 months, you will be billed for the services and products in use on your account at the pay-as-you-go rate.

###### Factors Affecting Costs

The following sections describe the main factors that affect Azure costs, including resource type, services, and the user's location.

- Resource type
  Costs are resource-specific, so the usage that a meter tracks and the number of meters associated with a resource depend on the resource type.
  The usage that a meter tracks correlates to a quantity of billable units. Those are charged to your account for each billing period, and the rate per billable unit depends on the resource type you are using.
- Services
  Azure usage rates and billing periods can differ between Enterprise, Web Direct, and Cloud Solution Provider (CSP) customers. Some subscription types also include usage allowances, which affect costs.
  The Azure team develops and offers first-party products and services, while products and services from third-party vendors are available in the Azure marketplace. Different billing structures apply to each of these categories.
- Location
  The Azure infrastructure is globally distributed, and usage costs might vary between locations that offer particular Azure products, services, and resources.

###### Zones for Billing Purposes

Bandwidth refers to data moving in and out of Azure datacenters. Some inbound data transfers, such as data going into Azure datacenters, are free. For outbound data transfers, such as data going out of Azure datacenters, data transfer pricing is based on Zones.

![alt text](https://training.future-proof.net/assets/courseware/v1/4782e9ed722fa9a92a4faf3a91c0d7ef/asset-v1:FP+AZ-900+2019_T1+type@asset+block/0403-azure-regions-globe.png "Logo Title Text 1")

A Zone is a geographical grouping of Azure Regions for billing purposes. the following Zones exist and include the sample regions as listed below:

Zone 1 – West US, East US, Canada West, West Europe, France Central and others…
Zone 2 – Australia Central, Japan West, Central India, Korea South and others…
Zone 3 - Brazil South
DE Zone 1 - Germany Central, Germany Northeast
