# APIs.io Search API (apis-io)
This is the API contract for the APIs.io API search API, providing all of the details used to manage the API, providing the manifest for everything that has happened throughout the lifecycle of this API over time.

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
        <td width="10%" align="center"><img src="https://apievangelist.com/images/human-url.png" width="40"></td>
        <td width="20%">Human URL</td>
        <td width="40%">The default landing page for human visitors of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/base-url.png" width="40"></td>
        <td>Base URL</td>
        <td>The base url for applications make calls to an API.</td>
        <td width="10%" align="center"><a href="https://search-api.apis.io" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Policy</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Guidance</a></td>
    </tr>    
</table>
    
#### Source of Truth
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/repositories.png" width="40"></td>
        <td width="20%">GitHub Repository</td>
        <td width="40%">The repository for managing everything about the API.</td>
        <td width="10%" align="center"><a href="https://github.com/api-search/search-api    " align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/actions.png" width="40"></td>
        <td>GitHub Action</td>
         <td>The pipeline used to automate the deploying of the API.</td>
        <td width="10%" align="center"><a href="https://github.com/api-search/search-api/blob/main/.github/workflows/pipeline.yml " align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Policy</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Guidance</a></td>
    </tr>    
</table>

#### Documentation for API
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/documentation.png" width="40"></td>
        <td width="20%">Documentation</td>
        <td width="40%">The documentation for understand how to use the API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>  
</table>

#### Technical Contract
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/openapi.png" width="40"></td>
        <td width="20%">OpenAPI</td>
        <td width="40%">The machine-readable OpenAPI contract for the API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/openapi" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/collection.png" width="40"></td>
        <td>Postman Collection</td>
         <td>An executable Postman Collection for working with the API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/postman-collection/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Policy</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Guidance</a></td>
    </tr>    
</table>

#### Operations
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/method-get.png" width="60"></td>
        <td width="20%">/search/apis</td>
        <td width="70%">Search APIs - Searching across all APIs by keyword or phrase.</td>
    </tr>
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/method-post.png" width="60"></td>
        <td width="20%">/search/apis</td>
        <td width="70%">Submit API - Submit a valid APIs.json to be included in APIs.io.</td>
    </tr>   
</table>

#### Managing Change
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/change-logs.png" width="40"></td>
        <td width="20%">ChangeLog</td>
        <td width="40%">A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="hhttps://github.com/api-search/search-api/labels/change-log" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/road-maps.png" width="40"></td>
        <td>RoadMap</td>
         <td>A list of the planned changes to an API that will be coming in the future.</td>
        <td width="10%" align="center"><a href="https://github.com/api-search/search-api/labels/road-map" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Policy</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Guidance</a></td>
    </tr>    
</table>

#### Business Alignment
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/use-cases.png" width="40"></td>
        <td width="20%">Use Cases</td>
        <td width="40%">The who, what, how, why, and where of consumers using the API.</td>
        <td width="10%" align="center"><a href="https://github.com/api-search/search-api/blob/main/use-cases.yml" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>  
</table>

#### Reliability
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/status.png" width="40"></td>
        <td width="20%">Status Page</td>
        <td width="40%">The dedicated page that monitors the status of the API availability.</td>
        <td width="10%" align="center"><a href="https://www.postman.com/api-evangelist/apis-io/monitor/APIs-io-Search---Status~1ef6bc29-9da9-4040-b98b-cef03be1155e" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>  
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/performance.png" width="40"></td>
        <td>Performance</td>
        <td>The dedicated page that monitors the performance of each API.</td>
        <td width="10%" align="center"><a href="https://www.postman.com/api-evangelist/apis-io/monitor/APIs-io-Search---Performance~1ef6bc38-c969-4bd0-815b-25b7d1b1a503" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>     
</table>

