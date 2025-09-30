# SCORM Packages for Vendors

## SCORM File Structure

Each module contains SCORM 1.2 .zip packages for each sprint within that module. Each .zip is a self-contained SCORM package ready for LMS import.   

This design makes it easy for vendors to:

* Download only the sprint they need without re-downloading the entire course.  
* Replace a single SCORM file in their LMS if updates are released (instead of re-importing all files).  
* Keep their LMS organized by mapping each sprint to a lesson, topic, or module.

This approach reduces vendor workload and ensures smoother updates when future revisions are made.

## Where to Download

SCORM packages are not stored in this folder. Download the **ready-to-import** zips from the project’s **GitHub Releases**.

### Quick steps
1. Open the Releases page:  
   - **Latest:** https://github.com/usds/ditap-curriculum-update/releases/latest  
   - **All releases:** https://github.com/usds/ditap-curriculum-update/releases
2. Open the most recent release (look for the **Latest** badge).
3. Scroll to **Assets**.
4. Download the SCORM `.zip` for each module you need.

> Tip: Bookmark the **Latest** link so you always get the current packages.

### What you’ll find
- One `.zip` per module (SCORM package), ready to import into your LMS.
- Release notes with changes and usage guidance.

### Importing into your LMS
- Use your LMS’s “Import/Upload SCORM” feature and select the downloaded `.zip`.  
- Packages are self-contained to improve compatibility with common LMS settings.

### Questions or issues
- Open an issue here: https://github.com/usds/ditap-curriculum-update/issues  
  Include your LMS name/version, the module zip, the release tag (e.g., `v2`), and any error messages/screenshots.


## Mapping: 

| SCORM file | Markdown file |
| :---- | :---- |
| Module 0 Pre Assessment | 1\_Pre-Program Assessment |
| Module 0 Orientation | 2\_Orientation |
| Module 1 Sprint 1 | 1\_The Digital Services Landscape |
| Module 1 Sprint 2 | 1\_Digital Service Methods, Roles and Sources of Supply |
| Module 1 Sprint 3 | 1\_Digital Service Tech Bootcamp |
| Module 2 Sprint 1 | 1\_Assessing Agency Readiness |
| Module 2 Sprint 2 | 1\_Stakeholder and Customer Mapping |
| Module 2 Sprint 3 | 1\_Defining Success for your Digital Services Acquisition |
| Module 2 Sprint 4 | 1\_Conducting Effective Market Research |
| Module 3 Sprint 1 | 1\_Developing a Successful Acquisition Strategy |
| Module 3 Sprint 2 | 1\_Developing the Solicitation |
| Module 3 Sprint 3 | 1\_Running a Successful Evaluation |
| Module 4 Sprint 1 | 1\_Management of Digital Service Delivery |
| Module 4 Sprint 2 | 1\_Performance Measurement Under Agile Delivery Contracts |
| Module 4 Sprint 3 | 1\_Contract Kickoff |
| Module 4 Sprint 4 | 1\_Contract Management and Problem Resolution |
| Module 5 Sprint 1 | 1\_Leading Change as an Individual |
| Module 5 Sprint 2 | 1\_Leading Organizational Change |
| Module 5 Post Assessment | 2\_Post-Program Assessment |

All packages were exported using the [LiaScript SCORM exporter](https://liascript.github.io/exporter/).  

---

## Import Instructions

1. Download the files you need.  
2. Do not unzip the .zip file. Import the .zip directly into your LMS.  
3. In your LMS, go to Course Import \> SCORM Upload (terminology may vary).  
4. Import each module separately and arrange them in the correct order.  
5. Confirm SCORM settings in your LMS:  
   * SCORM version: *\[1.2\]*  
   * Completion: *\[e.g., Passed/Completed, Viewed All Slides\]*  
   * Tracking: *\[quiz score, progress, or completion – specify\]*

---

## Notes for LMS Administrators

* These are 19 separate SCORM packages; your LMS may treat each one as a lesson/topic.  
* If your LMS supports multi-SCORM packaging, you may be able to group them into one “master course.”  
* File sizes vary; ensure your LMS supports uploads of at least \~125 MB.  
* For large downloads, use a stable connection to avoid corruption.

---

## Versioning
- Each release has a version tag (e.g., `v1`, `v2`).  
- Confirm the tag matches the version your team plans to deploy.
 
* Vendors can also generate their own SCORM packages using the [LiaScript exporter](https://liascript.github.io/exporter/).

---

## Troubleshooting

* If an import fails:  
  * Verify you are importing the .zip (not the extracted folder).  
  * Confirm your LMS supports the specified SCORM version.  
  * Check LMS file size limits.  
* Contact your LMS Technical Support for further assistance. 

