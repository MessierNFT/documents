# Messier.Art Developer Guideline #

Welcome to this guideline, once below data is ready, you should apply to admin@messier.art.

## What we need ##
1. Collection Name which will be shown in contract.
2. Collection Symbol which will be shown in contract
3. All art assets in single folder with file name as {id}.jpg
4. All token metadata in single folder with file name as {id}.json, token metadata should have below format.
```json
{
  "name": "Enterprise",
  "extension": {
    "image": "{id}.jpg",
    "image_data": "",
    "external_url": "{External url if any}",
    "description": "{Nft description}",
    "name": "{Nft name}",
    "attributes": [{"Array of Nft attributes"}],
    "animation_url":  "{NFT Animation file if any}",
    "youtube_url": "{NFT Youtube file if any}"
  }
}
```
Example 

```json
{
  "name": "Enterprise #1",
  "extension": {
    "image": "1.jpg",
    "image_data": null,
    "external_url": null,
    "description": "Spaceship with Warp Drive",
    "name": "Starship USS Enterprise",
    "attributes": [{
                        "display_type": null,
                        "trait_type": "color",
                        "value": "black"
                    }],
    "background_color": null,
    "animation_url": null,
    "youtube_url": null
  }
}
```
5. We will take care of below things
   * Token ID as per file name 
   * File uploads to IPFS
   * Token metadata upload to IPFS

If you have more question, contact admin@messier.art

An example folder is provided in this repo for the reference.
