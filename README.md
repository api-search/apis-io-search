# APIs.io Search API (apis-io)
The API contract for the APIs.io API search API, providing all of the details used to manage the API, providing the manifest for everything that has happened throughout the lifecycle of this API over time.

The [APIs.json](https://github.com/api-search/search-api/blob/main/apis.yml) for APIs.io Search API is using version 0.18 of the [specification](https://apisjson.org), which is used to auto generate this README, and automate other parts of automation for the API.

This API contract has APIs, Search Engine, Directory applied as tags to help organize and make more discoverable via GitHub search, IDE, and other discovery tools.

This API contract was originally created on 2024-08-20, and was last modified on 2024-09-05, with 0 days since the last update or modification to API or any issues.

## APIs
These are the APIs that are contained within this Contract APIs.json.

### APIs.io Search API (apis-io:search-api)
This is the API to access APIs.io API search engine, from the product management perspective.

#### Tags
APIs, Search Engine, Directory

#### Default URLs
<table style="width: 100%">
    <tr>
        <td width="20%">Human URL</td>
        <td width="35%">The default landing page for human visitors of an API.</td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation" align="center">URL</a></td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>
    <tr>
        <td width="20%">Base URL</td>
        <td width="35%">The base url for applications make calls to an API.</td>
        <td width="15%" align="center"><a href="https://search-api.apis.io" align="center">URL</a></td>
        <td width="15%" align="center"><a href="https://search-api.apis.io">Policy</a></td>
        <td width="15%" align="center"><a href="https://search-api.apis.io">Guidance</a></td>
    </tr>    
</table>
    
#### Source of Truth
<table style="width: 100%">
    <tr>
        <td width="20%">GitHub Repository</td>
        <td width="35%">The repository for managing everything about the API.</td>
        <td width="15%" align="center"><a href="https://github.com/api-search/search-api    " align="center">URL</a></td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>
    <tr>
        <td width="20%">GitHub Action</td>
         <td width="35%">The pipeline used to automate the deploying of the API.</td>
        <td width="15%" align="center"><a href="https://github.com/api-search/search-api/blob/main/.github/workflows/pipeline.yml " align="center">URL</a></td>
        <td width="15%" align="center"><a href="https://search-api.apis.io">Policy</a></td>
        <td width="15%" align="center"><a href="https://search-api.apis.io">Guidance</a></td>
    </tr>    
</table>

#### Documentation for API
<table style="width: 100%">
    <tr>
        <td width="20%">Documentation</td>
        <td width="35%">The documentation for understand how to use the API.</td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation/" align="center">URL</a></td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>  
</table>

#### Technical Contract
<table style="width: 100%">
    <tr>
        <td width="20%">OpenAPI</td>
        <td width="35%">The machine-readable OpenAPI contract for the API.</td>
        <td width="15%" align="center"><a href="https://developer.apis.io/openapi" align="center">URL</a></td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="15%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>
    <tr>
        <td width="20%">Postman Collection</td>
         <td width="35%">An executable Postman Collection for working with the API.</td>
        <td width="15%" align="center"><a href="https://developer.apis.io/postman-collection/" align="center">URL</a></td>
        <td width="15%" align="center"><a href="https://search-api.apis.io">Policy</a></td>
        <td width="15%" align="center"><a href="https://search-api.apis.io">Guidance</a></td>
    </tr>    
</table>

#### Managing Change

- ChangeLog: https://github.com/api-search/search-api/labels/change-log
- RoadMap: https://github.com/api-search/search-api/labels/road-map

#### Business Alignment

- UseCases: https://github.com/api-search/search-api/blob/main/use-cases.yml

#### Reliability

- StatusPage: https://www.postman.com/api-evangelist/apis-io/monitor/APIs-io-Search---Status~1ef6bc29-9da9-4040-b98b-cef03be1155e              
- Performance: https://www.postman.com/api-evangelist/apis-io/monitor/APIs-io-Search---Performance~1ef6bc38-c969-4bd0-815b-25b7d1b1a503

Contact APIs.io at info@apis.io 

### Common Properties

  # Workspaces
  - type: GitHubOrganization
    url: https://github.com/api-search/ 

  - type: PostmanWorkspace
    url: https://www.postman.com/api-evangelist/apis-io/overview

  # Onboarding
  - type: Portal
    url: https://developer.apis.io

  - type: GettingStarted
    url: 'https://developer.apis.io/getting-started/'  

  - type: Plans
    url: 'https://developer.apis.io/plans/'         

  - type: Authentication
    url: 'https://developer.apis.io/authentication/'            

  # Change
  - type: RoadMap
    url: https://developer.apis.io/road-map/

  - type: ChangeLog
    url: https://developer.apis.io/change-log/                             

  # Code
  - type: SDKs
    url: https://developer.apis.io/sdks/                                          

  # Monitors
  - type: Monitor
    url: 'https://api-evangelist.postman.co/workspace/APIs.io-Private~a91b6fa0-9b59-4330-bec4-bf87c30b853a/monitor/Testing-Uptime---APIs-io-Search~1ee42164-0de2-4c80-b9a6-257e30c42c9e'

  # Communication
  - type: Blog
    url: 'https://developer.apis.io/blog/' 

  - type: BlogFeed
    url: 'https://developer.apis.io/atom.xml'

  - type: Videos
    url: 'https://developer.apis.io/videos/'   

  # Support / Feedback Loop
  - type: Forums
    url: 'https://github.com/orgs/api-search/discussions'

  - type: Support
    url: 'https://developer.apis.io/support/''

  - type: Issues
    url: 'https://github.com/api-search/developer-portal/issues' 

  - type: Email
    url: 'info@apievangelist.com'

  # Governance
  - type: Policies
    url: https://developer.apis.io/policies.yml

  - type: ApisJsonRules
    url:  https://developer.apis.io/apis-json-rules.yml

  - type: OpenApiRules
    url: https://developer.apis.io/openapi-rules.yml  

  - type: Lifecycle
    url: https://developer.apis.io/api-lifecycle.yml

  # Legal
  - type: TermsOfService
    url: 'https://developer.apis.io/terms-of-service/'  
    
  - type: PrivacyPolicy
    url: 'https://developer.apis.io/privacy-policy/' 
                       
    
maintainers:

  - FN: Kin Lane
    email: info@apievangelist.com
    X-github: kinlane