---
name: AWS CloudSearch
x-slug: aws-cloudsearch
description: Amazon CloudSearch is a managed service in the AWS Cloud that makes it
  simple and cost-effective to set up, manage, and scale a search solution for your
  website or application.Amazon CloudSearch supports 34 languages and popular search
  features such as highlighting, autocomplete, and geospatial search. For more information,
  see Benefits.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS CloudSearch
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CloudSearch Add Tags
  x-api-slug: aws-cloudsearch
  description: |-
    Attaches resource tags to an
     Amazon CloudSearch domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=AddTags
  tags: Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionaddtags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionaddtags-get-openapi.md
- name: AWS CloudSearch Build Suggesters
  x-api-slug: aws-cloudsearch
  description: Indexes the search suggestions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=BuildSuggesters
  tags: Suggesters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionbuildsuggesters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionbuildsuggesters-get-openapi.md
- name: AWS CloudSearch Create Domain
  x-api-slug: aws-cloudsearch
  description: Creates a new search domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=CreateDomain
  tags: Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actioncreatedomain-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actioncreatedomain-get-openapi.md
- name: AWS CloudSearch Define Analysis Scheme
  x-api-slug: aws-cloudsearch
  description: Configures an analysis scheme that can be applied to a text or text-array
    field to define language-specific text processing options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DefineAnalysisScheme
  tags: Analysis Scheme
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondefineanalysisscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondefineanalysisscheme-get-openapi.md
- name: AWS CloudSearch Define Expression
  x-api-slug: aws-cloudsearch
  description: Configures an Expression  for the search domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DefineExpression
  tags: Expressions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondefineexpression-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondefineexpression-get-openapi.md
- name: AWS CloudSearch Define Index Field
  x-api-slug: aws-cloudsearch
  description: Configures an ndexField  for the search domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DefineIndexField
  tags: Index Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondefineindexfield-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondefineindexfield-get-openapi.md
- name: AWS CloudSearch Define Suggester
  x-api-slug: aws-cloudsearch
  description: Configures a suggester for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DefineSuggester
  tags: Suggesters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondefinesuggester-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondefinesuggester-get-openapi.md
- name: AWS CloudSearch Delete Analysis Scheme
  x-api-slug: aws-cloudsearch
  description: Deletes an analysis scheme.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DeleteAnalysisScheme
  tags: Analysis Scheme
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeleteanalysisscheme-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeleteanalysisscheme-get-openapi.md
- name: AWS CloudSearch Delete Domain
  x-api-slug: aws-cloudsearch
  description: Permanently deletes a search domain and all of its data.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DeleteDomain
  tags: Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeletedomain-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeletedomain-get-openapi.md
- name: AWS CloudSearch Delete Expression
  x-api-slug: aws-cloudsearch
  description: "Removes an \n  Expression\n  from the search domain."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DeleteExpression
  tags: Expressions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeleteexpression-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeleteexpression-get-openapi.md
- name: AWS CloudSearch Delete Index Field
  x-api-slug: aws-cloudsearch
  description: "Removes an \n  IndexField\n  from the search domain."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DeleteIndexField
  tags: Index Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeleteindexfield-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeleteindexfield-get-openapi.md
- name: AWS CloudSearch Delete Suggester
  x-api-slug: aws-cloudsearch
  description: Deletes a suggester.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DeleteSuggester
  tags: Suggesters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeletesuggester-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondeletesuggester-get-openapi.md
- name: AWS CloudSearch Describe Analysis Schemes
  x-api-slug: aws-cloudsearch
  description: Gets the analysis schemes configured for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeAnalysisSchemes
  tags: Analysis Scheme
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeanalysisschemes-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeanalysisschemes-get-openapi.md
- name: AWS CloudSearch Describe Availability Options
  x-api-slug: aws-cloudsearch
  description: Gets the availability options configured for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeAvailabilityOptions
  tags: Availability Options
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeavailabilityoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeavailabilityoptions-get-openapi.md
- name: AWS CloudSearch Describe Domains
  x-api-slug: aws-cloudsearch
  description: Gets information about the search domains owned by this account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeDomains
  tags: Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribedomains-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribedomains-get-openapi.md
- name: AWS CloudSearch Describe Expressions
  x-api-slug: aws-cloudsearch
  description: Gets the expressions configured for the search domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeExpressions
  tags: Expressions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeexpressions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeexpressions-get-openapi.md
