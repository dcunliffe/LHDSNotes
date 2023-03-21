---
layout: post
title:  "Test Drawio"
date:   2023-03-20 16:30:00 +0000
categories: LDHS Test
mermaid: true
---

This is a test post:

## Test image:
![Alt text](/drawings/test.drawio.svg)


## Test Mermaid:

<div class="mermaid">
sequenceDiagram
    Data Lake->>+Decrypt Function: Document created event
    Decrypt Function->>-Key Vault: Retrieve decryption certificate
</div>

<div class="mermaid">
    pie
        "Hello": 50
        "World": 25
        "England": 25
</div>

```mermaid!
pie
    "Hello": 50
    "World": 25
    "England": 25
```