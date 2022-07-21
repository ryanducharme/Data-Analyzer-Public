# Data-Analyzer
***Due to this being an internal tool, I cannot share the code. I also had to censor some sensitve data.***

Using .NET's XML library I was able to create a program that reads in document templates which break down into large XML files, and rip out the data that we need for configuring the documents in our database. This tool also serves as an easy way for our QA testers to find data that is being dynamically populated within our document templates.

This saves the employee from having to go through document templates and count up all of the necessary data by hand. Finding the proper configuration data can take a anywhere from a few minutes to half an hour depending on the size of the document. This tool results in a nearly instantaneous, 100% accurate result. On top of that you can load as many document templates into the system as you want making the process even easier.

![censored preview](https://user-images.githubusercontent.com/72882588/180104076-1df06cda-7a0d-403f-b4a9-a7ae2f710fe7.png)

## Features
- Analyze multiple document templates at once
- Pinpoint necessary database configuration data (internally known as "extended data")
- Sample generation for easier QA testing
- Easy copying of document details such as names and GUIDS

### Multi-Document Analysis
![gif 1](https://user-images.githubusercontent.com/72882588/180104087-3b1391d4-7161-4021-a1f6-bd94f5dec5f6.gif)

### Document Analysis Results
![output-onlinegiftools](https://user-images.githubusercontent.com/72882588/180104102-7e8509eb-15bb-4c4c-9c74-b04018532c00.gif)