- name: AWS CloudSearch Describe Index Fields
  x-api-slug: aws-cloudsearch
  description: Gets information about the index fields configured for the search domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeIndexFields
  tags: Index Fields
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeindexfields-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeindexfields-get-openapi.md
- name: AWS CloudSearch Describe Scaling Parameters
  x-api-slug: aws-cloudsearch
  description: Gets the scaling parameters configured for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeScalingParameters
  tags: Scaling Parameters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribescalingparameters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribescalingparameters-get-openapi.md
- name: AWS CloudSearch Describe Service Access Policies
  x-api-slug: aws-cloudsearch
  description: Gets information about the access policies that control access to the
    domain's document and search endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeServiceAccessPolicies
  tags: Service Access Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeserviceaccesspolicies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribeserviceaccesspolicies-get-openapi.md
- name: AWS CloudSearch Describe Suggesters
  x-api-slug: aws-cloudsearch
  description: Gets the suggesters configured for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=DescribeSuggesters
  tags: Suggesters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribesuggesters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actiondescribesuggesters-get-openapi.md
- name: AWS CloudSearch Index Documents
  x-api-slug: aws-cloudsearch
  description: Tells the search domain to start indexing its documents using the latest
    indexing options.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=IndexDocuments
  tags: Index Documents
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionindexdocuments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionindexdocuments-get-openapi.md
- name: AWS CloudSearch List Domain Names
  x-api-slug: aws-cloudsearch
  description: Lists all search domains owned by an account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=ListDomainNames
  tags: Domains
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionlistdomainnames-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionlistdomainnames-get-openapi.md
- name: AWS CloudSearch List Tags
  x-api-slug: aws-cloudsearch
  description: |-
    Displays all of the resource
     tags for an Amazon CloudSearch domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=ListTags
  tags: Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionlisttags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionlisttags-get-openapi.md
- name: AWS CloudSearch Remove Tags
  x-api-slug: aws-cloudsearch
  description: |-
    Removes the specified resource tags
     from an Amazon ES domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=RemoveTags
  tags: Tags
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionremovetags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionremovetags-get-openapi.md
- name: AWS CloudSearch Update Availability Options
  x-api-slug: aws-cloudsearch
  description: Configures the availability options for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=UpdateAvailabilityOptions
  tags: Availability Options
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionupdateavailabilityoptions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionupdateavailabilityoptions-get-openapi.md
- name: AWS CloudSearch Update Scaling Parameters
  x-api-slug: aws-cloudsearch
  description: Configures scaling parameters for a domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=UpdateScalingParameters
  tags: Scaling Parameters
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionupdatescalingparameters-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionupdatescalingparameters-get-openapi.md
- name: AWS CloudSearch Update Service Access Policies
  x-api-slug: aws-cloudsearch
  description: Configures the access rules that control access to the domain's document
    and search endpoints.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///?Action=UpdateServiceAccessPolicies
  tags: Service Access Policies
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionupdateserviceaccesspolicies-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/actionupdateserviceaccesspolicies-get-openapi.md
- name: AWS CloudSearch Search Documents
  x-api-slug: aws-cloudsearch
  description: You use the document service API to add, replace, or delete documents
    in your Amazon CloudSearch domain. For more information managing the documents
    in your search domain, see Uploading Data to an Amazon CloudSearch Domain.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https://///2013-01-01/documents/batch
  tags: Search
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/20130101documentsbatch-get-openapi.md
- name: AWS CloudSearch
  x-api-slug: aws-cloudsearch
  description: Amazon CloudSearch is a managed service in the AWS Cloud that makes
    it simple and cost-effective to set up, manage, and scale a search solution for
    your website or application.Amazon CloudSearch supports 34 languages and popular
    search features such as highlighting, autocomplete, and geospatial search. For
    more information, see Benefits.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Application-Services_AmazonCloudSearch.png
  humanURL: https://aws.amazon.com/cloudsearch/
  baseURL: https:///
  tags: AWS CloudSearch
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-cloudsearch/master/_listings/aws-cloudsearch/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cloudsearch/latest/developerguide/cloudsearch-command-line-tools.html
- type: x-console
  url: https://console.aws.amazon.com/cloudsearch
- type: x-documentation
  url: http://docs.aws.amazon.com/cloudsearch/latest/developerguide/api-ref.html *
    hard to find
- type: x-faq
  url: https://aws.amazon.com/cloudsearch/faqs/
- type: x-getting-started
  url: https://aws.amazon.com/cloudsearch/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/cloudsearch/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/cloudsearch/testimonials/
- type: x-website
  url: https://aws.amazon.com/cloudsearch/
- type: x-whats-new
  url: https://aws.amazon.com/cloudsearch/whats-new/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---