# Fundamentals of Azure Cloud

## Azure Services

Below is a list of Azure services found at the time of writing based on [Azure Portal All Services](https://portal.azure.com/#allservices). There are about 301 services
excluding others. The categories that are more related to the fundamentals are in bold

 | Service Category Name | Service Count| Examples |
| --- | --- | --- |
| **Analytics**| 15 | |
|AI/ML|9||
| BlockChain | 1 ||
| **Computer** | 26 | virtual machine|
| Containers | 5 | |
| **Database** | 20 | |
|DevOps|8||
|**Identity**|23||
|**Integration**|28||
|Intune|4||
|**IoT**|24||
|**Management & Governance**|28||
|**Monitor**|9||
| Mobile | 3||
| **Networking** | 38 | |
| **Storage** | 16 ||
| Web | 16 | |
|**Security**|23||
|Others|247||


## Azure service life cycles

- Development: SDLC: Training/Requirement/Design/Implement/Verify/Release/Respond
- Private Preview: only a small number of customers; no SLA; test new features and functionalities
- Public Preview: Everyone can see; pre-release; should not be used for business critical; no guaranteed supports. 
- General Availablity: Production release; SLA if not for free
- End of support: will give 12 month prior notice

## Azure support levels

|Support | Basic |Developer|Standard|Professional Direct|
| --- | --- | --- |---|---|
|Fee| Free | $37/month|$128/month|$1280/month|
|Scope| All customers| dev/test | prod | business critical|
|24/7 self-help| Y | Y|Y|Y|
|Submit tickets| Y | Y |Y | Y|
|Azure Advisor | Y|Y|Y|Y|
|Azure Service Health|Y|Y|Y|Y|
|3rd party service|X|Y|Y|Y|
|24/7 email/phone|X|email@business hour|Y|Y|
|Severity Response|X|Level C in 8 hour |C/8h; B/4h; A/1h| C/4h; B/2h; A/1h|
|Architecture support|X|general guideance|general guidance | delievery manager help|
|Support API|X|X|X|Y|
|Operation Support|X|X|X|Y|
|Training|X|X|X|Y|
|Proactive Guidance|X|X|X|Y|

## Cost Estimate

- Pricing Calculator
- Total Cost of Ownership 

## SLA and Credits

SLA: 
  - service level agreement between customers and service providers
  - criteria: availability; latency
  - availability: (maximal up time - downtime)/maximal up time
  - if failed to meet SLA, the CSP gives credit. Customer needs to claim the credit before the end of next month. For example, if SLA failure happens
     in May 10, 2021, then June 30, 2021 is the deadline for claiming.
  - SLA is associated with purchased service; free services don't get support, and no SLA. Services purchased with credit, their SLAs are not honoured
  - Composite SLA: an application consists of three VMs one Azure load balance, the composite SLA = SLA(vm1)*SLA(vm2)*SLA(vm3)*SLA(balance). 
  - Increase SLA by: 
        - Higher availability
        - Redundancy
        - Tier (increase from free to purchased ) 


## Types of Services

| Service Name | Service Type | Comments |
|:---|:---|:---|
|Azure Storage Account | IaaS | |
|Azure Virtual Machine | IaaS ||
|Azure App Service | PaaS ||
|Azure Database SQL | PaaS ||
|Azure Cosmos DB | PaaS||


