---
title: Galactic Standard 1 
created: 08-16-2021
authors: Aidas <aidas@idep.network>, Denny <denny@idep.network>
discussions-to: https://discord.gg/Jrarctk4hG
status: Draft
Type: GS1
---


## Simple Summary

This standard describes a set of key value stores that describe a digital asset for extended reality use.

## Abstract

The Galactic-Standard-1 (GS1), defines a set of key value stores that are required to create digital assets in the IDEP Network.

## Motivation

This standard aims to improve on the [EIP-1155](https://eips.ethereum.org/EIPS/eip-1155) and to create a better version of Non Fungible Token (NFT). Its intentionally created to allow for more functionality to be attached to assets, with a focus on extended reality (XR) and gamification support (NFT-X).

## Specification

Every contract that supports the Galactic-Standard-1 SHOULD implement:

#### ITEM Definition

```js
{
    "base_req": {
                    "from": "idep1mc3t0cye333achqg6enw2nkfmftxja4x3mt0zh",
                    "chain_id": "Test-Denali"
                },
    "sn": Number,
    "name": 'string',
    "transferable": 'bool', // (true = 1 , false = 0)
    "owner": "idep1mc3t0cye333achqg6enw2nkfmftxja4x3mt0zh",
    "recipient": "idep1mc3t0cye333achqg6enw2nkfmftxja4x3mt0zh",
    "denom_id": mixed,
    "metadata": "URI",
}
```
#### ITEM Metadata
The description of the asset.

The linked JSON file should have the following format:
```js
{
    "description": "string",
    "name": "string", //OPTIONAL
    "attributes": ["string1, "string2", ...],
    "images": [ // multiple images in different sizes, related to the Item, image 0, should be the main image
        [{
                "width": Number,
                "height": Number,
                "url": "string"
            },
            ...
        ],
        [...]
    ],
    "assets": [{
            "title": "string", // (optional)
            "hashFunction": "keccak256",
            "hash": "string",
            "source": "string",
            "type": "gltf",
        },
        ...
    ],
    "url": [{
                "title": "string",
                "url": "string"
            },
            ...
            ],
}
```
