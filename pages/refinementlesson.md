---
title: Metadata Refinement Lesson Plan
layout: about
permalink: /refinementlesson.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://cdil.lib.uidaho.edu/images/palouse_sm.jpg" %}

{% include feature/nav-menu.html sections="Overview;Lesson Plan;Activity Instructions for Learners" %}

## Overview: The Metadata Refinement Lesson
**About the lesson:** This lesson was designed as part of the Learn-Static initiative funded by the National Endowement for the Humanities. The lesson's intention is for educators be able to reuse and adapt within their own digital humanities classroom projects. It serves to support the digital project's greater goal of acting as an archival recovery project that seeks to conform Beyond Toxic's collected primary sources to an international metadata standard and made publicly available online for research and education purposes. 

Within the ENG 470 Technologies and Text Capstone class context, this lesson represents the first of multiple instruction sessions that introduces learners to describing and analyzing primary sources and making them publicly available online through CollectionBuilder. 

**About the data:** All source materials came from the Lane County History Museum's archives and the University of Oregon digital repositories, Scholars' Bank and the Oregon Digital Newspapers, and were collected and supplied to the class by Beyond Toxic, a nonprofit environmental justice organization based in Eugene, Oregon. Item-level metadata used for class refinement was supplied by the course instructor.

## Lesson Plan for Instructor
**Description:** The goal of of the Metadata Refinement Lesson is for learners to be able to standardized primary source item-level metadata in accordance with CollectionBuilder's data interoperability requirements and the class data dictionary.

**Duration:** 70 minutes

**Audience:** Undergraduate students, graudate students

**Learning Outcomes:**
- Recognize that metadata is a major part of data curation
- Apply metadata refinements to the Beyond Toxic digital collection using the class data dictionary so items can be added to CollectionBullder

**Alignment with International Society for Technology in Education (ISTE) Standards for Students**:

[1.5 Computational Thinker.](https://www.iste.org/standards/iste-standards-for-students) 

1.5b Students collect data or identify relevant data sets, use digital tools to analyze them, and represent data in various ways to facilitate problem-solving and decision-making.

**Materials for Learners:** 
- Laptop or desktop computers
- Data Dictionary Metadata Sheet (Google Sheets)
- Object Storage Location
- 3 objects and metadata to remediate per student
    
**Materials for Instructor:**
- Laptop
- Slides
- In-person Classroom
- CollectionBuilder repository setup on GitHub, ready for objects and metadata to be added to it

**Lesson Outline**

*Introduction* - 5 minutes
1. Class gets settled
2. Brief overview of what will be covered in the lesson. 

*Teaching Strategy* #1 - 10 minutes

Lecture about what is data curation and interoperability using the presentation slides.

*Comprehension Check* - 10 minutes

Ask students to perform a 3, 2, 1 reflect exercise. They should take 2 minutes to write using a laptop or paper and pen while respond to the following questions.The remaining time should be for report outs from a few students. Focus should be mainly on question 3 responses.
- What are 3 things you found interesting?
- What are 2 things you learned?
- What is 1 thing you still have a question about?

*Teaching Strategy #2* - 10 minutes

- Lecture about what is a data dictionary using the slide presentation, and explain how it connects to CollectionBuilder's interoperability and ingest requirements.

*Teaching Strategy #3* - 10 minutes

Show and Tell - How to refine metadata according to the class' data dictionary.

Instructor should demo how they fix metadata so it follows the class' data dictionary, which uses CollectionBuilder's ingest requirements. Place emphasis on learning about standardizing metadata for ingest. This lesson is not about describing resources.

- Show learners where to find object files, the metadata sheet, and the data dictionary
- Show learners how to follow data entry instructions set by the data dictionary. Focus on the following fields when demo'ing how to correct metadata:
    - objectid
    - filename
    - subjects
    - format
    - longitude and latitude
    - rightsstatement

Once the demo is finished the learners should follow the steps you just took to correct metadata so it conforms to CollectionBuilder's ingest standards.

After learners have completed the activity, and only if there is time, then demonstrate how to upload objects and metadata into CollectionBuilder. Show the learners how objects and metadata appear on item pages. Briefly compare how the data is rendered on a webpage v.s. displayed in a spreadsheet. If there is no time then either record a video of you uploading objects and metadata, and how they render, or perform the upload during the next class. Performing this demonstration allows learners to see if there have been any data entry errors. If you make a video then share it with your students via the course management system you are using to faciliate your class.

# Activity Instructions for Learners - 20 minutes
**Note to Instructors:** Be aware that you willl need to assign 2-3 items per student. This lesson has been structured for individual work, but students can also work in groups to accomplish the activity.

**Activity Goal:** Correct the metadata for three objects in the Beyond Toxic dataset. Once the dataset has been corrected your Instructor will upload the dataset to CollectionBuilder.

**Materials for the Activity**
- [Google Drive Folder](https://drive.google.com/drive/folders/1bopMHqUv2hCE3TVZoARPE7maPN4oQOsF?usp=sharing). This folder contains all the objects in the collection, metadata sheet, and data dictionary to use for the activity.
    - The class data dictionary
    - The metadata sheet (Google Sheets)
    - The objects

Important Note: The folder and contents above contains materials meant for this activity demo. There are three items that need remediation. A complete dataset for an entire class to work on should be supplied by the Instructor.

**The Steps**
1. Go to the Beyond Toxic digital collections metadata refinement folder located in Google Drive. There should be objects (newspapers, images, and reports), a metadata sheet, and the class data dictionary.
2. Review the objects that have been assigned to you. Important Note: Please do not change the filenames for any of the objects.
3. Open the metadata sheet (Google Sheets) and find the rows representing your objects. Important Note: This metadata sheet is used by all learners. It is a collaborative cataloging space. Please do not write over anyone else's work.
4. Open the class data dictionary and review the metadata standards that you need to follow.
5. Locate the folllowing fields and make corrections to the values in each cell based on the data dictionary's instructions. Leave the other fields alone because they will be covered in another lesson.
    - objectid
    - filename
    - subjects
    - format
    - longitude and latitude
    - rightsstatement
6. Once you are done let the Instructor know.

# Notes for Learning Sequence Advisory Board Reviewer
Activity Instructions for Learners contains all the contents you need to complete the activity. Please make a copy of the Google Drive folder and work with the contents on your local drive.

Once you have completed the activity, you should then act as if you are the instructor and upload objects and metadata into your own CollectionBuilder repository. 

If you are unsure how to setup a CollectionBuilder repository or upload objects and metadata into it then visit the [CollectionBuilder documentation page](https://collectionbuilder.github.io/cb-docs/) for instructions.