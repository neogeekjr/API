
# NeoGeekJr API

Documentation on the endpoints for `https://api.neogeekjr.com`

## API Reference
Base URL is https://api.neogeekjr.com

#### Get Current UNIX Time

```http
  GET /time
```
#### Example
| Response | Type | Data | 
| :-------- | :------- | :------------------------- |
| 200 | `json` | `time:1486013877`



#### Get Random Animal Meme

```http
  GET /img/<animal>
```
`Options currently are possum, racoon & cat`

| Parameter | Type     | Description                       | Required |
| :-------- | :------- |:------- |  :-------------------------------- |
| `animal`      | `string` | Name of animal | **Yes**

