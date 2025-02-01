# Create Attachment
Upload attachments to Nerimity's CDN

**Files expire after 5 minutes if they were not sent to a channel**
#### Endpoint
```
POST https://cdn.nerimity.com/upload
```

| Body (FormData)       | Type      | Description                               |
| --------------------- | --------- | ----------------------------------------- |
|  file                 | binary    | The binary content of the image file      |


#### Response
```json
{"fileId": "1234.."}
```
