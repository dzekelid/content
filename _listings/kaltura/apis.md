---
name: Kaltura
x-slug: kaltura
description: A recognized leader in the OTT TV (Over the Top TV), OVP (Online Video
  Platform), EdVP (Education Video Platform) and EVP (Enterprise Video Platform) markets,
  Kaltura has emerged as the fastest growing video platform, and as the one with the
  widest use-case and appeal. Kaltura is deployed globally in thousands of enterprises,
  media companies, service providers and educational institutions and engages hundreds
  of millions of viewers at home, in work, and at school. The company is committed
  to its core values of openness, flexibility, and collaboration, and is the initiator
  and backer of the worlds leading open-source video-management project, which is
  home to more than 100,000 community members.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
x-kinRank: "7"
x-alexaRank: "23496"
tags: Content
created: "2018-06-18"
modified: "2018-06-18"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/apis.md
specificationVersion: "0.14"
apis:
- name: Kaltura VPaaS Post Service Attachment Attachmentasset Action Setcontent
  x-api-slug: kaltura-vpaas
  description: Update content of attachment asset
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/attachment_attachmentasset/action/setContent
  tags: Service,Attachment,Attachmentasset,Action,SetContent
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/serviceattachment-attachmentassetactionsetcontent-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/serviceattachment-attachmentassetactionsetcontent-post-openapi.md
- name: Kaltura VPaaS Post Service Baseentry Action Addcontent
  x-api-slug: kaltura-vpaas
  description: Attach content resource to entry in status NO_MEDIA
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/baseentry/action/addContent
  tags: Service,Baseentry,Action,AddContent
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicebaseentryactionaddcontent-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicebaseentryactionaddcontent-post-openapi.md
- name: Kaltura VPaaS Post Service Baseentry Action Updatecontent
  x-api-slug: kaltura-vpaas
  description: Update the content resource associated with the entry.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/baseentry/action/updateContent
  tags: Service,Baseentry,Action,UpdateContent
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicebaseentryactionupdatecontent-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicebaseentryactionupdatecontent-post-openapi.md
- name: Kaltura VPaaS Post Service Caption Captionasset Action Setcontent
  x-api-slug: kaltura-vpaas
  description: Update content of caption asset
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/caption_captionasset/action/setContent
  tags: Service,Caption,Captionasset,Action,SetContent
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecaption-captionassetactionsetcontent-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecaption-captionassetactionsetcontent-post-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Contentdistributionbatch Action
    Createrequiredjobs
  x-api-slug: kaltura-vpaas
  description: creates all required jobs according to entry distribution dirty flags
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_contentdistributionbatch/action/createRequiredJobs
  tags: Service,Contentdistribution,Contentdistributionbatch,Action,CreateRequiredJobs
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-contentdistributionbatchactioncreaterequiredjobs-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-contentdistributionbatchactioncreaterequiredjobs-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Contentdistributionbatch Action
    Getasseturl
  x-api-slug: kaltura-vpaas
  description: returns absolute valid url for asset file
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_contentdistributionbatch/action/getAssetUrl
  tags: Service,Contentdistribution,Contentdistributionbatch,Action,GetAssetUrl
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-contentdistributionbatchactiongetasseturl-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-contentdistributionbatchactiongetasseturl-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Contentdistributionbatch Action
    Updatesunstatus
  x-api-slug: kaltura-vpaas
  description: updates entry distribution sun status in the search engine
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_contentdistributionbatch/action/updateSunStatus
  tags: Service,Contentdistribution,Contentdistributionbatch,Action,UpdateSunStatus
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-contentdistributionbatchactionupdatesunstatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-contentdistributionbatchactionupdatesunstatus-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Distributionprofile Action Add
  x-api-slug: kaltura-vpaas
  description: Add new Distribution Profile
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_distributionprofile/action/add
  tags: Service,Contentdistribution,Distributionprofile,Action,Add
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionadd-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionadd-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Distributionprofile Action Delete
  x-api-slug: kaltura-vpaas
  description: Delete Distribution Profile by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_distributionprofile/action/delete
  tags: Service,Contentdistribution,Distributionprofile,Action,Delete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactiondelete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactiondelete-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Distributionprofile Action Get
  x-api-slug: kaltura-vpaas
  description: Get Distribution Profile by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_distributionprofile/action/get
  tags: Service,Contentdistribution,Distributionprofile,Action,Get
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionget-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Distributionprofile Action List
  x-api-slug: kaltura-vpaas
  description: List all distribution providers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_distributionprofile/action/list
  tags: Service,Contentdistribution,Distributionprofile,Action,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionlist-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Distributionprofile Action Listbypartner
  x-api-slug: kaltura-vpaas
  description: ""
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_distributionprofile/action/listByPartner
  tags: Service,Contentdistribution,Distributionprofile,Action,ListByPartner
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionlistbypartner-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionlistbypartner-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Distributionprofile Action Update
  x-api-slug: kaltura-vpaas
  description: Update Distribution Profile by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_distributionprofile/action/update
  tags: Service,Contentdistribution,Distributionprofile,Action,Update
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionupdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionupdate-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Distributionprofile Action Updatestatus
  x-api-slug: kaltura-vpaas
  description: Update Distribution Profile status by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_distributionprofile/action/updateStatus
  tags: Service,Contentdistribution,Distributionprofile,Action,UpdateStatus
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionupdatestatus-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprofileactionupdatestatus-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Distributionprover Action List
  x-api-slug: kaltura-vpaas
  description: List all distribution providers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_distributionprovider/action/list
  tags: Service,Contentdistribution,Distributionprovider,Action,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprovideractionlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-distributionprovideractionlist-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Add
  x-api-slug: kaltura-vpaas
  description: Add new Entry Distribution
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/add
  tags: Service,Contentdistribution,Entrydistribution,Action,Add
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionadd-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionadd-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Delete
  x-api-slug: kaltura-vpaas
  description: Delete Entry Distribution by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/delete
  tags: Service,Contentdistribution,Entrydistribution,Action,Delete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactiondelete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactiondelete-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Get
  x-api-slug: kaltura-vpaas
  description: Get Entry Distribution by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/get
  tags: Service,Contentdistribution,Entrydistribution,Action,Get
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionget-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action List
  x-api-slug: kaltura-vpaas
  description: List all distribution providers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/list
  tags: Service,Contentdistribution,Entrydistribution,Action,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionlist-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Retrysubmit
  x-api-slug: kaltura-vpaas
  description: Retries last submit action
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/retrySubmit
  tags: Service,Contentdistribution,Entrydistribution,Action,RetrySubmit
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionretrysubmit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionretrysubmit-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Servereturneddata
  x-api-slug: kaltura-vpaas
  description: Serves entry distribution returned data
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/serveReturnedData
  tags: Service,Contentdistribution,Entrydistribution,Action,ServeReturnedData
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionservereturneddata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionservereturneddata-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Servesentdata
  x-api-slug: kaltura-vpaas
  description: Serves entry distribution sent data
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/serveSentData
  tags: Service,Contentdistribution,Entrydistribution,Action,ServeSentData
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionservesentdata-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionservesentdata-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Submitadd
  x-api-slug: kaltura-vpaas
  description: Submits Entry Distribution to the remote destination
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/submitAdd
  tags: Service,Contentdistribution,Entrydistribution,Action,Submit
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionsubmitadd-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionsubmitadd-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Submitdelete
  x-api-slug: kaltura-vpaas
  description: Deletes Entry Distribution from the remote destination
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/submitDelete
  tags: Service,Contentdistribution,Entrydistribution,Action,Submit
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionsubmitdelete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionsubmitdelete-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Submitfetchreport
  x-api-slug: kaltura-vpaas
  description: Submits Entry Distribution report request
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/submitFetchReport
  tags: Service,Contentdistribution,Entrydistribution,Action,SubmitFetchReport
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionsubmitfetchreport-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionsubmitfetchreport-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Submitupdate
  x-api-slug: kaltura-vpaas
  description: Submits Entry Distribution changes to the remote destination
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/submitUpdate
  tags: Service,Contentdistribution,Entrydistribution,Action,Submit
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionsubmitupdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionsubmitupdate-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Update
  x-api-slug: kaltura-vpaas
  description: Update Entry Distribution by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/update
  tags: Service,Contentdistribution,Entrydistribution,Action,Update
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionupdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionupdate-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Entrydistribution Action Valate
  x-api-slug: kaltura-vpaas
  description: Validates Entry Distribution by id for submission
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_entrydistribution/action/validate
  tags: Service,Contentdistribution,Entrydistribution,Action,Validate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionvalidate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-entrydistributionactionvalidate-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionprover Action
    Add
  x-api-slug: kaltura-vpaas
  description: Add new Generic Distribution Provider
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovider/action/add
  tags: Service,Contentdistribution,Genericdistributionprovider,Action,Add
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionadd-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionadd-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionprover Action
    Delete
  x-api-slug: kaltura-vpaas
  description: Delete Generic Distribution Provider by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovider/action/delete
  tags: Service,Contentdistribution,Genericdistributionprovider,Action,Delete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractiondelete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractiondelete-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionprover Action
    Get
  x-api-slug: kaltura-vpaas
  description: Get Generic Distribution Provider by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovider/action/get
  tags: Service,Contentdistribution,Genericdistributionprovider,Action,Get
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionget-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionprover Action
    List
  x-api-slug: kaltura-vpaas
  description: List all distribution providers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovider/action/list
  tags: Service,Contentdistribution,Genericdistributionprovider,Action,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionlist-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionprover Action
    Update
  x-api-slug: kaltura-vpaas
  description: Update Generic Distribution Provider by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovider/action/update
  tags: Service,Contentdistribution,Genericdistributionprovider,Action,Update
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionupdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionupdate-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Add
  x-api-slug: kaltura-vpaas
  description: Add new Generic Distribution Provider Action
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/add
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,Add
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionadd-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionadd-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Addmrsstransform
  x-api-slug: kaltura-vpaas
  description: Add MRSS transform file to generic distribution provider action
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/addMrssTransform
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,AddMrssTransform
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddmrsstransform-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddmrsstransform-get-openapi.md
- name: Kaltura VPaaS Post Service Contentdistribution Genericdistributionproveraction
    Action Addmrsstransformfromfile
  x-api-slug: kaltura-vpaas
  description: Add MRSS transform file to generic distribution provider action
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/addMrssTransformFromFile
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,AddMrssTransformFromFile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddmrsstransformfromfile-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddmrsstransformfromfile-post-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Addmrssvalate
  x-api-slug: kaltura-vpaas
  description: Add MRSS validate file to generic distribution provider action
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/addMrssValidate
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,AddMrssValidate
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddmrssvalidate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddmrssvalidate-get-openapi.md
- name: Kaltura VPaaS Post Service Contentdistribution Genericdistributionproveraction
    Action Addmrssvalatefromfile
  x-api-slug: kaltura-vpaas
  description: Add MRSS validate file to generic distribution provider action
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/addMrssValidateFromFile
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,AddMrssValidateFromFile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddmrssvalidatefromfile-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddmrssvalidatefromfile-post-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Addresultstransform
  x-api-slug: kaltura-vpaas
  description: Add results transform file to generic distribution provider action
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/addResultsTransform
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,AddResultsTransform
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddresultstransform-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddresultstransform-get-openapi.md
- name: Kaltura VPaaS Post Service Contentdistribution Genericdistributionproveraction
    Action Addresultstransformfromfile
  x-api-slug: kaltura-vpaas
  description: Add MRSS transform file to generic distribution provider action
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/addResultsTransformFromFile
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,AddResultsTransformFromFile
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddresultstransformfromfile-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionaddresultstransformfromfile-post-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Delete
  x-api-slug: kaltura-vpaas
  description: Delete Generic Distribution Provider Action by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/delete
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,Delete
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactiondelete-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactiondelete-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Deletebyproverid
  x-api-slug: kaltura-vpaas
  description: Delete Generic Distribution Provider Action by provider id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/deleteByProviderId
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,DeleteByProviderId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactiondeletebyproviderid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactiondeletebyproviderid-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Get
  x-api-slug: kaltura-vpaas
  description: Get Generic Distribution Provider Action by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/get
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,Get
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionget-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionget-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Getbyproverid
  x-api-slug: kaltura-vpaas
  description: Get Generic Distribution Provider Action by provider id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/getByProviderId
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,GetByProviderId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactiongetbyproviderid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactiongetbyproviderid-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action List
  x-api-slug: kaltura-vpaas
  description: List all distribution providers
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/list
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,List
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionlist-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionlist-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Update
  x-api-slug: kaltura-vpaas
  description: Update Generic Distribution Provider Action by id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/update
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,Update
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionupdate-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionupdate-get-openapi.md
- name: Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction
    Action Updatebyproverid
  x-api-slug: kaltura-vpaas
  description: Update Generic Distribution Provider Action by provider id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3//service/contentdistribution_genericdistributionprovideraction/action/updateByProviderId
  tags: Service,Contentdistribution,Genericdistributionprovideraction,Action,UpdateByProviderId
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionupdatebyproviderid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/servicecontentdistribution-genericdistributionprovideractionactionupdatebyproviderid-get-openapi.md
- name: Kaltura VPaaS
  x-api-slug: kaltura-vpaas
  description: A recognized leader in the OTT TV (Over the Top TV), OVP (Online Video
    Platform), EdVP (Education Video Platform) and EVP (Enterprise Video Platform)
    markets, Kaltura has emerged as the fastest growing video platform, and as the
    one with the widest use-case and appeal. Kaltura is deployed globally in thousands
    of enterprises, media companies, service providers and educational institutions
    and engages hundreds of millions of viewers at home, in work, and at school. The
    company is committed to its core values of openness, flexibility, and collaboration,
    and is the initiator and backer of the worlds leading open-source video-management
    project, which is home to more than 100,000 community members.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28437-kaltura-vpaa-s.jpg
  humanURL: http://kaltura.com
  baseURL: https://www.kaltura.com//api_v3
  tags: Content
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/content/master/_listings/kaltura/openapi.md
x-common:
- type: x-blog
  url: https://blog.kaltura.com/
- type: x-code
  url: https://developer.kaltura.com/api-docs/Client_Libraries
- type: x-crunchbase
  url: https://crunchbase.com/organization/kaltura
- type: x-developer
  url: https://developer.kaltura.com/api-docs/Overview
- type: x-twitter
  url: https://twitter.com/Kaltura
- type: x-website
  url: http://kaltura.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---