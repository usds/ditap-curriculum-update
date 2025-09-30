## SCORM file structure

Each module has separate SCORM 1.2 and SCORM 2004 .zip packages for each sprint within that module.

Each .zip can be downloaded from the "Artifacts" section of this release (below) and is a self-contained SCORM package ready for LMS import.

This design makes it easy for vendors to:

* Download only the sprint they need without re-downloading the entire course.
* Replace a single SCORM file in their LMS if updates are released (instead of re-importing all files).
* Keep their LMS organized by mapping each sprint to a lesson, topic, or module.

This approach reduces vendor workload and ensures smoother updates when future revisions are made.

## Module 0 - Foundation
- Module0_Pre-Assessment
- Module0_Orientation

## Module 1 - Digital Services Landscape  
- Module1_Sprint1 (Digital Services Landscape)
- Module1_Sprint2 (Methods, Roles, and Sources)
- Module1_Sprint3 (Tech Bootcamp)

## Module 2 - Preparation
- Module2_Sprint1 (Agency Readiness)
- Module2_Sprint2 (Stakeholder Mapping)
- Module2_Sprint3 (Defining Success)
- Module2_Sprint4 (Market Research)

## Module 3 - Acquisition Strategy
- Module3_Sprint1 (Acquisition Strategy)
- Module3_Sprint2 (Solicitation Development)
- Module3_Sprint3 (Evaluation)

## Module 4 - Contract Management
- Module4_Sprint1 (Service Delivery Management)
- Module4_Sprint2 (Performance Measurement)
- Module4_Sprint3 (Contract Kickoff)
- Module4_Sprint4 (Contract Management)

## Module 5 - Leadership & Change
- Module5_Sprint1 (Individual Leadership)
- Module5_Sprint2 (Organizational Change)
- Module5_Sprint2_Post-Assessment (Final Assessment)

**Total: 19 SCORM packages**

All packages were exported using the [LiaScript SCORM exporter](https://liascript.github.io/exporter/).

---

## Import Instructions

1. Download the files you need.
2. Do not unzip the .zip file. Import the .zip directly into your LMS.
3. In your LMS, go to Course Import > SCORM Upload (terminology may vary).
4. Import each module separately and arrange them in the correct order.
5. Confirm SCORM settings in your LMS:
   * SCORM version: *[1.2]* or *[2004]* as appropriate.
   * Completion: *[e.g., Passed/Completed, Viewed All Slides]*
   * Tracking: *[quiz score, progress, or completion – specify]*

---

## Notes for LMS Administrators

* Ensure you download the right SCORM version package for each module, based on your LMS supported standards.
* These are 19 separate SCORM packages; your LMS may treat each one as a lesson/topic.
* If your LMS supports multi-SCORM packaging, you may be able to group them into one "master course."
* Vendors should replace older SCORM packages with the updated .zip files if available.
* Vendors can also generate their own SCORM packages using the [LiaScript exporter](https://liascript.github.io/exporter/).

---

## Troubleshooting

* If an import fails:
  * Verify you are importing the .zip (not the extracted folder).
  * Confirm your LMS supports the specified SCORM version.
  * Check LMS file size limits.
* Contact your LMS Technical Support for further assistance.
