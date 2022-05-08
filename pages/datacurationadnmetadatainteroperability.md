---
title: Data Curation and Metadata Interoperability Learning Sequence
layout: about
permalink: /datacurationadninteroperability.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="bethel-school_1930" %}

{% include feature/nav-menu.html sections="Overview;Data Curation and Metadata for Digital Collections;Making Metadata Interoperable with CollectionBuilder; Metadata Remediation and Refinement Activity" %}

# Data Curation and Metadata Interoperability Learning Sequence
**🖋️ Lesson Plan for Instructors**

[This learning sequence's instructor lesson plan is found on a different page. Please use this resource to help facilitate teaching the learning sequence. It also contains instructions for next steps after the sequence is finished.](/dcmilessonplan.html)

## Overview
This learning sequence will prepare you for working with the Beyond Toxic Dataset before using the dataset for your own research purposes. Before anyone is able to use the dataset, it must first be made publicly available online using CollectionBuilder, the platform used to host, search, and browse the dataset.

This learning sequence gives you an introduction to data curation and standardizing metadata to be interoperable. It also asks you to complete a Beyond Toxic metadata remediation and refinement activity. By correcting and adding metadata to the Beyond Toxic dataset, you are directly contributing to making a digital collection for Beyond Toxic, a nonprofit environmental justice organization based in Eugene, Oregon, to use for their advocacy purposes.

**What will you learn after completing this learning sequence**
- Define data curation and interoperability within the context of digital collections
- Recognize metadata standards applied to data found in the Digital Public Library of America way for metadata to be interoperable 
- Use a class data dictionary to correct and add descriptive and technical metadata to the Beyond Toxic Dataset
- Apply CollectionBuilder's system requirements so objects and metadata can be added to a central data repository


## Data Curation and Metadata for Digital Collections

### What is Data Curation?
Data Curation, sometimes called Digital Curation, is the necessary steps required to actov manage historical and scientific records.  Data includes files representing photographs, tabulated data, sound recordings, video recordings, textual documents, 3D models, etc. and the accompanying metadata (data about data representing context and meaning for humans and computers).

Data Curation involves people using computers to do the following activities: 
- Selecting data
- Aquiring data
- Archiving data
- Monitoring data over periods of time
- Delivering and sharing data

These activities can take shape through the following actions, but at not limited to this list:
- Picking data that is relevant to a project's scope
- Setting up and coordinating workflow processes for project management
- Scanning files for viruses
- Reviewing data to comply with privacy and security restrictions
- Identifying, converting and transferring data 
- Transfering files from one server to another
- Backing up data in multiple secure server locations
- Running integrity checks to ensure data has not changed over time 
- Creating and reviewing of metadata
- Making sure data is retrievable and findable
- Ensuring all platforms and tools used for curation properly works with the data you collection, manipulate, and share with users
- Making sure copyright is followed and communicated when collecting and sharing data
- Asking ethical questions about the type of treatments data should have during the curation process.

Within the library, museums, and archives profession, data curation tends to have a team of information science professionals charged with overseeing all care activities. [Here's an example from the Smithsonian's Archives. They have a digital curation team responsible for this type of work.](https://siarchives.si.edu/what-we-do/digital-curation) Professionals take one specific roles connected to the data acquisition, accessioning, processing, archiving, and sharing.

### What is Metadata?

At its core, metadata adds meaning and context to how data is described, technically represented, and strucured for humans and computers to manage.

There are many different catalogies of metadata types.

- *Descriptive Metadata:* Information about an object's (e.g. newspaper, photograph, tabbulated dataset, sound recordings, video recording, etc.) aboutness. An example of this type of metadata: creator information, object title, creation data, object description, and copyright information
- *Administrative Metadata:* Information that captures the needed steps to manage and use objects. This is usually used internally by data curators. An example of this type of metadata: the name of the person who cataloged an object or who can use and access digital objects.
- *Technical Metadata:* Information that captures the technical qualities of all file formats and metadata representing objects. An example of this type of metadata includes technical information about file formats, resolutions, color spaces, etc.
- *Preservation Metadata:* Information about documenting the curation activities ensuring long-term access and archiving of digital objects. An example of this type of metadata includes: data authenticity and integrity checks.
- *Structural Metadata:* Information about technical requirements for managing the digital parts of an object. Here is an example of what this looks like in practice. We know our Beyond Text dataset includes a variety of digitized (the scanning of 2-dimentional physical objects) textual objects, e.g. newspapers, city planning reports, etc., that come from library, archives, and museums. These textual objects are digitally represented through file formats like .pdfs and .jpgs and accompanying information about object's descriptive (descriptive metadata) and administrative (administrative metadata). Structural metadata encodes this relationship so computers know how to manage it and keep the object's context intact.

### Digital Collections Metadata in Context: The Digital Public Library of America (DPLA)
DPLA is an online database where libraries, museums, and archives across the United States aggregate their digital collections to be found in one place instead of siloed in their own database systems. 

DPLA allows anyone in the world to be able to search millions of digital and digitized primary sources made publicly available by different types of digital collection programs at research libraries and archives (University of Oregon and Oregon State University); government managed archives (The Library of Congress; museums (The Smithsonian and the Getty Museum of Art); and public libraries (Boston Public Library and New York Public Library).

#### How does metadata work with DPLA?
Libraries, museums, and archives contributing to DPLA follow a metadata standard, which gives DPLA the ability to aggregate institutional and organizationally curated digital collections. 

A metadata standard supports the consistant ways digital objects need to be cataloged. For this lesson, we'll focus primarily on how DPLA wants descriptive metadata standardized instead of highlighting the other types of metadata previously mentioned.

##### Lets look at two different digital objects in DPLA
These photographs are of two different libraries and contributed to DPLA by two different universities, the University of Oregon and Oregon State University.
- [Oregon State University Library. Retrieved from the Digital Public Library of America, http://hdl.handle.net/11134/470002:116676. (Accessed May 8, 2022.)](https://dp.la/item/3fbb8c71b0da90ebc9a2183f82152d6a?q=%22oregon+state+university%22)
- [Lawrence, Holford, and Allyn, Lawrence, Ellis Fuller, Holford, William, Allyn, Frederick S, Lawrence, H. Abbott, Tucker, Ernest F, Wallmann, George R, Hamlin & Martin Architecture, Hamlin, Claire K, Martin, B. King, Hammond, Ross B. Knight Library, University of Oregon (Eugene, Oregon). 1937. Retrieved from the Digital Public Library of America, https://utah-primoprod.hosted.exlibrisgroup.com/primo-explore/fulldisplay?docid=digcoll_ore_47building-or/df67q9346&context=L&vid=MWDL. (Accessed May 8, 2022.)](https://dp.la/item/0a57cff183d5bf3b45751588d4ffb7a7?q=university+of+oregon+library)

Each of these objects are described using similar labels:

- Created Date: The date an object was originally made
- Description: A description about the object
- Creator: The name of person or organizational entity that created the object
- Collection: The name of the libray, museum, or archival collection the object resides within an organizational context
- Subjects: terms what categorize an object's aboutness
- Location: An identified geographic location associated with the object
- Standardized Rights Statement: A description about the copyright status using [RightsStatements.org](https://rightsstatements.org/en/)

### Let us reflect!
Take 2 minutes to write a quick lecture reflection response. You can use a notetaking app on your computer or use a paper and writing instrument.

Answer these questions:
- What are 3 things you found interesting?
- What are 2 things you learned?
- What is 1 thing you still have a question about?

## Making Metadata Interoperable with CollectionBuilder

### What is interoperability?

Interoperability allows people to setup and express metadata so computers can aggregate, read, and intergrate data within different computer systems like online databases.

### How can metadata become interoperable?

Data dictionaries, also known as metadata application profiles (MAP, support metadata interoperability and standarization so data curators, computers systems, and data users are able to make sense of and use metadata.

- *Data Curators* need data dictionaries to help describe objects accurately and consistantly. This can involve uniform explanations about objects. These explanations can take shape through consistant metadata labels and controlled lists representing terminology and descriptions (controlled vocabularies) about objects.
- *Computer Systems* need data dictionaries to properly add, function, and represent data within an application. This can involve specific data entry conventions required by a computer to be able to interpret and represent objects in interactive ways.
- *Data Users* need data dictionaries to be able to use data for a specific purpose e.g. search for objects, read copyright statements, identify specific historical dates, etc. This involves making sure data curators understand what a computer system requires for object browsing, readability, searching, and reusability.

##### An example of metadata interoperability in practice
Data curators at the University of Oregon and Oregon State University following a metadata standard so digital collections can not only be found and used in [Oregon Digital](https://oregondigital.org/catalog), UO and OSU's jointly managed digital repository for unique cultural heritage materials, but also in [DPLA](https://dp.la/). In order for digital collections to live in two places, the metadata has to conform to metadata descriptions and upload requirements set by both the Oregon Digital repository system and DPLA's aggregation requirements.

[The library photos coming from Oregon Digital follow DPLA's MAP. This MAP sets what is required for anything that goes into the DPLA repository system.](https://pro.dp.la/hubs/metadata-application-profile) It ultimately acts as data dictionary that tells data curators how to prepare metadata so it is interoperable.  

Look at these photographs and look for similarities in descriptive metadata labels, identify how dates are displayed, and click on the Subject field to find other primary sources. Something to note: When clicking on a hyperclicked subject term, the system is able to find related objects because data curators use controlled vocabularies. This allows people to find categorized topics related to the "aboutness" of an object.

- [Oregon State University Library. Retrieved from the Digital Public Library of America, http://hdl.handle.net/11134/470002:116676. (Accessed May 8, 2022.)](https://dp.la/item/3fbb8c71b0da90ebc9a2183f82152d6a?q=%22oregon+state+university%22)
- [Lawrence, Holford, and Allyn, Lawrence, Ellis Fuller, Holford, William, Allyn, Frederick S, Lawrence, H. Abbott, Tucker, Ernest F, Wallmann, George R, Hamlin & Martin Architecture, Hamlin, Claire K, Martin, B. King, Hammond, Ross B. Knight Library, University of Oregon (Eugene, Oregon). 1937. Retrieved from the Digital Public Library of America, https://utah-primoprod.hosted.exlibrisgroup.com/primo-explore/fulldisplay?docid=digcoll_ore_47building-or/df67q9346&context=L&vid=MWDL. (Accessed May 8, 2022.)](https://dp.la/item/0a57cff183d5bf3b45751588d4ffb7a7?q=university+of+oregon+library)

### How does interoperability relate to the Beyond Toxic Dataset?

You as a data curator will need to follow the class data dictonary that will be supplied in the forthcoming activity. This data dictionary has been created to following metadata description standards. It complies with how CollectionBuilder (the comptuer system) wants data entry to be standardized in order for data to be integreted upon system ingest.

By following the data dictionary and adding objects (newspapers clippings represented through .pdf or .jpg) and metadata to CollectionBuilder, the people (data users) who come to the Beyond Toxic Data Repository will be able to search, browse, read, find, and download any data added to CollectionBuilder.

**What CollectionBuilder system requirements need to be followed by data curators?**

CollectionBuilder wants data curators to add values, a term from the computer science discipline used to describe numbers, letters, and the unique unique combinations of them, in a very specific way for certain fields. 

Here is a specific example for how to do data entry for the Subject field.

**subject:**
- The subject field contains topic(s) related to the object.
- This field allows for multiple subjects to be input for a single record. Each should be separated with a semicolon (;)

Example value to add to a spreadsheet cell: Dogs; Cats; Zebras

[For the data dictionary used in class, please review the required fields for CollectionBuilder-GH to see how the application wants values expressed in a required way.](https://collectionbuilder.github.io/cb-docs/docs/metadata/gh_metadata/)

### Okay, now lets apply this knowledg through an instructor "Show and Tell" 
Watch your instructor demonstrate how to access Beyond Toxic Dataset (objects and metadata spreadsheet) and work through how to remediate and refine metadata records to conform to CollectionBuilder's requirements. After they are finished then you will need to complete the activity below.

## Metadata Remediation and Refinement Activity
**Activity Goal:** The Beyond Toxic Dataset needs remediation and refinement so objects and their descriptions can be successfully added to CollectionBuilder. Your goal is to follow the class data dictionary and remediate and refine 3 metadata records (the rows in the Google Sheet) associated with a unique object found in the dataset. 

After the class has completed the activity, objects and metadata records will be added into the Beyond Toxic Data Repository (CollectionBuilder) by the instructor.

**Materials for the Activity**
- [Google Drive Folder](https://drive.google.com/drive/folders/1bopMHqUv2hCE3TVZoARPE7maPN4oQOsF?usp=sharing). Here is a list of what you will find in the folder:
    - The class data dictionary. Use this data dictionary as a metadata guide supporting the requirements for CollectionBuilder ingest and descriptive metadata
    - The spreadsheet (Google Sheet). Use this spreadsheet contains the metadata you will use to remediate and refine the metadata. Everyone in the class will use this spreadsheet to catalog objects.
- [Object Directory](https://github.com/learn-static/eng-470/tree/main/objects). Here is where you will find the files for all objects in the Beyond Toxic Dataset.

**❗ Important Note to Learners ❗**
Everyone is going to be working in the same space. Before starting the activity, you will need to find the objects and metadata that are assigned to you.  

First, located the metadata record that has been assigned to you.
1. Open the [Google Drive Folder](https://drive.google.com/drive/folders/1bopMHqUv2hCE3TVZoARPE7maPN4oQOsF?usp=sharing)
2. Open the spreadsheet
3. Find the column header titled: "Cataloger". This metadata field identifies what metadata records are assigned to you. By the way, this is a version of administrative metadata not seen by your data users.

Second, locate the object's file that is assigned to you.
1. Open [Object Directory](https://github.com/learn-static/eng-470/tree/main/objects).
2. Find the object you have to catalog
3. Read and review the object before you start refining and remediating metadata

**Begin Your Metadata Refinement and Remedition Proccess**

1. Open [Google Drive Folder](https://drive.google.com/drive/folders/1bopMHqUv2hCE3TVZoARPE7maPN4oQOsF?usp=sharing) and Open [Object Directory](https://github.com/learn-static/eng-470/tree/main/objects)
2. Locate the objects and metadata records that you will be working with
3. Open the class data dictionary, which is located in the [Google Drive Folder](https://drive.google.com/drive/folders/1bopMHqUv2hCE3TVZoARPE7maPN4oQOsF?usp=sharing).
4. Read the data dictionary to understand what the metadata standard is asking you to do with your object's metadata record
5. Locate the folllowing metadata fields identified in the data dictionary
    - objectid
    - filename
    - subjects
    - format
    - longitude and latitude
    - rightsstatement
6. For each metadata record and the field identified in the previous step, compare the values against how the data dictionary wants you to conform to it's standard.

    - Look for discrepencies to correct
    - Some spreadsheet cells will have values requiring remediation and refinement 
    - Some cells will not have any data. If there is not a value in a cell then add one according to the data dictionary.
7. Start correcting your metadata records.

8. Once you are done let the Instructor know. When everyone has completed the activity they will demo how objects and the metadata sheets are uploaded to CollectionBuilder.

**If you have questions be sure to raise your head and ask for help from the instructor.**

