{
  "info": {
    "name": "Kaltura VPaaS Post Service Contentdistribution Genericdistributionproveraction Action Addresultstransformfromfile",
    "_postman_id": "470b5f05-6297-4a96-8587-e9d4a5762d43",
    "description": "Add MRSS transform file to generic distribution provider action",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "264e1805-ba46-4e0b-8e46-4e727597cafa",
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
              "id": "bc42ef7e-0dee-441f-b2c8-d262e74a6491"
            }
          ]
        },
        {
          "id": "bebca689-90de-4fab-b779-2fd997f57386",
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
              "id": "9d4ce65a-5d6f-4968-b576-4a23f874f77b"
            }
          ]
        },
        {
          "id": "25d9edfd-befa-4a92-a66b-19b689037fd5",
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
              "id": "c0edd31d-5d04-4813-b37d-3e42ea4c6342"
            }
          ]
        },
        {
          "id": "82f547b9-d181-4892-99dc-98c23b85c784",
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
              "id": "9e2c3013-5331-4bfe-ba6a-457544db6df5"
            }
          ]
        },
        {
          "id": "41855640-2ee1-4b39-b12e-c036c7d0e823",
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
              "id": "1e269b10-419d-4bda-bc9f-09bbc1ef8558"
            }
          ]
        },
        {
          "id": "d1517f1c-6291-4e39-bd56-3786ba275d12",
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
              "id": "316118e4-3339-4ace-a131-b471df10eebd"
            }
          ]
        },
        {
          "id": "9dc223f5-2c46-4b30-b63f-d360a8db6427",
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
              "id": "93fe47f6-d223-42d5-acde-3ed838766e1f"
            }
          ]
        },
        {
          "id": "49790620-e1d4-4722-a400-bc72e830525e",
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
              "id": "667579fd-590f-48d8-8f44-c01826842aa2"
            }
          ]
        },
        {
          "id": "ff111c74-8156-452b-b2fa-b0c261d551d7",
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
              "id": "7d2c32eb-0d2b-43b1-aacc-0cf2ed86c060"
            }
          ]
        },
        {
          "id": "88ded636-b74f-4111-be21-be84bf6b30e6",
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
              "id": "c57a0dfe-6f06-402a-be72-b76075441193"
            }
          ]
        },
        {
          "id": "a5c05f24-745d-424d-9987-48b91dd20419",
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
              "id": "91585e3b-2d42-4092-a086-a46942a6fbd0"
            }
          ]
        },
        {
          "id": "5a19cb9c-48af-4ca2-b742-b5391d00d037",
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
              "id": "6a436d9c-ec5c-4a71-9070-375f8d69b192"
            }
          ]
        },
        {
          "id": "da4982d0-d4c1-4ded-ad27-a911ae48dd4f",
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
              "id": "f2799190-ac33-4ed5-9015-b5e6cdd62d3b"
            }
          ]
        },
        {
          "id": "c74a54f5-4b40-4747-a6b6-0df8040601a4",
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
              "id": "932452e2-8fb2-4f6b-a2d6-ff2a95d11c05"
            }
          ]
        },
        {
          "id": "cb51618f-420e-462d-9adf-8bd1a0561b3b",
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
              "id": "0f2d6d89-41a1-4c2a-8c8f-b27563fdc94c"
            }
          ]
        },
        {
          "id": "b6af9877-6f20-4d14-b01a-620cd5c1b2e3",
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
              "id": "063e15a4-9e77-47ee-82fe-33d58d84dfef"
            }
          ]
        },
        {
          "id": "3680cefd-42b4-4d79-a0d8-f253b8bdcc68",
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
              "id": "46824fbf-433b-41fc-aecc-62c95a20d961"
            }
          ]
        },
        {
          "id": "36ec2870-975f-4512-a0de-101469a4ecd0",
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
              "id": "352bfdb2-210b-4c61-b2cd-675608a2f8cf"
            }
          ]
        },
        {
          "id": "45b77ab1-575b-475c-b0c8-0996be82c61c",
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
              "id": "2a4faea5-ca74-4f34-847f-a1b4d69bd70c"
            }
          ]
        },
        {
          "id": "ff9a8669-9aed-4778-8bf4-99060c4eda5d",
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
              "id": "d3cb25c3-03fd-4f46-8cf0-05f9e956e7ee"
            }
          ]
        },
        {
          "id": "20571445-2409-4934-9bc8-c05c23cf6f46",
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
              "id": "9d78c9c4-34a0-482d-955f-5deffc7c66df"
            }
          ]
        },
        {
          "id": "7bd2b1c8-76dd-4ca8-8b17-89df0d3be521",
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
              "id": "49a492c6-9932-4d55-99e1-50021270f495"
            }
          ]
        },
        {
          "id": "6952ff8b-fa38-4a5b-aab9-5d91e79089d6",
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
              "id": "76495d7d-7c45-423d-b34d-bbb6e05ce4fe"
            }
          ]
        },
        {
          "id": "c893991a-71f0-470b-8d9d-d9e445056194",
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
              "id": "f26b6564-f034-4e6e-8639-c71eb08c774c"
            }
          ]
        },
        {
          "id": "c60348a1-a764-48df-8519-817e76a8ace5",
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
              "id": "8f7f5915-0ff8-4f2d-969b-6f1a76d36cca"
            }
          ]
        },
        {
          "id": "e3a145f6-00fc-4205-92ba-868df5081667",
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
              "id": "00958fe4-a3fc-4a96-acd0-4984659fa5d5"
            }
          ]
        },
        {
          "id": "e1827f5e-6bbe-433d-b56a-142a8bf01855",
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
              "id": "defab4e8-c36e-4152-a95e-002f67495af9"
            }
          ]
        },
        {
          "id": "253115f6-f89a-472b-b821-d4cc93415dc6",
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
              "id": "b899cdc4-ceb7-481b-88ab-c3ece77e635f"
            }
          ]
        },
        {
          "id": "15600ea6-4b26-4995-bcab-a5b0263305b1",
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
              "id": "33a0eb8a-43a4-4695-bc7b-381d0346f376"
            }
          ]
        },
        {
          "id": "7f4da0d2-44b4-40b1-a9c9-ad6a1a846de2",
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
              "id": "1ac720e2-7c70-4ba9-bf28-c20ed659f871"
            }
          ]
        },
        {
          "id": "d4b5f3c0-d74c-4397-b1f5-744e7eb6ec7c",
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
              "id": "17454f71-20a7-4dc0-9034-f704ea83785a"
            }
          ]
        },
        {
          "id": "4f829697-cb89-49eb-ac54-a3fdf9ef0366",
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
              "id": "d2be8e61-dc67-4e46-82c6-dd1fe944db26"
            }
          ]
        },
        {
          "id": "ce1020d1-d2cf-43ae-9587-d1ef63160e87",
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
              "id": "e3b67d5d-1551-4415-b207-90095639e093"
            }
          ]
        },
        {
          "id": "5b2b9d2d-d50b-44f2-b119-a9554f9446e0",
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
              "id": "86a7c50f-e93a-4dba-adc5-056dca12d31a"
            }
          ]
        },
        {
          "id": "461a728c-a8ff-458e-b81a-c7625e02497e",
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
              "id": "a8b08c79-261a-4b9c-82d1-c4cacbf621db"
            }
          ]
        },
        {
          "id": "3aedb7ce-70d8-4af5-abe4-3b987bd82ea3",
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
              "id": "c5a42cc6-c6d8-47db-9d25-e3448379ee13"
            }
          ]
        },
        {
          "id": "43d6c4b2-2027-4483-aae3-74b946ae4330",
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
              "id": "9c7feac1-fac5-4f33-be8f-ec17aa4af59f"
            }
          ]
        },
        {
          "id": "7a8167bc-005e-49b2-bbd7-f3a5a0aee39c",
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
              "id": "d1b8be12-759a-4e55-8257-324189a54a04"
            }
          ]
        },
        {
          "id": "029541d2-f687-4d56-8cab-f3c6ade7a99b",
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
              "id": "333e0231-d08a-4399-9ce3-c08e2354a7a5"
            }
          ]
        },
        {
          "id": "e8c25639-62f6-4e6a-9d08-7cf29457457e",
          "name": "genericDistributionProviderAction.addResultsTransformFromFile",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/contentdistribution_genericdistributionprovideraction/action/addResultsTransformFromFile?id=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "transformFile",
                  "value": "{}",
                  "disabled": false,
                  "description": "transformation file xsl, xPath or regex"
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
              "id": "57285564-dad3-403c-a088-fcdccf4c4aba"
            }
          ]
        }
      ]
    }
  ]
}