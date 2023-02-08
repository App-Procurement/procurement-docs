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
|**Requisition Management** | Purchase Request| This is the very first request that is raised from internal employees of the organization to purchase any item | create/update/delete/approve/reject/archive | [link-to](./transactions/purchase-request-txns.md)| 
| | Purchase Requisition| Any approved purchase request will trigger a new entity Purchase Requisition | create/update/delete/approve/reject/archive | link|
| | Purchase Order | Any approved purchase request will trigger a new entity Purchase Requisition | create/update/delete/approve/reject/archive | link|


# Key UseCases
|Module | UseCase | Description | Actor | Design Link | UseCase Details| Api Specs |
|:---|:---|:---|:---|:---|:---|:---|
|**Requisition Management** | Create Purchase Request | This usecase describes how the internal employees raise Purchase Request | Admin/Approver/Requestor | [link-to](./transactions/purchase-request-txns.md)| [link-to](./UseCases/Requistion-Management-UseCases.md#create-purchase-request) | [link-to](./api-specs/Requistion-Management-api-spec.md#create-purchase-request)|
|**Requisition Management** | Update Purchase Request | This usecase describes how the internal employees raise Purchase Request | Admin/Approver/Requestor | [link-to](./transactions/purchase-request-txns.md)| [link-to](./UseCases/Requistion-Management-UseCases.md#create-purchase-request) | [link-to](./api-specs/Requistion-Management-api-spec.md#create-purchase-request)|