### Common Properties
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/github-organization.png" width="40"></td>
        <td width="20%">GitHub Organization</td>
        <td width="40%">The overall organization that an API is part of for the domain.</td>
        <td width="10%" align="center"><a href="https://github.com/api-search/ " align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>  
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/postman-workspace.png" width="40"></td>
        <td>Postman Workspace</td>
        <td>The dedicated Postman workspace for working with the API.</td>
        <td width="10%" align="center"><a href="https://www.postman.com/api-evangelist/apis-io/monitor/APIs-io-Search---Performance~1ef6bc38-c969-4bd0-815b-25b7d1b1a503" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>     
</table>

### Onboarding
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/portals.png" width="40"></td>
        <td width="20%">Portal</td>
        <td width="40%">The dedicated portal where you will find and common supporting resources.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>  
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/getting-started.png" width="40"></td>
        <td>Getting Started</td>
        <td>Information regarding each step required in getting started with API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/getting-started/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>  
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/plans.png" width="40"></td>
        <td>Plans</td>
        <td>The plans, resources, features, and rate limits for consuming the API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/plans/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>  
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/authentication.png" width="40"></td>
        <td>Authentication</td>
        <td>How consumers will be authenticating with an API when using in application.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/authentication/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>            
</table>

### Managing Overall Change
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/change-logs.png" width="40"></td>
        <td width="20%">ChangeLog</td>
        <td width="40%">A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/road-map/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/road-maps.png" width="40"></td>
        <td>RoadMap</td>
         <td>A list of the planned changes to an API that will be coming in the future.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/change-log/  " align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Policy</a></td>
        <td width="10%" align="center"><a href="https://search-api.apis.io">Guidance</a></td>
    </tr>    
</table>

### Code
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/sdks.png" width="40"></td>
        <td width="20%">SDKs</td>
        <td width="40%">A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/sdks/   " align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>   
</table>

### Communication
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/blogs.png" width="40"></td>
        <td width="20%">Blog</td>
        <td width="40%">A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/blog/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>   
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/blog-feeds.png" width="40"></td>
        <td>BlogFeed</td>
        <td>A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/atom.xml" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>   
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/videos.png" width="40"></td>
        <td>Videos</td>
        <td>A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/videos/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>          
</table>

### Support / Feedback Loop
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/forums.png" width="40"></td>
        <td width="20%">Forums</td>
        <td width="40%">A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://github.com/orgs/api-search/discussions" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>   
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/support.png" width="40"></td>
        <td>Support</td>
        <td>A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/support/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>   
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/issues.png" width="40"></td>
        <td>Issues</td>
        <td>A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://github.com/api-search/developer-portal/issues" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr> 
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/email.png" width="40"></td>
        <td>Email</td>
        <td>A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="info@apievangelist.com" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>              
</table>

### Governance
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/policies.png" width="40"></td>
        <td width="20%">Policies</td>
        <td width="40%">A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/policies.yml" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>   
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/rules.png" width="40"></td>
        <td>ApisJsonRules</td>
        <td>A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/apis-json-rules.yml" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>   
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/rules.png" width="40"></td>
        <td>OpenApiRules</td>
        <td>A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/openapi-rules.yml" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr> 
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/lifecycle.png" width="40"></td>
        <td>Lifecycle</td>
        <td>A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/api-lifecycle.yml" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>              
</table>

### Legal
<table style="width: 100%">
    <tr>
        <td width="10%" align="center"><img src="https://apievangelist.com/images/terms-of-service.png" width="40"></td>
        <td width="20%">Terms Of Service</td>
        <td width="40%">A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/terms-of-service/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>   
    <tr>
        <td align="center"><img src="https://apievangelist.com/images/privacy-policy.png" width="40"></td>
        <td>Privacy Policy</td>
        <td>A list of the changes that have occurred to each version of an API.</td>
        <td width="10%" align="center"><a href="https://developer.apis.io/privacy-policy/" align="center">URL</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Policy</a></td>
        <td width="10%" align="center"><a href="https://developer.apis.io/documentation">Guidance</a></td>
    </tr>                
</table>

maintainers:

  - FN: Kin Lane
    email: info@apievangelist.com
    X-github: kinlane