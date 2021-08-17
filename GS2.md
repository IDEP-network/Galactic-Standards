---
title: Galactic Standard 2
created: 08-16-2021
authors: Aidas <aidas@idep.network>, Denny <denny@idep.network>
discussions-to: https://discord.gg/Jrarctk4hG
status: Draft
Type: GS2
---


## Simple Summary

This standard describes a set of key value stores that describe a digital asset collection for extended reality use.

## Abstract

The Galactic-Standard-2 (GS2), defines a set of key value stores that are required to create digital asset collection in the IDEP Network.

## Motivation

This standard aims to create a collection standard for Non Fungible Tokens (NFT). Its intentionally created to allow for more functionality to be attached to assets, with a focus on extended reality (XR) and gamification support (NFT-X).

## Specification

Every contract that supports the Galactic-Standard-2 SHOULD implement:

#### Collection Definition
```js
{
    "base_req": {
                    "from": "idep1mc3t0cye333achqg6enw2nkfmftxja4x3mt0zh",
                    "chain_id": "Test-Denali"
                },
    "id": mixed,
    "name": "string",
    "owner": "idep1mc3t0cye333achqg6enw2nkfmftxja4x3mt0zh", // wallet address
    "recipient": "idep1mc3t0cye333achqg6enw2nkfmftxja4x3mt0zh", // wallet address
    "denom_id": mixed,
    "metadata": "URI",
}
```

#### Collection Metadata
The description of the collection.

The linked JSON file should have the following format:
```js
{
    "description": "string",
    "name": "string", // optional
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
            "title": "string", // optional
            "hashFunction": "keccak256",
            "hash": "string",
            "source": "string",
            "type": "gltf",
           },
        [...]
    ],
    "url": [{
                "title": "string",
                "url": "string"
            },
            [...]
            ],
}
```

