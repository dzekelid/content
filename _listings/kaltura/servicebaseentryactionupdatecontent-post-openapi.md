---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Post Service Baseentry Action Updatecontent
  description: Update the content resource associated with the entry.
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/attachment_attachmentasset/action/setContent:
    post:
      summary: Post Service Attachment Attachmentasset Action Setcontent
      description: Update content of attachment asset
      operationId: attachmentAsset.setContent
      x-api-path-slug: serviceattachment-attachmentassetactionsetcontent-post
      parameters:
      - in: query
        name: contentResource[assetId]
        description: ID of the source asset
      - in: query
        name: contentResource[content]
        description: Textual content
      - in: query
        name: contentResource[dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: contentResource[entryId]
        description: ID of the source entry
      - in: formData
        name: contentResource[fileData]
        description: Represents the $_FILE
      - in: query
        name: contentResource[fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: contentResource[flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: contentResource[forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: contentResource[keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: contentResource[keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: contentResource[localFilePath]
        description: Full path to the local file
      - in: query
        name: contentResource[objectId]
        description: The object id of the file sync object
      - in: query
        name: contentResource[objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: contentResource[objectType]
      - in: query
        name: contentResource[privateKey]
        description: SSH private key
      - in: query
        name: contentResource[publicKey]
        description: SSH public key
      - in: query
        name: contentResource[resources]
      - in: query
        name: contentResource[resource][assetId]
        description: ID of the source asset
      - in: query
        name: contentResource[resource][content]
        description: Textual content
      - in: query
        name: contentResource[resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: contentResource[resource][entryId]
        description: ID of the source entry
      - in: formData
        name: contentResource[resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: contentResource[resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: contentResource[resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: contentResource[resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: contentResource[resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: contentResource[resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: contentResource[resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: contentResource[resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: contentResource[resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: contentResource[resource][objectType]
      - in: query
        name: contentResource[resource][privateKey]
        description: SSH private key
      - in: query
        name: contentResource[resource][publicKey]
        description: SSH public key
      - in: query
        name: contentResource[resource][resources]
      - in: query
        name: contentResource[resource][resource][assetId]
        description: ID of the source asset
      - in: query
        name: contentResource[resource][resource][content]
        description: Textual content
      - in: query
        name: contentResource[resource][resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: contentResource[resource][resource][entryId]
        description: ID of the source entry
      - in: formData
        name: contentResource[resource][resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: contentResource[resource][resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: contentResource[resource][resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: contentResource[resource][resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: contentResource[resource][resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: contentResource[resource][resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: contentResource[resource][resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: contentResource[resource][resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: contentResource[resource][resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: contentResource[resource][resource][objectType]
      - in: query
        name: contentResource[resource][resource][privateKey]
        description: SSH private key
      - in: query
        name: contentResource[resource][resource][publicKey]
        description: SSH public key
      - in: query
        name: contentResource[resource][resource][resources]
      - in: query
        name: contentResource[resource][resource][resource][assetId]
        description: ID of the source asset
      - in: query
        name: contentResource[resource][resource][resource][content]
        description: Textual content
      - in: query
        name: contentResource[resource][resource][resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: contentResource[resource][resource][resource][entryId]
        description: ID of the source entry
      - in: formData
        name: contentResource[resource][resource][resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: contentResource[resource][resource][resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: contentResource[resource][resource][resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: contentResource[resource][resource][resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: contentResource[resource][resource][resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: contentResource[resource][resource][resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: contentResource[resource][resource][resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: contentResource[resource][resource][resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: contentResource[resource][resource][resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: contentResource[resource][resource][resource][objectType]
      - in: query
        name: contentResource[resource][resource][resource][privateKey]
        description: SSH private key
      - in: query
        name: contentResource[resource][resource][resource][publicKey]
        description: SSH public key
      - in: query
        name: contentResource[resource][resource][resource][resources]
      - in: query
        name: contentResource[resource][resource][resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: contentResource[resource][resource][resource][token]
        description: Token that returned from upload
      - in: query
        name: contentResource[resource][resource][resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: contentResource[resource][resource][resource][version]
        description: The version of the file sync object
      - in: query
        name: contentResource[resource][resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: contentResource[resource][resource][token]
        description: Token that returned from upload
      - in: query
        name: contentResource[resource][resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: contentResource[resource][resource][version]
        description: The version of the file sync object
      - in: query
        name: contentResource[resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: contentResource[resource][token]
        description: Token that returned from upload
      - in: query
        name: contentResource[resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: contentResource[resource][version]
        description: The version of the file sync object
      - in: query
        name: contentResource[storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: contentResource[token]
        description: Token that returned from upload
      - in: query
        name: contentResource[url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: contentResource[version]
        description: The version of the file sync object
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Attachment
      - Attachmentasset
      - Action
      - SetContent
  /service/baseentry/action/addContent:
    post:
      summary: Post Service Baseentry Action Addcontent
      description: Attach content resource to entry in status NO_MEDIA
      operationId: baseEntry.addContent
      x-api-path-slug: servicebaseentryactionaddcontent-post
      parameters:
      - in: query
        name: entryId
      - in: query
        name: No Name
      - in: query
        name: resource[assetId]
        description: ID of the source asset
      - in: query
        name: resource[content]
        description: Textual content
      - in: query
        name: resource[dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: resource[entryId]
        description: ID of the source entry
      - in: formData
        name: resource[fileData]
        description: Represents the $_FILE
      - in: query
        name: resource[fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: resource[flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: resource[forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: resource[keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: resource[keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: resource[localFilePath]
        description: Full path to the local file
      - in: query
        name: resource[objectId]
        description: The object id of the file sync object
      - in: query
        name: resource[objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: resource[objectType]
      - in: query
        name: resource[privateKey]
        description: SSH private key
      - in: query
        name: resource[publicKey]
        description: SSH public key
      - in: query
        name: resource[resources]
      - in: query
        name: resource[resource][assetId]
        description: ID of the source asset
      - in: query
        name: resource[resource][content]
        description: Textual content
      - in: query
        name: resource[resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: resource[resource][entryId]
        description: ID of the source entry
      - in: formData
        name: resource[resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: resource[resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: resource[resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: resource[resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: resource[resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: resource[resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: resource[resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: resource[resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: resource[resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: resource[resource][objectType]
      - in: query
        name: resource[resource][privateKey]
        description: SSH private key
      - in: query
        name: resource[resource][publicKey]
        description: SSH public key
      - in: query
        name: resource[resource][resources]
      - in: query
        name: resource[resource][resource][assetId]
        description: ID of the source asset
      - in: query
        name: resource[resource][resource][content]
        description: Textual content
      - in: query
        name: resource[resource][resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: resource[resource][resource][entryId]
        description: ID of the source entry
      - in: formData
        name: resource[resource][resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: resource[resource][resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: resource[resource][resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: resource[resource][resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: resource[resource][resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: resource[resource][resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: resource[resource][resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: resource[resource][resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: resource[resource][resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: resource[resource][resource][objectType]
      - in: query
        name: resource[resource][resource][privateKey]
        description: SSH private key
      - in: query
        name: resource[resource][resource][publicKey]
        description: SSH public key
      - in: query
        name: resource[resource][resource][resources]
      - in: query
        name: resource[resource][resource][resource][assetId]
        description: ID of the source asset
      - in: query
        name: resource[resource][resource][resource][content]
        description: Textual content
      - in: query
        name: resource[resource][resource][resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: resource[resource][resource][resource][entryId]
        description: ID of the source entry
      - in: formData
        name: resource[resource][resource][resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: resource[resource][resource][resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: resource[resource][resource][resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: resource[resource][resource][resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: resource[resource][resource][resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: resource[resource][resource][resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: resource[resource][resource][resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: resource[resource][resource][resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: resource[resource][resource][resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: resource[resource][resource][resource][objectType]
      - in: query
        name: resource[resource][resource][resource][privateKey]
        description: SSH private key
      - in: query
        name: resource[resource][resource][resource][publicKey]
        description: SSH public key
      - in: query
        name: resource[resource][resource][resource][resources]
      - in: query
        name: resource[resource][resource][resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: resource[resource][resource][resource][token]
        description: Token that returned from upload
      - in: query
        name: resource[resource][resource][resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: resource[resource][resource][resource][version]
        description: The version of the file sync object
      - in: query
        name: resource[resource][resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: resource[resource][resource][token]
        description: Token that returned from upload
      - in: query
        name: resource[resource][resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: resource[resource][resource][version]
        description: The version of the file sync object
      - in: query
        name: resource[resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: resource[resource][token]
        description: Token that returned from upload
      - in: query
        name: resource[resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: resource[resource][version]
        description: The version of the file sync object
      - in: query
        name: resource[storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: resource[token]
        description: Token that returned from upload
      - in: query
        name: resource[url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: resource[version]
        description: The version of the file sync object
      responses:
        200:
          description: OK
      tags:
      - Service
      - Baseentry
      - Action
      - AddContent
  /service/baseentry/action/updateContent:
    post:
      summary: Post Service Baseentry Action Updatecontent
      description: Update the content resource associated with the entry.
      operationId: baseEntry.updateContent
      x-api-path-slug: servicebaseentryactionupdatecontent-post
      parameters:
      - in: query
        name: advancedOptions[keepManualThumbnails]
        description: If true manually created thumbnails will not be deleted on entry
          replacement
      - in: query
        name: advancedOptions[pluginOptionItems]
      - in: query
        name: conversionProfileId
        description: The conversion profile id to be used on the entry
      - in: query
        name: entryId
        description: Entry id to update
      - in: query
        name: No Name
      - in: query
        name: resource[assetId]
        description: ID of the source asset
      - in: query
        name: resource[content]
        description: Textual content
      - in: query
        name: resource[dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: resource[entryId]
        description: ID of the source entry
      - in: formData
        name: resource[fileData]
        description: Represents the $_FILE
      - in: query
        name: resource[fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: resource[flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: resource[forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: resource[keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: resource[keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: resource[localFilePath]
        description: Full path to the local file
      - in: query
        name: resource[objectId]
        description: The object id of the file sync object
      - in: query
        name: resource[objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: resource[objectType]
      - in: query
        name: resource[privateKey]
        description: SSH private key
      - in: query
        name: resource[publicKey]
        description: SSH public key
      - in: query
        name: resource[resources]
      - in: query
        name: resource[resource][assetId]
        description: ID of the source asset
      - in: query
        name: resource[resource][content]
        description: Textual content
      - in: query
        name: resource[resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: resource[resource][entryId]
        description: ID of the source entry
      - in: formData
        name: resource[resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: resource[resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: resource[resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: resource[resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: resource[resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: resource[resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: resource[resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: resource[resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: resource[resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: resource[resource][objectType]
      - in: query
        name: resource[resource][privateKey]
        description: SSH private key
      - in: query
        name: resource[resource][publicKey]
        description: SSH public key
      - in: query
        name: resource[resource][resources]
      - in: query
        name: resource[resource][resource][assetId]
        description: ID of the source asset
      - in: query
        name: resource[resource][resource][content]
        description: Textual content
      - in: query
        name: resource[resource][resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: resource[resource][resource][entryId]
        description: ID of the source entry
      - in: formData
        name: resource[resource][resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: resource[resource][resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: resource[resource][resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: resource[resource][resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: resource[resource][resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: resource[resource][resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: resource[resource][resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: resource[resource][resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: resource[resource][resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: resource[resource][resource][objectType]
      - in: query
        name: resource[resource][resource][privateKey]
        description: SSH private key
      - in: query
        name: resource[resource][resource][publicKey]
        description: SSH public key
      - in: query
        name: resource[resource][resource][resources]
      - in: query
        name: resource[resource][resource][resource][assetId]
        description: ID of the source asset
      - in: query
        name: resource[resource][resource][resource][content]
        description: Textual content
      - in: query
        name: resource[resource][resource][resource][dropFolderFileId]
        description: Id of the drop folder file object
      - in: query
        name: resource[resource][resource][resource][entryId]
        description: ID of the source entry
      - in: formData
        name: resource[resource][resource][resource][fileData]
        description: Represents the $_FILE
      - in: query
        name: resource[resource][resource][resource][fileSyncObjectType]
        description: The object type of the file sync object
      - in: query
        name: resource[resource][resource][resource][flavorParamsId]
        description: ID of the source flavor params, set to null to use the source
          flavor
      - in: query
        name: resource[resource][resource][resource][forceAsyncDownload]
        description: Force Import Job
      - in: query
        name: resource[resource][resource][resource][keepOriginalFile]
        description: Should keep original file (false = mv, true = cp)
      - in: query
        name: resource[resource][resource][resource][keyPassphrase]
        description: Passphrase for SSH keys
      - in: query
        name: resource[resource][resource][resource][localFilePath]
        description: Full path to the local file
      - in: query
        name: resource[resource][resource][resource][objectId]
        description: The object id of the file sync object
      - in: query
        name: resource[resource][resource][resource][objectSubType]
        description: The object sub-type of the file sync object
      - in: query
        name: resource[resource][resource][resource][objectType]
      - in: query
        name: resource[resource][resource][resource][privateKey]
        description: SSH private key
      - in: query
        name: resource[resource][resource][resource][publicKey]
        description: SSH public key
      - in: query
        name: resource[resource][resource][resource][resources]
      - in: query
        name: resource[resource][resource][resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: resource[resource][resource][resource][token]
        description: Token that returned from upload
      - in: query
        name: resource[resource][resource][resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: resource[resource][resource][resource][version]
        description: The version of the file sync object
      - in: query
        name: resource[resource][resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: resource[resource][resource][token]
        description: Token that returned from upload
      - in: query
        name: resource[resource][resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: resource[resource][resource][version]
        description: The version of the file sync object
      - in: query
        name: resource[resource][storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: resource[resource][token]
        description: Token that returned from upload
      - in: query
        name: resource[resource][url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: resource[resource][version]
        description: The version of the file sync object
      - in: query
        name: resource[storageProfileId]
        description: ID of storage profile to be associated with the created file
          sync, used for file serving URL composing
      - in: query
        name: resource[token]
        description: Token that returned from upload
      - in: query
        name: resource[url]
        description: Remote URL, FTP, HTTP or HTTPS
      - in: query
        name: resource[version]
        description: The version of the file sync object
      responses:
        200:
          description: OK
      tags:
      - Service
      - Baseentry
      - Action
      - UpdateContent
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---