# Towhee - Faiss/Hnswlib - FederPy

## Overview

- Embedding: images => vectors
  - Input: images [, operator]
  - Output: rowId => vector, rowId => imageName
- Index Building: vectors => indexFile
  - Input: [, indexType, buildParams]
  - Output: indexFile
- Visualization: index / index-search => vis
  - Input: indexFile [, imageUrl, searchParams]
  - Output: `html`
- External
  - Data
    - images (or other unstructured data)
  - fileName
    - rowId => vectors
    - rowId => imageName
    - index file
  - web service
    - rowId => imageName => imageFile
  - env requirements
    - towhee
    - faiss
    - hnswlib
    - federpy - ipython

