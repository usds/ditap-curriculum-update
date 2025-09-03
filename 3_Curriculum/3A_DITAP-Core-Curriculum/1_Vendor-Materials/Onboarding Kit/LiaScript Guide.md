# LiaScript Guide


## Introduction
This document provides course vendors with an overview of LiaScript, its use in this project, and step-by-step guidance for exporting SCORM packages for LMS delivery. It serves as both an introduction to the tool and a practical operational guide.

## What is LiaScript?

### Overview
LiaScript is an open-source framework for creating interactive eLearning courses using simple, text-based authoring. It enables course designers to build engaging, self-paced learning experiences with multimedia, interactive assessments, and scenario-based exercises—without requiring advanced programming skills.

### Key Features for Course Vendors
- **Interactive Elements:** Quizzes, polls, knowledge checks, and branching scenarios.  
- **Self-Paced Modules:** Supports asynchronous learning.  
- **Multimedia Integration:** Images, audio, video, and other resources.  
- **Export Options:** HTML for web, PDF for offline, and SCORM for LMS integration.  
- **Lightweight & Accessible:** Text-based format supports accessibility standards, including screen reader compatibility, alt text for images, keyboard navigation, and captions/transcripts.  

---

## Why LiaScript Was Chosen for This Project
LiaScript was selected for its ability to combine interactive, scenario-based learning with efficient development and iteration. It allowed the team to:

- Rapidly prototype modules and integrate SME feedback.  
- Maintain version control and collaborative editing across multiple contributors.  
- Ensure quality and consistency across modules while preparing for LMS deployment.  
- Support accessibility compliance (Section 508/WCAG), ensuring the refreshed curriculum is usable for all learners.  

---

## How LiaScript Was Used in This Project

### Project Goals
The goal was to create a modular, interactive version of the refreshed DITAP curriculum that supports learners in understanding complex concepts through hands-on activities, scenarios, and self-paced exercises.

### Module Design Approach
- **Self-Paced Content:** Core readings, instructions, and multimedia at learner’s own pace.  
- **Interactive Exercises:** Embedded knowledge checks and practice opportunities.  
- **Scenario-Based Learning:** Case studies and simulations mirroring real-world challenges.  
- **Accessibility in Practice:** Modules were built with accessibility in mind, including clear text structure, descriptive links, and interactive elements designed to be usable by keyboard and screen readers.  

### Benefits Achieved
Using LiaScript, the team was able to:
- Develop highly interactive, learner-centered content quickly.  
- Maintain quality and consistency across modules.  
- Export content as SCORM packages for smooth LMS deployment.  
- Provide a scalable, engaging learning experience that remains accessible and inclusive for all users.  

---

## Exporting Courses from LiaScript

### Overview of Export Options
LiaScript provides multiple export options to make courses usable in different contexts:
- **SCORM Package:** Ideal for LMS integration, tracks learner progress, completion, and scores.  
- **HTML Export:** Runs as a standalone web course in any modern browser.  
- **PDF Export:** Provides a static version of the course for offline reference or documentation purposes.  

>For LMS deployment, the **SCORM package** is the recommended format.

### Preparing the Course for Export
Before exporting, ensure the course is fully prepared:
- Complete all modules with content and interactive elements.  
- Test quizzes, multimedia, and knowledge checks.  
- Verify media assets are properly linked and functional.  
- Check scoring and completion logic (pass/fail, quiz requirements).  

### SCORM Export Steps
1. **Open the LiaScript Course in the Exporter**  
   Access via LiaScript platform or authoring interface.  

2. **Select the SCORM Export Option**  
   Choose SCORM from the export menu.  

3. **Configure SCORM Settings**  
   - *Course Title*  
   - *SCORM Version* (1.2 or 2004 depending on LMS)  
   - *Completion Criteria*  

4. **Generate the SCORM Package**  
   Export into a `.zip` file for LMS upload.  

5. **Download the SCORM Package**  
   Save securely for upload.  

---

## Importing SCORM into an LMS
Steps to upload the SCORM package:
1. Log in with admin/course creator credentials.  
2. Navigate to SCORM Upload Section for your LMS (i.e., Course Import, SCORM Packages, Add Content, etc.).  
3. Upload the SCORM .zip File.  
4. Configure course Settings (enrollment, completion, pass/fail).  
5. Test the course as a learner.  

---

## Tips and Considerations
- Some LMS platforms may need adjustments for interactivity.  
- Always test in a sandbox environment before deployment.  
- Confirm all media assets are included.  

---

## Troubleshooting & Tips

### Common SCORM/LMS Issues
- **Multimedia Not Displaying**  
  Check file links, formats, and browser support.  

- **Branching or Scoring Not Tracked**  
  Configure completion tracking properly and test in sandbox.  

- **Browser Compatibility Issues**  
  Recommend modern browsers (Chrome, Firefox, Safari, Edge).  

### LiaScript-Specific Considerations
- **Anchors & Internal Links**: Test navigation within LMS.  
- **Dynamic Content Rendering**: Ensure LMS allows scripts.  
- **SCORM Version Selection**: Use SCORM 1.2 (broad compatibility) or 2004 (advanced tracking).  
- **Testing & Validation**: Always preview as a learner.  

---

## Best Practices for Vendors
- Maintain consistent file and folder structures.  
- Document LMS-specific configurations.  
- Keep backups of LiaScript source files.  
- Work with LMS administrators for troubleshooting.  

---

## Additional Resources
- [LiaScript Website](https://liascript.github.io/)  
- [LiaScript Documentation](https://liascript.github.io/docs/)  
- [LiaScript Exporter](https://liascript.github.io/exporter/)  
- LiaScript Supported LMS list (via Exporter)  
- [LiaScript GitHub Issues](https://github.com/LiaScript/LiaScript/issues)  
- [Community Discussions](https://github.com/orgs/LiaScript/discussions)  

### Recommended Workflow for Updates
- Maintain version control (Git).  
- Test exports in sandbox LMS.  
- Document LMS-specific settings.  
