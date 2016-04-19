# azure-search-get-started-sample-data
This repository contains sample data for use with Azure Search.

Files in this dataset consist of the following:

1. 246 JSON documents, one per file (filename=<number>.json). These documents are sample data used in our "Get Started with Azure Search" tutorial. Although the files are numbered, there are gaps in the sequence. Do not rely on sequential numbering for the files in this dataset.

2. **musicstore-data<number>.json** is a collection of 3 data files, not currently used in tutorials, but included anyway in case you need sample data for other purposes. Azure Search can parse a file that contains multiple JSON documents. If you are writing test code, these files might be useful to you. These 3 files provide the same data as the standalone JSON documents, but consolidated.  

3. **search-index-schema.json** is not currently used in tutorials, but we include this file in case you need it for other purposes. This file is the schema for an Azure Search index that conforms to the JSON data in this sample dataset.

Files were last updated on April 19, 2016. Change was to rename a "key" field to "id".
