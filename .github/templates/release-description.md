## SCORM file structure

Each module has separate SCORM 1.2 .zip packages for each sprint within that module. Each .zip is a self-contained SCORM package ready for LMS import.

This design makes it easy for vendors to:

* Download only the sprint they need without re-downloading the entire course.
* Replace a single SCORM file in their LMS if updates are released (instead of re-importing all files).
* Keep their LMS organized by mapping each sprint to a lesson, topic, or module.

This approach reduces vendor workload and ensures smoother updates when future revisions are made.

## Module 0 - Foundation
- Module0_Pre-Assessment.zip
- Module0_Orientation.zip

## Module 1 - Digital Services Landscape  
- Module1_Sprint1.zip (Digital Services Landscape)
- Module1_Sprint2.zip (Methods, Roles, and Sources)
- Module1_Sprint3.zip (Tech Bootcamp)

## Module 2 - Preparation
- Module2_Sprint1.zip (Agency Readiness)
- Module2_Sprint2.zip (Stakeholder Mapping)
- Module2_Sprint3.zip (Defining Success)
- Module2_Sprint4.zip (Market Research)

## Module 3 - Acquisition Strategy
- Module3_Sprint1.zip (Acquisition Strategy)
- Module3_Sprint2.zip (Solicitation Development)
- Module3_Sprint3.zip (Evaluation)

## Module 4 - Contract Management
- Module4_Sprint1.zip (Service Delivery Management)
- Module4_Sprint2.zip (Performance Measurement)
- Module4_Sprint3.zip (Contract Kickoff)
- Module4_Sprint4.zip (Contract Management)

## Module 5 - Leadership & Change
- Module5_Sprint1.zip (Individual Leadership)
- Module5_Sprint2.zip (Organizational Change)
- Module5_Sprint2_Post-Assessment.zip (Final Assessment)

**Total: 19 SCORM packages**

All packages were exported using the [LiaScript SCORM exporter](https://liascript.github.io/exporter/).

---

## Import Instructions

1. Download the files you need.
2. Do not unzip the .zip file. Import the .zip directly into your LMS.
3. In your LMS, go to Course Import > SCORM Upload (terminology may vary).
4. Import each module separately and arrange them in the correct order.
5. Confirm SCORM settings in your LMS:
   * SCORM version: *[1.2]*
   * Completion: *[e.g., Passed/Completed, Viewed All Slides]*
   * Tracking: *[quiz score, progress, or completion – specify]*

---

## Notes for LMS Administrators

* These are 19 separate SCORM packages; your LMS may treat each one as a lesson/topic.
* If your LMS supports multi-SCORM packaging, you may be able to group them into one "master course."
* File sizes vary; ensure your LMS supports uploads of at least ~125 MB.
* For large downloads, use a stable connection to avoid corruption.

---

## Versioning

* Current release: {{RELEASE_DATE}}
* Vendors should replace older SCORM packages with the updated .zip files if available.
* Vendors can also generate their own SCORM packages using the [LiaScript exporter](https://liascript.github.io/exporter/).

---

## Troubleshooting

* If an import fails:
  * Verify you are importing the .zip (not the extracted folder).
  * Confirm your LMS supports the specified SCORM version.
  * Check LMS file size limits.
* Contact your LMS Technical Support for further assistance.

---

**Organization:** USDS Digital IT Acquisition Professional Training Program (DITAP)  
**Format:** SCORM 1.2  
**Generated:** {{RELEASE_DATE}}