{
  "info": {
    "name": "Kaltura VPaaS Get Service Contentdistribution Genericdistributionproveraction Action Addresultstransform",
    "_postman_id": "e7a4d4c4-4edc-436f-946d-252f8c2e73fa",
    "description": "Add results transform file to generic distribution provider action",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "02f497be-a60c-4ed0-b6b1-1b882f4b247c",
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
              "id": "1eea7a2b-6163-4590-8536-ee91e981e31d"
            }
          ]
        },
        {
          "id": "c4849665-c5b0-4731-b821-007985dd34fa",
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
              "id": "2792783d-a970-4f86-aaad-852b0a407d26"
            }
          ]
        },
        {
          "id": "48bdebce-7261-400e-b1d2-c345872e5fa1",
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
              "id": "8acbf6aa-b266-4a87-99b2-973514dbe56b"
            }
          ]
        },
        {
          "id": "c87964f5-38c0-4800-9702-5d8638cc4e29",
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
              "id": "378492d6-ecfc-44c5-85cf-9e465adc1c57"
            }
          ]
        },
        {
          "id": "6d58f60a-57fd-4d36-8f46-091ba5426f0d",
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
              "id": "f478f975-73e5-4679-b425-52998cad241b"
            }
          ]
        },
        {
          "id": "f896c732-4fff-42ff-9a4e-f4fecad5eeb5",
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
              "id": "ff45e58b-1eb7-4798-8b76-7e9c2e77459d"
            }
          ]
        },
        {
          "id": "83df8ed3-037d-428c-9112-29997ae8ac97",
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
              "id": "1c31aaaa-a646-453a-851f-ef6ece509734"
            }
          ]
        },
        {
          "id": "04930ce2-b251-4494-8929-0229d511de7c",
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
              "id": "98125e33-d426-48d1-b8cd-67395ce665ed"
            }
          ]
        },
        {
          "id": "c6512827-52b0-42ed-9830-a5b9924acda2",
          "name": "distributionProfile.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Distribution Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9da3ea33-5143-4d48-bd24-2b456f278bd0"
            }
          ]
        },
        {
          "id": "979e85a8-87ba-478c-866b-dfceee04c9c8",
          "name": "distributionProfile.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Distribution Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d6559b71-099b-4bd8-8203-c2121d1ca0fd"
            }
          ]
        },
        {
          "id": "f230da3d-428b-4244-8554-6b926e448c2d",
          "name": "distributionProfile.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all distribution providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a7679991-77be-4e8c-8cd7-40695c9b32dd"
            }
          ]
        },
        {
          "id": "377bc516-3dbe-46a4-9e9d-b596f769a8f3",
          "name": "distributionProfile.listByPartner",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/listByPartner?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[groupTypeEq]=%7B%7D&filter[groupTypeIn]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[idNotIn]=%7B%7D&filter[nameEqual]=%7B%7D&filter[nameLike]=%7B%7D&filter[nameMultiLikeAnd]=%7B%7D&filter[nameMultiLikeOr]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerGroupTypeEqual]=%7B%7D&filter[partnerNameDescriptionWebsiteAdminNameAdminEmailLike]=%7B%7D&filter[partnerPackageEqual]=%7B%7D&filter[partnerPackageGreaterThanOrEqual]=%7B%7D&filter[partnerPackageIn]=%7B%7D&filter[partnerPackageLessThanOrEqual]=%7B%7D&filter[partnerPermissionsExist]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Contentdistribution Distributionprofile Action Listbypartner"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90427ff0-192b-4a18-994e-12f0385edd7a"
            }
          ]
        },
        {
          "id": "1db1b3e6-4922-4eec-aeab-70533019b900",
          "name": "distributionProfile.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/update?distributionProfile[accountId]=%7B%7D&distributionProfile[adFreeApplicationGuid]=%7B%7D&distributionProfile[adServerPartnerId]=%7B%7D&distributionProfile[allowAdsenseForVideo]=%7B%7D&distributionProfile[allowComments]=%7B%7D&distributionProfile[allowDownload]=%7B%7D&distributionProfile[allowEmbedding]=%7B%7D&distributionProfile[allowInvideo]=%7B%7D&distributionProfile[allowMidRollAds]=%7B%7D&distributionProfile[allowPostRollAds]=%7B%7D&distributionProfile[allowPreRollAds]=%7B%7D&distributionProfile[allowRatings]=%7B%7D&distributionProfile[allowResponses]=%7B%7D&distributionProfile[allowStreaming]=%7B%7D&distributionProfile[allowSyndication]=%7B%7D&distributionProfile[apiAuthorizeUrl]=%7B%7D&distributionProfile[apiHostUrl]=%7B%7D&distributionProfile[apikey]=%7B%7D&distributionProfile[asperaHost]=%7B%7D&distributionProfile[asperaLogin]=%7B%7D&distributionProfile[asperaPass]=%7B%7D&distributionProfile[asperaPrivateKey]=%7B%7D&distributionProfile[asperaPublicKey]=%7B%7D&distributionProfile[assetFilenameXslt]=%7B%7D&distributionProfile[assumeSuccess]=%7B%7D&distributionProfile[autoCreateFlavors]=%7B%7D&distributionProfile[autoCreateThumb]=%7B%7D&distributionProfile[backgroundImageStandard]=%7B%7D&distributionProfile[backgroundImageWide]=%7B%7D&distributionProfile[basePath]=%7B%7D&distributionProfile[blockOutsideOwnership]=%7B%7D&distributionProfile[bodyXslt]=%7B%7D&distributionProfile[captionAutosync]=%7B%7D&distributionProfile[categoryId]=%7B%7D&distributionProfile[certificateKey]=%7B%7D&distributionProfile[channelCopyright]=%7B%7D&distributionProfile[channelDescription]=%7B%7D&distributionProfile[channelGenerator]=%7B%7D&distributionProfile[channelGuid]=%7B%7D&distributionProfile[channelImageHeight]=%7B%7D&distributionProfile[channelImageLink]=%7B%7D&distributionProfile[channelImageTitle]=%7B%7D&distributionProfile[channelImageUrl]=%7B%7D&distributionProfile[channelImageWidth]=%7B%7D&distributionProfile[channelLanguage]=%7B%7D&distributionProfile[channelLink]=%7B%7D&distributionProfile[channelManagingEditor]=%7B%7D&distributionProfile[channelRating]=%7B%7D&distributionProfile[channelTitle]=%7B%7D&distributionProfile[claimType]=%7B%7D&distributionProfile[commercialPolicy]=%7B%7D&distributionProfile[contactEmail]=%7B%7D&distributionProfile[contactTelephone]=%7B%7D&distributionProfile[contentOwner]=%7B%7D&distributionProfile[copyright]=%7B%7D&distributionProfile[cPlatformTvSeriesField]=%7B%7D&distributionProfile[cPlatformTvSeries]=%7B%7D&distributionProfile[csId]=%7B%7D&distributionProfile[cuePointsProvider]=%7B%7D&distributionProfile[defaultCategory]=%7B%7D&distributionProfile[deleteEnabled]=%7B%7D&distributionProfile[deleteReference]=%7B%7D&distributionProfile[disableEpisodeNumberCustomValidation]=%7B%7D&distributionProfile[disableMetadata]=%7B%7D&distributionProfile[distributeCaptions]=%7B%7D&distributionProfile[distributeCuePoints]=%7B%7D&distributionProfile[distributeRemoteCaptionAssetContent]=%7B%7D&distributionProfile[distributeRemoteFlavorAssetContent]=%7B%7D&distributionProfile[distributeRemoteThumbAssetContent]=%7B%7D&distributionProfile[domainGuid]=%7B%7D&distributionProfile[domainName]=%7B%7D&distributionProfile[domain]=%7B%7D&distributionProfile[downloadPriceCode]=%7B%7D&distributionProfile[email]=%7B%7D&distributionProfile[enableAdServer]=%7B%7D&distributionProfile[entitlements]=%7B%7D&distributionProfile[entitlement]=%7B%7D&distributionProfile[feedAuthorName]=%7B%7D&distributionProfile[feedCopyright]=%7B%7D&distributionProfile[feedDescription]=%7B%7D&distributionProfile[feedImageHeight]=%7B%7D&distributionProfile[feedImageLink]=%7B%7D&distributionProfile[feedImageTitle]=%7B%7D&distributionProfile[feedImageUrl]=%7B%7D&distributionProfile[feedImageWidth]=%7B%7D&distributionProfile[feedLanguage]=%7B%7D&distributionProfile[feedLastBuildDate]=%7B%7D&distributionProfile[feedLink]=%7B%7D&distributionProfile[feedSpecVersion]=%7B%7D&distributionProfile[feedSubtitle]=%7B%7D&distributionProfile[feedTitle]=%7B%7D&distributionProfile[fieldConfigArray]=%7B%7D&distributionProfile[flavorAssetFilenameXslt]=%7B%7D&distributionProfile[flvFlavorParamsId]=%7B%7D&distributionProfile[ftpHost]=%7B%7D&distributionProfile[ftpLogin]=%7B%7D&distributionProfile[ftpPassword]=%7B%7D&distributionProfile[ftpPass]=%7B%7D&distributionProfile[ftpPath]=%7B%7D&distributionProfile[ftpUsername]=%7B%7D&distributionProfile[genericProviderId]=%7B%7D&distributionProfile[geoBlockingMapping]=%7B%7D&distributionProfile[googleClientId]=%7B%7D&distributionProfile[googleClientSecret]=%7B%7D&distributionProfile[googleTokenData]=%7B%7D&distributionProfile[hideViewCount]=%7B%7D&distributionProfile[host]=%7B%7D&distributionProfile[ignoreSchedulingInFeed]=%7B%7D&distributionProfile[ingestUrl]=%7B%7D&distributionProfile[instreamStandard]=%7B%7D&distributionProfile[instreamTrueview]=%7B%7D&distributionProfile[ips]=%7B%7D&distributionProfile[itemLink]=%7B%7D&distributionProfile[itemMediaRating]=%7B%7D&distributionProfile[itemsPerPage]=%7B%7D&distributionProfile[itemType]=%7B%7D&distributionProfile[itemXpathsToExtend]=%7B%7D&distributionProfile[mapAccessControlProfileIds]=%7B%7D&distributionProfile[mapCaptionParamsIds]=%7B%7D&distributionProfile[mapConversionProfileIds]=%7B%7D&distributionProfile[mapFlavorParamsIds]=%7B%7D&distributionProfile[mapMetadataProfileIds]=%7B%7D&distributionProfile[mapStorageProfileIds]=%7B%7D&distributionProfile[mapThumbParamsIds]=%7B%7D&distributionProfile[metadataFilenameXslt]=%7B%7D&distributionProfile[metadataProfileId]=%7B%7D&distributionProfile[metadataXpathsTriggerUpdate]=%7B%7D&distributionProfile[metadataXslt]=%7B%7D&distributionProfile[msnvideoCat]=%7B%7D&distributionProfile[msnvideoTopCat]=%7B%7D&distributionProfile[msnvideoTop]=%7B%7D&distributionProfile[name]=%7B%7D&distributionProfile[notificationEmail]=%7B%7D&distributionProfile[objectType]=%7B%7D&distributionProfile[optionalAssetDistributionRules]=%7B%7D&distributionProfile[optionalFlavorParamsIds]=%7B%7D&distributionProfile[optionalThumbDimensions]=%7B%7D&distributionProfile[overrideManualEdits]=%7B%7D&distributionProfile[ownerName]=%7B%7D&distributionProfile[pageAccessToken]=%7B%7D&distributionProfile[pageGroup]=%7B%7D&distributionProfile[pageId]=%7B%7D&distributionProfile[passphrase]=%7B%7D&distributionProfile[password]=%7B%7D&distributionProfile[permissions]=%7B%7D&distributionProfile[port]=%7B%7D&distributionProfile[priority]=%7B%7D&distributionProfile[privacyStatus]=%7B%7D&distributionProfile[processFeed]=%7B%7D&distributionProfile[protocol]=%7B%7D&distributionProfile[providerId]=%7B%7D&distributionProfile[providerName]=%7B%7D&distributionProfile[providerType]=%7B%7D&distributionProfile[rating]=%7B%7D&distributionProfile[recommendedDcForDownload]=%7B%7D&distributionProfile[recommendedDcForExecute]=%7B%7D&distributionProfile[recommendedStorageProfileForDownload]=%7B%7D&distributionProfile[releaseClaims]=%7B%7D&distributionProfile[remoteAssetParamsId]=%7B%7D&distributionProfile[replaceAirDates]=%7B%7D&distributionProfile[replaceGroup]=%7B%7D&distributionProfile[reportEnabled]=%7B%7D&distributionProfile[requiredAssetDistributionRules]=%7B%7D&distributionProfile[requiredFlavorParamsIds]=%7B%7D&distributionProfile[requiredThumbDimensions]=%7B%7D&distributionProfile[reRequestPermissions]=%7B%7D&distributionProfile[seasonNumber]=%7B%7D&distributionProfile[seasonSynopsis]=%7B%7D&distributionProfile[seasonTuneInInformation]=%7B%7D&distributionProfile[sendMetadataAfterAssets]=%7B%7D&distributionProfile[seriesAdditionalCategories]=%7B%7D&distributionProfile[seriesChannel]=%7B%7D&distributionProfile[seriesPrimaryCategory]=%7B%7D&distributionProfile[sftpBaseDir]=%7B%7D&distributionProfile[sftpBasePath]=%7B%7D&distributionProfile[sftpHost]=%7B%7D&distributionProfile[sftpLogin]=%7B%7D&distributionProfile[sftpPass]=%7B%7D&distributionProfile[sftpPort]=%7B%7D&distributionProfile[sftpPrivateKey]=%7B%7D&distributionProfile[sftpPublicKey]=%7B%7D&distributionProfile[shouldAddThumbExtension]=%7B%7D&distributionProfile[shouldIncludeCaptions]=%7B%7D&distributionProfile[shouldIncludeCuePoints]=%7B%7D&distributionProfile[slFlavorParamsId]=%7B%7D&distributionProfile[slHdFlavorParamsId]=%7B%7D&distributionProfile[sourceFlavorParamsId]=%7B%7D&distributionProfile[sourceFriendlyName]=%7B%7D&distributionProfile[source]=%7B%7D&distributionProfile[state]=%7B%7D&distributionProfile[status]=%7B%7D&distributionProfile[storageProfileId]=%7B%7D&distributionProfile[streamingPriceCode]=%7B%7D&distributionProfile[strict]=%7B%7D&distributionProfile[submitAction][ftpPassiveMode]=%7B%7D&distributionProfile[submitAction][httpFieldName]=%7B%7D&distributionProfile[submitAction][httpFileName]=%7B%7D&distributionProfile[submitAction][password]=%7B%7D&distributionProfile[submitAction][protocol]=%7B%7D&distributionProfile[submitAction][serverPath]=%7B%7D&distributionProfile[submitAction][serverUrl]=%7B%7D&distributionProfile[submitAction][username]=%7B%7D&distributionProfile[submitEnabled]=%7B%7D&distributionProfile[sunriseDefaultOffset]=%7B%7D&distributionProfile[sunsetDefaultOffset]=%7B%7D&distributionProfile[tags]=%7B%7D&distributionProfile[targetAccountId]=%7B%7D&distributionProfile[targetLoginId]=%7B%7D&distributionProfile[targetLoginPassword]=%7B%7D&distributionProfile[targetServiceUrl]=%7B%7D&distributionProfile[target]=%7B%7D&distributionProfile[thumbnailAssetFilenameXslt]=%7B%7D&distributionProfile[ugcPolicy]=%7B%7D&distributionProfile[updateEnabled]=%7B%7D&distributionProfile[upstreamNetworkId]=%7B%7D&distributionProfile[upstreamNetworkName]=%7B%7D&distributionProfile[upstreamVideoId]=%7B%7D&distributionProfile[urgentReference]=%7B%7D&distributionProfile[useCategoryEntries]=%7B%7D&distributionProfile[userAccessToken]=%7B%7D&distributionProfile[username]=%7B%7D&distributionProfile[user]=%7B%7D&distributionProfile[videoMediaType]=%7B%7D&distributionProfile[wmvFlavorParamsId]=%7B%7D&distributionProfile[xsltFile]=%7B%7D&distributionProfile[xsl]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Distribution Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d5f0ee1-64c6-4eb8-99f8-bc7235a9c749"
            }
          ]
        },
        {
          "id": "6c9e1fe9-b779-4737-b2f8-6ddb9e012b2f",
          "name": "distributionProfile.updateStatus",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprofile/action/updateStatus?id=%7B%7D&No Name=%7B%7D&status=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Distribution Profile status by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "482fb414-800b-4c2a-8ea2-10619a416bc5"
            }
          ]
        },
        {
          "id": "918d3bee-317a-41e0-8f93-fef9c6cc74ed",
          "name": "distributionProvider.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_distributionprovider/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isDefaultEqual]=%7B%7D&filter[isDefaultIn]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[typeEqual]=%7B%7D&filter[typeIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all distribution providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50c11a30-5164-46f9-9c8e-122dfa6b8033"
            }
          ]
        },
        {
          "id": "46863463-69c3-4ed1-95d9-d61f028e0aee",
          "name": "entryDistribution.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/add?entryDistribution[assetIds]=%7B%7D&entryDistribution[distributionProfileId]=%7B%7D&entryDistribution[entryId]=%7B%7D&entryDistribution[flavorAssetIds]=%7B%7D&entryDistribution[sunrise]=%7B%7D&entryDistribution[sunset]=%7B%7D&entryDistribution[thumbAssetIds]=%7B%7D&entryDistribution[validationErrors]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Entry Distribution"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1fd68cbc-aff6-4d61-a0fe-4329c583a116"
            }
          ]
        },
        {
          "id": "99b8e9a2-49dd-4e0f-947b-a363525359bf",
          "name": "entryDistribution.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Entry Distribution by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "57793f91-1333-4c76-b3fe-b540e7fdd4be"
            }
          ]
        },
        {
          "id": "95298fc0-ee0e-4991-a800-20d8a5deb0c5",
          "name": "entryDistribution.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Entry Distribution by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c8178d6-ff6a-4535-baaa-ffa8dafc69f1"
            }
          ]
        },
        {
          "id": "51f71082-ecd9-4b94-9455-24633f290726",
          "name": "entryDistribution.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[dirtyStatusEqual]=%7B%7D&filter[dirtyStatusIn]=%7B%7D&filter[distributionProfileIdEqual]=%7B%7D&filter[distributionProfileIdIn]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[submittedAtGreaterThanOrEqual]=%7B%7D&filter[submittedAtLessThanOrEqual]=%7B%7D&filter[sunriseGreaterThanOrEqual]=%7B%7D&filter[sunriseLessThanOrEqual]=%7B%7D&filter[sunsetGreaterThanOrEqual]=%7B%7D&filter[sunsetLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all distribution providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bd1198f7-12e7-4714-a450-9dc99b81f23b"
            }
          ]
        },
        {
          "id": "00caae91-da46-4178-9cae-ab9ff413af4f",
          "name": "entryDistribution.retrySubmit",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/retrySubmit?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retries last submit action"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "30a385f5-daff-4458-b3da-60dbfacab8d6"
            }
          ]
        },
        {
          "id": "90ca5669-9d99-4a14-859c-293cdea38b70",
          "name": "entryDistribution.serveReturnedData",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/serveReturnedData?actionType=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Serves entry distribution returned data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e602b48a-f0f6-4f3b-940d-5e2f0ec40680"
            }
          ]
        },
        {
          "id": "e40c6984-d559-49f4-8c10-bf5b7ca466ea",
          "name": "entryDistribution.serveSentData",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/serveSentData?actionType=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Serves entry distribution sent data"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb6e2d3b-cff3-44b5-baac-a250a3f2ce39"
            }
          ]
        },
        {
          "id": "d4ef27ce-b86a-4279-aa80-ebc704a79683",
          "name": "entryDistribution.submitAdd",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/submitAdd?id=%7B%7D&No Name=%7B%7D&submitWhenReady=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Submits Entry Distribution to the remote destination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "432378e3-121c-4ca7-8342-0b575cabd0c6"
            }
          ]
        },
        {
          "id": "793896a7-8445-47d6-b6ac-583bc16761b5",
          "name": "entryDistribution.submitDelete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/submitDelete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes Entry Distribution from the remote destination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45338d08-fe98-4531-83ab-69bb68eb6369"
            }
          ]
        },
        {
          "id": "166a1cb5-556a-4955-b77f-0202b47237b7",
          "name": "entryDistribution.submitFetchReport",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/submitFetchReport?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Submits Entry Distribution report request"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f6315f1d-0004-4c73-b5ad-ee7f664d81d7"
            }
          ]
        },
        {
          "id": "84c208b0-5ebd-4fdd-9a1e-4e962b34638f",
          "name": "entryDistribution.submitUpdate",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/submitUpdate?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Submits Entry Distribution changes to the remote destination"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69664cb6-a817-4bf4-b8d1-5c81ea09767d"
            }
          ]
        },
        {
          "id": "a689df3e-7b08-4d6f-96f0-41fed2330c79",
          "name": "entryDistribution.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/update?entryDistribution[assetIds]=%7B%7D&entryDistribution[distributionProfileId]=%7B%7D&entryDistribution[entryId]=%7B%7D&entryDistribution[flavorAssetIds]=%7B%7D&entryDistribution[sunrise]=%7B%7D&entryDistribution[sunset]=%7B%7D&entryDistribution[thumbAssetIds]=%7B%7D&entryDistribution[validationErrors]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Entry Distribution by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e281a607-27a4-47d5-94ce-7d31bd796fc3"
            }
          ]
        },
        {
          "id": "7d96c2e2-4140-4fb8-ad3a-de7d6299ce83",
          "name": "entryDistribution.validate",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_entrydistribution/action/validate?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Validates Entry Distribution by id for submission"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ae6f9db-f35d-4c9b-93e2-ee8e4fcf3589"
            }
          ]
        },
        {
          "id": "c4fb7a1a-cdfe-4906-bc7e-a7c8f3749af7",
          "name": "genericDistributionProvider.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovider/action/add?genericDistributionProvider[availabilityUpdateEnabled]=%7B%7D&genericDistributionProvider[deleteInsteadUpdate]=%7B%7D&genericDistributionProvider[editableFields]=%7B%7D&genericDistributionProvider[intervalBeforeSunrise]=%7B%7D&genericDistributionProvider[intervalBeforeSunset]=%7B%7D&genericDistributionProvider[isDefault]=%7B%7D&genericDistributionProvider[mandatoryFields]=%7B%7D&genericDistributionProvider[name]=%7B%7D&genericDistributionProvider[optionalFlavorParamsIds]=%7B%7D&genericDistributionProvider[optionalThumbDimensions]=%7B%7D&genericDistributionProvider[requiredFlavorParamsIds]=%7B%7D&genericDistributionProvider[requiredThumbDimensions]=%7B%7D&genericDistributionProvider[scheduleUpdateEnabled]=%7B%7D&genericDistributionProvider[updateRequiredEntryFields]=%7B%7D&genericDistributionProvider[updateRequiredMetadataXPaths]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Generic Distribution Provider"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "32ce6e24-0d0d-435c-8780-5fbd6a34ca29"
            }
          ]
        },
        {
          "id": "192019dd-d5e7-4d2e-ad93-125eaeb720bd",
          "name": "genericDistributionProvider.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovider/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Generic Distribution Provider by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ef4efd4f-23a8-429c-8277-928296478411"
            }
          ]
        },
        {
          "id": "0232f6b6-8541-4ce0-85e2-97071eeb40e5",
          "name": "genericDistributionProvider.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovider/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Generic Distribution Provider by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4a71dd08-f78a-4c7b-8731-0738be7b3d89"
            }
          ]
        },
        {
          "id": "abd7d0e5-d09b-428c-b4ff-b4c2b1dfa2a0",
          "name": "genericDistributionProvider.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovider/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isDefaultEqual]=%7B%7D&filter[isDefaultIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[typeEqual]=%7B%7D&filter[typeIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all distribution providers"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b34cdf44-16f0-44d1-a8f8-ca23a6f68b18"
            }
          ]
        },
        {
          "id": "f81a8fbb-99ed-4b2f-9a69-1c8833a23226",
          "name": "genericDistributionProvider.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovider/action/update?genericDistributionProvider[availabilityUpdateEnabled]=%7B%7D&genericDistributionProvider[deleteInsteadUpdate]=%7B%7D&genericDistributionProvider[editableFields]=%7B%7D&genericDistributionProvider[intervalBeforeSunrise]=%7B%7D&genericDistributionProvider[intervalBeforeSunset]=%7B%7D&genericDistributionProvider[isDefault]=%7B%7D&genericDistributionProvider[mandatoryFields]=%7B%7D&genericDistributionProvider[name]=%7B%7D&genericDistributionProvider[optionalFlavorParamsIds]=%7B%7D&genericDistributionProvider[optionalThumbDimensions]=%7B%7D&genericDistributionProvider[requiredFlavorParamsIds]=%7B%7D&genericDistributionProvider[requiredThumbDimensions]=%7B%7D&genericDistributionProvider[scheduleUpdateEnabled]=%7B%7D&genericDistributionProvider[updateRequiredEntryFields]=%7B%7D&genericDistributionProvider[updateRequiredMetadataXPaths]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Generic Distribution Provider by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "40e1541e-dcc9-413a-b660-56d066ddc236"
            }
          ]
        },
        {
          "id": "80dc25e7-e32c-4ce9-8714-a2be84fede0b",
          "name": "genericDistributionProviderAction.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovideraction/action/add?genericDistributionProviderAction[action]=%7B%7D&genericDistributionProviderAction[editableFields]=%7B%7D&genericDistributionProviderAction[genericDistributionProviderId]=%7B%7D&genericDistributionProviderAction[mandatoryFields]=%7B%7D&genericDistributionProviderAction[protocol]=%7B%7D&genericDistributionProviderAction[remotePassword]=%7B%7D&genericDistributionProviderAction[remotePath]=%7B%7D&genericDistributionProviderAction[remoteUsername]=%7B%7D&genericDistributionProviderAction[resultsParser]=%7B%7D&genericDistributionProviderAction[serverAddress]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Generic Distribution Provider Action"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b57cc6a7-1e85-4405-a084-a4ebfdad5d47"
            }
          ]
        },
        {
          "id": "de31a21a-3938-4974-b24d-0523003489ab",
          "name": "genericDistributionProviderAction.addMrssTransform",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovideraction/action/addMrssTransform?id=%7B%7D&No Name=%7B%7D&xslData=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add MRSS transform file to generic distribution provider action"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "13f31e39-2191-49f6-a4b5-e7ddc469562e"
            }
          ]
        },
        {
          "id": "acab0845-c798-49f6-a7ce-7d9c16a0a006",
          "name": "genericDistributionProviderAction.addMrssTransformFromFile",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovideraction/action/addMrssTransformFromFile?id=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "xslFile",
                  "value": "{}",
                  "disabled": false,
                  "description": "XSL MRSS transformation file"
                }
              ]
            },
            "description": "Add MRSS transform file to generic distribution provider action"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31738324-b8eb-43a9-82d6-c28752bdbf72"
            }
          ]
        },
        {
          "id": "5f6a5393-19dd-44ba-a1ae-1549d82a2ef9",
          "name": "genericDistributionProviderAction.addMrssValidate",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovideraction/action/addMrssValidate?id=%7B%7D&No Name=%7B%7D&xsdData=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add MRSS validate file to generic distribution provider action"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d881b831-bacb-40c0-82b7-c84a91df4593"
            }
          ]
        },
        {
          "id": "f03c6919-e4ee-4280-812a-07939d35cfb3",
          "name": "genericDistributionProviderAction.addMrssValidateFromFile",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovideraction/action/addMrssValidateFromFile?id=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "xsdFile",
                  "value": "{}",
                  "disabled": false,
                  "description": "XSD MRSS validatation file"
                }
              ]
            },
            "description": "Add MRSS validate file to generic distribution provider action"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bdec0b08-689f-484c-aa2d-73b5e233e7c1"
            }
          ]
        },
        {
          "id": "03238f7f-de01-4f68-90d9-f586535d5b79",
          "name": "genericDistributionProviderAction.addResultsTransform",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovideraction/action/addResultsTransform?id=%7B%7D&No Name=%7B%7D&transformData=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add results transform file to generic distribution provider action"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "925c57a2-1325-461d-a1a2-c8d2c5b2b470"
            }
          ]
        }
      ]
    }
  ]
}