---
title: Data Curation and Metadata Interoperability Lesson Plan
layout: about
permalink: /dcmilessonplan.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="bethel-school_1930" %}

{% include feature/nav-menu.html sections="Overview;Instructor Lesson Plan;Notes for Learning Sequence Advisory Board Reviewer" %}

# The Data Curation and Metadata Interoperability Lesson Plan

# Note for Learning Sequence NEH Advisory Board Reviewer
Please work through this lesson plan and the learning sequence. You do not need to complete the "Let's reflect" activity. The only activity you need to complete is the "Metadata Remediation and Refinement Activity". This activity is found toward the end of the learning sequence.

The Google Folder contains all the contents you need to complete the activity. The metadata sheet does not contain all the metadata using in the digital collection.

Once you have completed the learning sequence, you should then act as if you are the instructor and upload objects and metadata into your own CollectionBuilder GitHub repository. This will show the NEH Learn-Static team if you were able to complete the metadata remediation and refinement activity.

If you are unsure how to setup a CollectionBuilder repository or upload objects and metadata into it then visit the [CollectionBuilder documentation page](https://collectionbuilder.github.io/cb-docs/) for instructions.

## Overview
**About the lesson:** This lesson was designed as part of the Learn-Static initiative funded by the National Endowement for the Humanities. The lesson's intention is for educators be able to reuse and adapt within their own digital humanities classroom projects. It serves to support the digital project's greater goal of acting as an archival recovery project that seeks to conform Beyond Toxic's collected primary sources to a metadata standard and made publicly available online for research and education purposes.

Within the ENG 470 Technologies and Text Capstone class context, this lesson represents the first of multiple instruction sessions that introduces learners to describing and analyzing primary sources and making them publicly available online through CollectionBuilder.

**Where can I find the learning sequence?** The learning sequence for this lesson plan can be found at [Data Curation and Metadata Interoperability Learning Sequence](https://learn-static.github.io/eng-470/datacurationadninteroperability.html)

**Who designed the lesson plan and learning sequence?** Kate Thornhill, University of Oregon Libraries Digital Scholarship Librarian, in consultation with Mattie Burket, Assistant Professor of Digital Humanities.

**About the data:** All source materials came from the [Lane County History Museum's archives](https://www.lchm.org/) and the [University of Oregon digital repositories, Scholars' Bank](https://scholarsbank.uoregon.edu/) and the [Oregon Digital Newspapers](https://oregonnews.uoregon.edu/), and were collected and supplied to the class by Beyond Toxic, a nonprofit environmental justice organization based in Eugene, Oregon. Item-level metadata used for the class' metadata remediation and refinement activity was supplied by the course instructor.

## Instructor Lesson Plan
### Description
The goal of of the Data Curation and Metadata Interoperability lesson is for learners to be able to standardized primary source metadata records in accordance with CollectionBuilder's data ingest requirements that have been identified in the class data dictionary.

Two classes are needed to support learners. After the lecture and reflection exercise, learners will need more time to complete the hands-on refinement and remediation activity and watch the instructor add objects and the .csv spreadsheet to the GitHub hosted Beyond Toxic Data Repository.

### Duration
Two 70 minute classes. Two classes are suggested because students will need more time to complete the refinement and remediation activity and see the instructor add objects and metadata to a CollectionBuilder GitHub repository.

### Audience
Post-secondary learners: Undergraduate students, graudate students

### Learning Outcomes and Educational Standards Alignment
**Learning Outcomes:**
- Define data curation and interoperability within the context of digital collections
- Recognize metadata standards applied to data found in the Digital Public Library of America way for metadata to be interoperable 
- Use a class data dictionary to correct and add descriptive and technical metadata to the Beyond Toxic Dataset
- Apply CollectionBuilder's system requirements so objects and metadata can be added to a central data repository

**Learning Outcomes Alignment with International Society for Technology in Education (ISTE) Standards for Students**:

[1.5 Computational Thinker.](https://www.iste.org/standards/iste-standards-for-students) 

1.5b Students collect data or identify relevant data sets, use digital tools to analyze them, and represent data in various ways to facilitate problem-solving and decision-making.

### Learning Sequence Materials and Teaching Preparation
**Materials for Instructor:**
- In-person classroom
- Laptop or desktop computer
- Projector, if using a laptop then make sure to have the approproate adapters to connect to your laptop
- [Data Curation and Interoperability](/datacurationadninteroperability.html). This contains the lecture and activity materials.
- CollectionBuilder repository setup on GitHub, ready for objects and metadata to be added to it. You should set this up ahead of time. The goal after learner's are finished with the metadata refine and remediation activity is to have them see how data is rendered through the CollectionBuilder repository interface.

**Materials for Learners:** 
- Laptop or desktop computers
- [Access to the Data Curation and Metadata Interoperability Learning Sequence](/datacurationadninteroperability.html)
- 3 objects and accompanying metadata records assigned to each leaner learner. You as the instructor will need to assign metadata records to each student. Add their first and last name as a values into the appropriate cells under the "Cataloger" field located in the metadata spreadsheet.

*Access to materials for the in-class activity*

[Google Drive Folder](https://drive.google.com/drive/folders/1bopMHqUv2hCE3TVZoARPE7maPN4oQOsF?usp=sharing). It is suggested for the class activity to set the folder permissions to editable by anyone. 

Here is a list of what you will find in the folder:
- The class data dictionary. Use this data dictionary as a metadata guide supporting the requirements for CollectionBuilder ingest and descriptive metadata
- The metadata spreadsheet (Google Sheet). Use this spreadsheet contains the metadata you will use to remediate and refine the metadata. Everyone in the class will use this spreadsheet to catalog objects.

[Object Directory](https://github.com/learn-static/eng-470/tree/main/objects). Here is where you will find the files for all objects in the Beyond Toxic Dataset.

### Lesson Outline

#### Introduction - 5 minutes
1. Class gets settled
2. Brief overview of what will be covered in the lesson. 

#### Teaching Strategy #1 - 15 minutes

Complete the following lecture components for the learning sequence
- Data Curation and Metadata for Digital Collections
- What is Metadata?
- Digital Collections Metadata in Context: The Digital Public Library of America (DPLA)

#### Comprehension Check #1 - 15 minutes

Complete the following comprehension check identified in the learning sequence
- Let us reflect! activity

#### Teaching Strategy #2 - 10 minutes

Complete the following lecture components for the learning sequence
- Making Metadata Interoperable with CollectionBuilder
- How does interoperability relate to the Beyond Toxic Dataset?

#### Teaching Strategy #3 - 10 minutes

**Show and Tell**

How to remediate and refine metadata according to the class' data dictionary.

Instructor should demo how they fix metadata so it follows the class' data dictionary, which uses CollectionBuilder's ingest requirements. Place emphasis on learning about standardizing metadata for CollectionBuilder ingest because this lesson is not about fixing resource descriptions.

Be sure to do the following:
- Show learners where to find the object directory, the metadata sheet, and the class data dictionary
- Show learners how to follow data entry instructions set by the data dictionary. Focus on the following fields when demo'ing how to correct metadata. Select only one field requirements to model for learners to do on their own.
    - objectid
    - filename
    - subjects
    - format
    - longitude and latitude
    - rightsstatement

Once the demo is finished the learners should follow the steps you took to correct metadata so it conforms to CollectionBuilder's ingest standards.

#### Comprehension Check #3 - 30 minutes
- Learners complete the Metadata Remediation and Refinement Activity

After learners have completed the activity then demonstrate how to upload objects and metadata into CollectionBuilder. 

Remember to do the following:
- Show the learners how objects and metadata appear on item pages. 
- Briefly compare how the data is rendered on a webpage v.s. displayed in a spreadsheet. 

If there is no time to do this in-person then record a video of you uploading objects and metadata to CollectionBuilder. Performing this demonstration allows learners to see if there have been any data entry errors and also how metadata and objects visually represented in a user interface vs a spreadsheet. Be sure to share your video with students.
