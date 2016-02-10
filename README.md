# azure-search-get-started-sample-data
This repository contains sample data used in tutorials and walkthroughs for Azure Search.

The files in this dataset consist of the following:

1. 246 JSON documents, one per file (filename=<number>.json). These documents are sample data used in our "Get Started with Azure Search" tutorial. Although the files are numbered, there are gaps in the sequence. Do not rely on sequential numbering for the files in this  dataset.

2. **musicstore-data<number>.json** is not currently used in tutorials, but we include them in case they are useful to you. These 3 files provide the same data as the standalone JSON documents, but consolidated. Azure Search can parse a file that contains multiple JSON documents. You can use these files, plus the index included in this sample, to experiment with Azure Search.

3. **search-index-schema.json** is a schema file for an Azure Search index that conforms to the JSON data in this sample dataset.

Originally, these files shipped with a code sample for learning about scoring profiles. If you've seen that code sample, the music store data will look familiar.
