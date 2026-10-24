# Requirements

## Functional requirements (what the system must DO)
- **FR1:** The system shall accept an uploaded video file in MP4 format of up to 3 minutes.
- **FR2:** The system shall reject a file that is not a valid MP4 and show an error message that names the problem.
- **FR3:** The system shall convert the speech in an accepted video into a text transcript.
- **FR4:** The system shall extract one frame per second from an accepted video for analysis.
- **FR5:** The system shall classify each accepted video as "Fake" or "Real".
- **FR6:** The system shall show a confidence score between 0% and 100% next to each classification.
- **FR7:** The system shall display the transcript beside the classification.
- **FR8:** The system shall let the user mark a classification as correct or incorrect.

## Non-functional requirements (how the system must PERFORM)
- **NFR1 (Performance):** The system shall return a classification within 60 seconds for a 60-second video on a laptop with 8 GB of RAM.
- **NFR2 (Accuracy):** The classifier shall reach a macro F1-score of at least 0.75 on a held-out test set that was not used for training.
- **NFR3 (Privacy and security):** The system shall delete every uploaded video within 24 hours of upload and shall not share uploaded videos with any third party.
- **NFR4 (Usability):** A first-time user shall be able to upload a video and read the result in no more than 3 clicks, without reading instructions.
- **NFR5 (Reliability):** The system shall show an error message, and not crash, for 100% of the invalid test files in the test set (corrupted file, wrong format, empty file, video with no sound).

## Traceability
| Requirement | Supports user story |
|-------------|--------------------|
| FR1, FR5, FR6 | US1 |
| FR3, FR7 | US2 |
| FR8 | US3 |
