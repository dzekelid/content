{
  "info": {
    "name": "Kaltura VPaaS Get Service Contentdistribution Distributionprofile Action Add",
    "_postman_id": "1ceecb6f-cf82-4c76-a9e2-0f913ee042f8",
    "description": "Add new Distribution Profile",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "d1a7c456-8b0f-4da9-9734-cfb7609ea05a",
          "name": "attachmentAsset.setContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/setContent?contentResource[assetId]=%7B%7D&contentResource[content]=%7B%7D&contentResource[dropFolderFileId]=%7B%7D&contentResource[entryId]=%7B%7D&contentResource[fileSyncObjectType]=%7B%7D&contentResource[flavorParamsId]=%7B%7D&contentResource[forceAsyncDownload]=%7B%7D&contentResource[keepOriginalFile]=%7B%7D&contentResource[keyPassphrase]=%7B%7D&contentResource[localFilePath]=%7B%7D&contentResource[objectId]=%7B%7D&contentResource[objectSubType]=%7B%7D&contentResource[objectType]=%7B%7D&contentResource[privateKey]=%7B%7D&contentResource[publicKey]=%7B%7D&contentResource[resources]=%7B%7D&contentResource[resource][assetId]=%7B%7D&contentResource[resource][content]=%7B%7D&contentResource[resource][dropFolderFileId]=%7B%7D&contentResource[resource][entryId]=%7B%7D&contentResource[resource][fileSyncObjectType]=%7B%7D&contentResource[resource][flavorParamsId]=%7B%7D&contentResource[resource][forceAsyncDownload]=%7B%7D&contentResource[resource][keepOriginalFile]=%7B%7D&contentResource[resource][keyPassphrase]=%7B%7D&contentResource[resource][localFilePath]=%7B%7D&contentResource[resource][objectId]=%7B%7D&contentResource[resource][objectSubType]=%7B%7D&contentResource[resource][objectType]=%7B%7D&contentResource[resource][privateKey]=%7B%7D&contentResource[resource][publicKey]=%7B%7D&contentResource[resource][resources]=%7B%7D&contentResource[resource][resource][assetId]=%7B%7D&contentResource[resource][resource][content]=%7B%7D&contentResource[resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][entryId]=%7B%7D&contentResource[resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][objectId]=%7B%7D&contentResource[resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][objectType]=%7B%7D&contentResource[resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][assetId]=%7B%7D&contentResource[resource][resource][resource][content]=%7B%7D&contentResource[resource][resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][resource][entryId]=%7B%7D&contentResource[resource][resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][resource][objectId]=%7B%7D&contentResource[resource][resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][resource][objectType]=%7B%7D&contentResource[resource][resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][resource][token]=%7B%7D&contentResource[resource][resource][resource][url]=%7B%7D&contentResource[resource][resource][resource][version]=%7B%7D&contentResource[resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][token]=%7B%7D&contentResource[resource][resource][url]=%7B%7D&contentResource[resource][resource][version]=%7B%7D&contentResource[resource][storageProfileId]=%7B%7D&contentResource[resource][token]=%7B%7D&contentResource[resource][url]=%7B%7D&contentResource[resource][version]=%7B%7D&contentResource[storageProfileId]=%7B%7D&contentResource[token]=%7B%7D&contentResource[url]=%7B%7D&contentResource[version]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "contentResource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Update content of attachment asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21f771f3-4ddf-4528-9e47-832074cc4893"
            }
          ]
        },
        {
          "id": "89e824a6-3c83-40ad-b03b-d618ef5c55e3",
          "name": "baseEntry.addContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/baseentry/action/addContent?entryId=%7B%7D&No Name=%7B%7D&resource[assetId]=%7B%7D&resource[content]=%7B%7D&resource[dropFolderFileId]=%7B%7D&resource[entryId]=%7B%7D&resource[fileSyncObjectType]=%7B%7D&resource[flavorParamsId]=%7B%7D&resource[forceAsyncDownload]=%7B%7D&resource[keepOriginalFile]=%7B%7D&resource[keyPassphrase]=%7B%7D&resource[localFilePath]=%7B%7D&resource[objectId]=%7B%7D&resource[objectSubType]=%7B%7D&resource[objectType]=%7B%7D&resource[privateKey]=%7B%7D&resource[publicKey]=%7B%7D&resource[resources]=%7B%7D&resource[resource][assetId]=%7B%7D&resource[resource][content]=%7B%7D&resource[resource][dropFolderFileId]=%7B%7D&resource[resource][entryId]=%7B%7D&resource[resource][fileSyncObjectType]=%7B%7D&resource[resource][flavorParamsId]=%7B%7D&resource[resource][forceAsyncDownload]=%7B%7D&resource[resource][keepOriginalFile]=%7B%7D&resource[resource][keyPassphrase]=%7B%7D&resource[resource][localFilePath]=%7B%7D&resource[resource][objectId]=%7B%7D&resource[resource][objectSubType]=%7B%7D&resource[resource][objectType]=%7B%7D&resource[resource][privateKey]=%7B%7D&resource[resource][publicKey]=%7B%7D&resource[resource][resources]=%7B%7D&resource[resource][resource][assetId]=%7B%7D&resource[resource][resource][content]=%7B%7D&resource[resource][resource][dropFolderFileId]=%7B%7D&resource[resource][resource][entryId]=%7B%7D&resource[resource][resource][fileSyncObjectType]=%7B%7D&resource[resource][resource][flavorParamsId]=%7B%7D&resource[resource][resource][forceAsyncDownload]=%7B%7D&resource[resource][resource][keepOriginalFile]=%7B%7D&resource[resource][resource][keyPassphrase]=%7B%7D&resource[resource][resource][localFilePath]=%7B%7D&resource[resource][resource][objectId]=%7B%7D&resource[resource][resource][objectSubType]=%7B%7D&resource[resource][resource][objectType]=%7B%7D&resource[resource][resource][privateKey]=%7B%7D&resource[resource][resource][publicKey]=%7B%7D&resource[resource][resource][resources]=%7B%7D&resource[resource][resource][resource][assetId]=%7B%7D&resource[resource][resource][resource][content]=%7B%7D&resource[resource][resource][resource][dropFolderFileId]=%7B%7D&resource[resource][resource][resource][entryId]=%7B%7D&resource[resource][resource][resource][fileSyncObjectType]=%7B%7D&resource[resource][resource][resource][flavorParamsId]=%7B%7D&resource[resource][resource][resource][forceAsyncDownload]=%7B%7D&resource[resource][resource][resource][keepOriginalFile]=%7B%7D&resource[resource][resource][resource][keyPassphrase]=%7B%7D&resource[resource][resource][resource][localFilePath]=%7B%7D&resource[resource][resource][resource][objectId]=%7B%7D&resource[resource][resource][resource][objectSubType]=%7B%7D&resource[resource][resource][resource][objectType]=%7B%7D&resource[resource][resource][resource][privateKey]=%7B%7D&resource[resource][resource][resource][publicKey]=%7B%7D&resource[resource][resource][resource][resources]=%7B%7D&resource[resource][resource][resource][storageProfileId]=%7B%7D&resource[resource][resource][resource][token]=%7B%7D&resource[resource][resource][resource][url]=%7B%7D&resource[resource][resource][resource][version]=%7B%7D&resource[resource][resource][storageProfileId]=%7B%7D&resource[resource][resource][token]=%7B%7D&resource[resource][resource][url]=%7B%7D&resource[resource][resource][version]=%7B%7D&resource[resource][storageProfileId]=%7B%7D&resource[resource][token]=%7B%7D&resource[resource][url]=%7B%7D&resource[resource][version]=%7B%7D&resource[storageProfileId]=%7B%7D&resource[token]=%7B%7D&resource[url]=%7B%7D&resource[version]=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "resource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Attach content resource to entry in status NO_MEDIA"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "24d9fc25-b8ac-4869-a629-08e634fdc9ec"
            }
          ]
        },
        {
          "id": "c461153f-da50-43fe-82f7-a5d1f5110e33",
          "name": "baseEntry.updateContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/baseentry/action/updateContent?advancedOptions[keepManualThumbnails]=%7B%7D&advancedOptions[pluginOptionItems]=%7B%7D&conversionProfileId=%7B%7D&entryId=%7B%7D&No Name=%7B%7D&resource[assetId]=%7B%7D&resource[content]=%7B%7D&resource[dropFolderFileId]=%7B%7D&resource[entryId]=%7B%7D&resource[fileSyncObjectType]=%7B%7D&resource[flavorParamsId]=%7B%7D&resource[forceAsyncDownload]=%7B%7D&resource[keepOriginalFile]=%7B%7D&resource[keyPassphrase]=%7B%7D&resource[localFilePath]=%7B%7D&resource[objectId]=%7B%7D&resource[objectSubType]=%7B%7D&resource[objectType]=%7B%7D&resource[privateKey]=%7B%7D&resource[publicKey]=%7B%7D&resource[resources]=%7B%7D&resource[resource][assetId]=%7B%7D&resource[resource][content]=%7B%7D&resource[resource][dropFolderFileId]=%7B%7D&resource[resource][entryId]=%7B%7D&resource[resource][fileSyncObjectType]=%7B%7D&resource[resource][flavorParamsId]=%7B%7D&resource[resource][forceAsyncDownload]=%7B%7D&resource[resource][keepOriginalFile]=%7B%7D&resource[resource][keyPassphrase]=%7B%7D&resource[resource][localFilePath]=%7B%7D&resource[resource][objectId]=%7B%7D&resource[resource][objectSubType]=%7B%7D&resource[resource][objectType]=%7B%7D&resource[resource][privateKey]=%7B%7D&resource[resource][publicKey]=%7B%7D&resource[resource][resources]=%7B%7D&resource[resource][resource][assetId]=%7B%7D&resource[resource][resource][content]=%7B%7D&resource[resource][resource][dropFolderFileId]=%7B%7D&resource[resource][resource][entryId]=%7B%7D&resource[resource][resource][fileSyncObjectType]=%7B%7D&resource[resource][resource][flavorParamsId]=%7B%7D&resource[resource][resource][forceAsyncDownload]=%7B%7D&resource[resource][resource][keepOriginalFile]=%7B%7D&resource[resource][resource][keyPassphrase]=%7B%7D&resource[resource][resource][localFilePath]=%7B%7D&resource[resource][resource][objectId]=%7B%7D&resource[resource][resource][objectSubType]=%7B%7D&resource[resource][resource][objectType]=%7B%7D&resource[resource][resource][privateKey]=%7B%7D&resource[resource][resource][publicKey]=%7B%7D&resource[resource][resource][resources]=%7B%7D&resource[resource][resource][resource][assetId]=%7B%7D&resource[resource][resource][resource][content]=%7B%7D&resource[resource][resource][resource][dropFolderFileId]=%7B%7D&resource[resource][resource][resource][entryId]=%7B%7D&resource[resource][resource][resource][fileSyncObjectType]=%7B%7D&resource[resource][resource][resource][flavorParamsId]=%7B%7D&resource[resource][resource][resource][forceAsyncDownload]=%7B%7D&resource[resource][resource][resource][keepOriginalFile]=%7B%7D&resource[resource][resource][resource][keyPassphrase]=%7B%7D&resource[resource][resource][resource][localFilePath]=%7B%7D&resource[resource][resource][resource][objectId]=%7B%7D&resource[resource][resource][resource][objectSubType]=%7B%7D&resource[resource][resource][resource][objectType]=%7B%7D&resource[resource][resource][resource][privateKey]=%7B%7D&resource[resource][resource][resource][publicKey]=%7B%7D&resource[resource][resource][resource][resources]=%7B%7D&resource[resource][resource][resource][storageProfileId]=%7B%7D&resource[resource][resource][resource][token]=%7B%7D&resource[resource][resource][resource][url]=%7B%7D&resource[resource][resource][resource][version]=%7B%7D&resource[resource][resource][storageProfileId]=%7B%7D&resource[resource][resource][token]=%7B%7D&resource[resource][resource][url]=%7B%7D&resource[resource][resource][version]=%7B%7D&resource[resource][storageProfileId]=%7B%7D&resource[resource][token]=%7B%7D&resource[resource][url]=%7B%7D&resource[resource][version]=%7B%7D&resource[storageProfileId]=%7B%7D&resource[token]=%7B%7D&resource[url]=%7B%7D&resource[version]=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "resource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "resource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Update the content resource associated with the entry."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8493e7a4-6d9b-4dde-91c6-bf3ccadff59a"
            }
          ]
        },
        {
          "id": "3ab5bdfe-b424-470e-90cf-ba95933064fd",
          "name": "captionAsset.setContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/caption_captionasset/action/setContent?contentResource[assetId]=%7B%7D&contentResource[content]=%7B%7D&contentResource[dropFolderFileId]=%7B%7D&contentResource[entryId]=%7B%7D&contentResource[fileSyncObjectType]=%7B%7D&contentResource[flavorParamsId]=%7B%7D&contentResource[forceAsyncDownload]=%7B%7D&contentResource[keepOriginalFile]=%7B%7D&contentResource[keyPassphrase]=%7B%7D&contentResource[localFilePath]=%7B%7D&contentResource[objectId]=%7B%7D&contentResource[objectSubType]=%7B%7D&contentResource[objectType]=%7B%7D&contentResource[privateKey]=%7B%7D&contentResource[publicKey]=%7B%7D&contentResource[resources]=%7B%7D&contentResource[resource][assetId]=%7B%7D&contentResource[resource][content]=%7B%7D&contentResource[resource][dropFolderFileId]=%7B%7D&contentResource[resource][entryId]=%7B%7D&contentResource[resource][fileSyncObjectType]=%7B%7D&contentResource[resource][flavorParamsId]=%7B%7D&contentResource[resource][forceAsyncDownload]=%7B%7D&contentResource[resource][keepOriginalFile]=%7B%7D&contentResource[resource][keyPassphrase]=%7B%7D&contentResource[resource][localFilePath]=%7B%7D&contentResource[resource][objectId]=%7B%7D&contentResource[resource][objectSubType]=%7B%7D&contentResource[resource][objectType]=%7B%7D&contentResource[resource][privateKey]=%7B%7D&contentResource[resource][publicKey]=%7B%7D&contentResource[resource][resources]=%7B%7D&contentResource[resource][resource][assetId]=%7B%7D&contentResource[resource][resource][content]=%7B%7D&contentResource[resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][entryId]=%7B%7D&contentResource[resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][objectId]=%7B%7D&contentResource[resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][objectType]=%7B%7D&contentResource[resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][assetId]=%7B%7D&contentResource[resource][resource][resource][content]=%7B%7D&contentResource[resource][resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][resource][entryId]=%7B%7D&contentResource[resource][resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][resource][objectId]=%7B%7D&contentResource[resource][resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][resource][objectType]=%7B%7D&contentResource[resource][resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][resource][token]=%7B%7D&contentResource[resource][resource][resource][url]=%7B%7D&contentResource[resource][resource][resource][version]=%7B%7D&contentResource[resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][token]=%7B%7D&contentResource[resource][resource][url]=%7B%7D&contentResource[resource][resource][version]=%7B%7D&contentResource[resource][storageProfileId]=%7B%7D&contentResource[resource][token]=%7B%7D&contentResource[resource][url]=%7B%7D&contentResource[resource][version]=%7B%7D&contentResource[storageProfileId]=%7B%7D&contentResource[token]=%7B%7D&contentResource[url]=%7B%7D&contentResource[version]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "contentResource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Update content of caption asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "197cdc9f-7ac5-4810-bf2e-095c04307ec5"
            }
          ]
        },
        {
          "id": "b49f44cc-0ddd-4dcc-934f-80a099ed5280",
          "name": "contentDistributionBatch.createRequiredJobs",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_contentdistributionbatch/action/createRequiredJobs?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "creates all required jobs according to entry distribution dirty flags"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40e721d0-fa50-46ff-b036-40de349ad80d"
            }
          ]
        },
        {
          "id": "db12caae-9b43-4e1a-8444-57066382f2f6",
          "name": "contentDistributionBatch.getAssetUrl",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_contentdistributionbatch/action/getAssetUrl?assetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "returns absolute valid url for asset file"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e22a83a5-2ad7-4da2-8d17-5dcc5ffe2d9b"
            }
          ]
        },
        {
          "id": "b41d3ddd-1fa2-4d45-ad2a-8284e2286e3b",
          "name": "contentDistributionBatch.updateSunStatus",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_contentdistributionbatch/action/updateSunStatus?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "updates entry distribution sun status in the search engine"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2588440a-3510-4ec3-9e3e-f7a036843fc7"
            }
          ]
        },
        {
          "id": "dec049e8-242e-4aa9-8c58-195f47c26635",
          "name": "distributionProfile.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/add?distributionProfile[accountId]=%7B%7D&distributionProfile[adFreeApplicationGuid]=%7B%7D&distributionProfile[adServerPartnerId]=%7B%7D&distributionProfile[allowAdsenseForVideo]=%7B%7D&distributionProfile[allowComments]=%7B%7D&distributionProfile[allowDownload]=%7B%7D&distributionProfile[allowEmbedding]=%7B%7D&distributionProfile[allowInvideo]=%7B%7D&distributionProfile[allowMidRollAds]=%7B%7D&distributionProfile[allowPostRollAds]=%7B%7D&distributionProfile[allowPreRollAds]=%7B%7D&distributionProfile[allowRatings]=%7B%7D&distributionProfile[allowResponses]=%7B%7D&distributionProfile[allowStreaming]=%7B%7D&distributionProfile[allowSyndication]=%7B%7D&distributionProfile[apiAuthorizeUrl]=%7B%7D&distributionProfile[apiHostUrl]=%7B%7D&distributionProfile[apikey]=%7B%7D&distributionProfile[asperaHost]=%7B%7D&distributionProfile[asperaLogin]=%7B%7D&distributionProfile[asperaPass]=%7B%7D&distributionProfile[asperaPrivateKey]=%7B%7D&distributionProfile[asperaPublicKey]=%7B%7D&distributionProfile[assetFilenameXslt]=%7B%7D&distributionProfile[assumeSuccess]=%7B%7D&distributionProfile[autoCreateFlavors]=%7B%7D&distributionProfile[autoCreateThumb]=%7B%7D&distributionProfile[backgroundImageStandard]=%7B%7D&distributionProfile[backgroundImageWide]=%7B%7D&distributionProfile[basePath]=%7B%7D&distributionProfile[blockOutsideOwnership]=%7B%7D&distributionProfile[bodyXslt]=%7B%7D&distributionProfile[captionAutosync]=%7B%7D&distributionProfile[categoryId]=%7B%7D&distributionProfile[certificateKey]=%7B%7D&distributionProfile[channelCopyright]=%7B%7D&distributionProfile[channelDescription]=%7B%7D&distributionProfile[channelGenerator]=%7B%7D&distributionProfile[channelGuid]=%7B%7D&distributionProfile[channelImageHeight]=%7B%7D&distributionProfile[channelImageLink]=%7B%7D&distributionProfile[channelImageTitle]=%7B%7D&distributionProfile[channelImageUrl]=%7B%7D&distributionProfile[channelImageWidth]=%7B%7D&distributionProfile[channelLanguage]=%7B%7D&distributionProfile[channelLink]=%7B%7D&distributionProfile[channelManagingEditor]=%7B%7D&distributionProfile[channelRating]=%7B%7D&distributionProfile[channelTitle]=%7B%7D&distributionProfile[claimType]=%7B%7D&distributionProfile[commercialPolicy]=%7B%7D&distributionProfile[contactEmail]=%7B%7D&distributionProfile[contactTelephone]=%7B%7D&distributionProfile[contentOwner]=%7B%7D&distributionProfile[copyright]=%7B%7D&distributionProfile[cPlatformTvSeriesField]=%7B%7D&distributionProfile[cPlatformTvSeries]=%7B%7D&distributionProfile[csId]=%7B%7D&distributionProfile[cuePointsProvider]=%7B%7D&distributionProfile[defaultCategory]=%7B%7D&distributionProfile[deleteEnabled]=%7B%7D&distributionProfile[deleteReference]=%7B%7D&distributionProfile[disableEpisodeNumberCustomValidation]=%7B%7D&distributionProfile[disableMetadata]=%7B%7D&distributionProfile[distributeCaptions]=%7B%7D&distributionProfile[distributeCuePoints]=%7B%7D&distributionProfile[distributeRemoteCaptionAssetContent]=%7B%7D&distributionProfile[distributeRemoteFlavorAssetContent]=%7B%7D&distributionProfile[distributeRemoteThumbAssetContent]=%7B%7D&distributionProfile[domainGuid]=%7B%7D&distributionProfile[domainName]=%7B%7D&distributionProfile[domain]=%7B%7D&distributionProfile[downloadPriceCode]=%7B%7D&distributionProfile[email]=%7B%7D&distributionProfile[enableAdServer]=%7B%7D&distributionProfile[entitlements]=%7B%7D&distributionProfile[entitlement]=%7B%7D&distributionProfile[feedAuthorName]=%7B%7D&distributionProfile[feedCopyright]=%7B%7D&distributionProfile[feedDescription]=%7B%7D&distributionProfile[feedImageHeight]=%7B%7D&distributionProfile[feedImageLink]=%7B%7D&distributionProfile[feedImageTitle]=%7B%7D&distributionProfile[feedImageUrl]=%7B%7D&distributionProfile[feedImageWidth]=%7B%7D&distributionProfile[feedLanguage]=%7B%7D&distributionProfile[feedLastBuildDate]=%7B%7D&distributionProfile[feedLink]=%7B%7D&distributionProfile[feedSpecVersion]=%7B%7D&distributionProfile[feedSubtitle]=%7B%7D&distributionProfile[feedTitle]=%7B%7D&distributionProfile[fieldConfigArray]=%7B%7D&distributionProfile[flavorAssetFilenameXslt]=%7B%7D&distributionProfile[flvFlavorParamsId]=%7B%7D&distributionProfile[ftpHost]=%7B%7D&distributionProfile[ftpLogin]=%7B%7D&distributionProfile[ftpPassword]=%7B%7D&distributionProfile[ftpPass]=%7B%7D&distributionProfile[ftpPath]=%7B%7D&distributionProfile[ftpUsername]=%7B%7D&distributionProfile[genericProviderId]=%7B%7D&distributionProfile[geoBlockingMapping]=%7B%7D&distributionProfile[googleClientId]=%7B%7D&distributionProfile[googleClientSecret]=%7B%7D&distributionProfile[googleTokenData]=%7B%7D&distributionProfile[hideViewCount]=%7B%7D&distributionProfile[host]=%7B%7D&distributionProfile[ignoreSchedulingInFeed]=%7B%7D&distributionProfile[ingestUrl]=%7B%7D&distributionProfile[instreamStandard]=%7B%7D&distributionProfile[instreamTrueview]=%7B%7D&distributionProfile[ips]=%7B%7D&distributionProfile[itemLink]=%7B%7D&distributionProfile[itemMediaRating]=%7B%7D&distributionProfile[itemsPerPage]=%7B%7D&distributionProfile[itemType]=%7B%7D&distributionProfile[itemXpathsToExtend]=%7B%7D&distributionProfile[mapAccessControlProfileIds]=%7B%7D&distributionProfile[mapCaptionParamsIds]=%7B%7D&distributionProfile[mapConversionProfileIds]=%7B%7D&distributionProfile[mapFlavorParamsIds]=%7B%7D&distributionProfile[mapMetadataProfileIds]=%7B%7D&distributionProfile[mapStorageProfileIds]=%7B%7D&distributionProfile[mapThumbParamsIds]=%7B%7D&distributionProfile[metadataFilenameXslt]=%7B%7D&distributionProfile[metadataProfileId]=%7B%7D&distributionProfile[metadataXpathsTriggerUpdate]=%7B%7D&distributionProfile[metadataXslt]=%7B%7D&distributionProfile[msnvideoCat]=%7B%7D&distributionProfile[msnvideoTopCat]=%7B%7D&distributionProfile[msnvideoTop]=%7B%7D&distributionProfile[name]=%7B%7D&distributionProfile[notificationEmail]=%7B%7D&distributionProfile[objectType]=%7B%7D&distributionProfile[optionalAssetDistributionRules]=%7B%7D&distributionProfile[optionalFlavorParamsIds]=%7B%7D&distributionProfile[optionalThumbDimensions]=%7B%7D&distributionProfile[overrideManualEdits]=%7B%7D&distributionProfile[ownerName]=%7B%7D&distributionProfile[pageAccessToken]=%7B%7D&distributionProfile[pageGroup]=%7B%7D&distributionProfile[pageId]=%7B%7D&distributionProfile[passphrase]=%7B%7D&distributionProfile[password]=%7B%7D&distributionProfile[permissions]=%7B%7D&distributionProfile[port]=%7B%7D&distributionProfile[priority]=%7B%7D&distributionProfile[privacyStatus]=%7B%7D&distributionProfile[processFeed]=%7B%7D&distributionProfile[protocol]=%7B%7D&distributionProfile[providerId]=%7B%7D&distributionProfile[providerName]=%7B%7D&distributionProfile[providerType]=%7B%7D&distributionProfile[rating]=%7B%7D&distributionProfile[recommendedDcForDownload]=%7B%7D&distributionProfile[recommendedDcForExecute]=%7B%7D&distributionProfile[recommendedStorageProfileForDownload]=%7B%7D&distributionProfile[releaseClaims]=%7B%7D&distributionProfile[remoteAssetParamsId]=%7B%7D&distributionProfile[replaceAirDates]=%7B%7D&distributionProfile[replaceGroup]=%7B%7D&distributionProfile[reportEnabled]=%7B%7D&distributionProfile[requiredAssetDistributionRules]=%7B%7D&distributionProfile[requiredFlavorParamsIds]=%7B%7D&distributionProfile[requiredThumbDimensions]=%7B%7D&distributionProfile[reRequestPermissions]=%7B%7D&distributionProfile[seasonNumber]=%7B%7D&distributionProfile[seasonSynopsis]=%7B%7D&distributionProfile[seasonTuneInInformation]=%7B%7D&distributionProfile[sendMetadataAfterAssets]=%7B%7D&distributionProfile[seriesAdditionalCategories]=%7B%7D&distributionProfile[seriesChannel]=%7B%7D&distributionProfile[seriesPrimaryCategory]=%7B%7D&distributionProfile[sftpBaseDir]=%7B%7D&distributionProfile[sftpBasePath]=%7B%7D&distributionProfile[sftpHost]=%7B%7D&distributionProfile[sftpLogin]=%7B%7D&distributionProfile[sftpPass]=%7B%7D&distributionProfile[sftpPort]=%7B%7D&distributionProfile[sftpPrivateKey]=%7B%7D&distributionProfile[sftpPublicKey]=%7B%7D&distributionProfile[shouldAddThumbExtension]=%7B%7D&distributionProfile[shouldIncludeCaptions]=%7B%7D&distributionProfile[shouldIncludeCuePoints]=%7B%7D&distributionProfile[slFlavorParamsId]=%7B%7D&distributionProfile[slHdFlavorParamsId]=%7B%7D&distributionProfile[sourceFlavorParamsId]=%7B%7D&distributionProfile[sourceFriendlyName]=%7B%7D&distributionProfile[source]=%7B%7D&distributionProfile[state]=%7B%7D&distributionProfile[status]=%7B%7D&distributionProfile[storageProfileId]=%7B%7D&distributionProfile[streamingPriceCode]=%7B%7D&distributionProfile[strict]=%7B%7D&distributionProfile[submitAction][ftpPassiveMode]=%7B%7D&distributionProfile[submitAction][httpFieldName]=%7B%7D&distributionProfile[submitAction][httpFileName]=%7B%7D&distributionProfile[submitAction][password]=%7B%7D&distributionProfile[submitAction][protocol]=%7B%7D&distributionProfile[submitAction][serverPath]=%7B%7D&distributionProfile[submitAction][serverUrl]=%7B%7D&distributionProfile[submitAction][username]=%7B%7D&distributionProfile[submitEnabled]=%7B%7D&distributionProfile[sunriseDefaultOffset]=%7B%7D&distributionProfile[sunsetDefaultOffset]=%7B%7D&distributionProfile[tags]=%7B%7D&distributionProfile[targetAccountId]=%7B%7D&distributionProfile[targetLoginId]=%7B%7D&distributionProfile[targetLoginPassword]=%7B%7D&distributionProfile[targetServiceUrl]=%7B%7D&distributionProfile[target]=%7B%7D&distributionProfile[thumbnailAssetFilenameXslt]=%7B%7D&distributionProfile[ugcPolicy]=%7B%7D&distributionProfile[updateEnabled]=%7B%7D&distributionProfile[upstreamNetworkId]=%7B%7D&distributionProfile[upstreamNetworkName]=%7B%7D&distributionProfile[upstreamVideoId]=%7B%7D&distributionProfile[urgentReference]=%7B%7D&distributionProfile[useCategoryEntries]=%7B%7D&distributionProfile[userAccessToken]=%7B%7D&distributionProfile[username]=%7B%7D&distributionProfile[user]=%7B%7D&distributionProfile[videoMediaType]=%7B%7D&distributionProfile[wmvFlavorParamsId]=%7B%7D&distributionProfile[xsltFile]=%7B%7D&distributionProfile[xsl]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Distribution Profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "82deaf28-b5de-45f0-a590-b28fee546f53"
            }
          ]
        }
      ]
    }
  ]
}