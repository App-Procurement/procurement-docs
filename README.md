# Introduction
This repo contains the procurement application documentation and links to all other procurement documentation. 

# Different Documentation location
|github location | Description | WebLocation |
|:---|:---|:---|
|https://github.com/App-Procurement/procurement-docs | Procurement Main docs| https://procurement-docs.netlify.app |
|https://github.com/App-Procurement/procurement-architectures | All procurement architectures are described here| NA  |
|https://github.com/App-Procurement/procurement-usecases-doc | Procurement usecases docs| https://procurement-usecases-doc.netlify.app |
|https://github.com/App-Procurement/procurement-catalogue | Procurement artifacts cataloue | https://procurement-catalogue.netlify.app |
|https://github.com/App-Procurement/procurement-tech-doc | Procurement technical docs| https://procurement-tech-doc.netlify.app |
|https://github.com/App-Procurement/procurement-api-spec | Procurement api specification | NA |
|https://github.com/App-Procurement/procurement-website | Procurement Website | https://procurement-website.netlify.app |
|https://github.com/App-Procurement/procurement-training | Procurement Training and SkillSet | NA|

# Key Entities and Lifecycle
|Module | Entity | Description | LifeCycle | Transactions|
|:---|:---|:---|:---|:---|
|Requisition Management | Purchase Request| This is the very first request that is raised from internal employees of the organization to purchase any item | create/update/delete/approve/reject/archive |![alt](./transactions/purchase-request-txns.md)| 
|Requisition Management | Purchase Requisition| Any approved purchase request will trigger a new entity Purchase Requisition | create/update/delete/approve/reject/archive | link|
|Requisition Management | Purchase Order | Any approved purchase request will trigger a new entity Purchase Requisition | create/update/delete/approve/reject/archive | link|
