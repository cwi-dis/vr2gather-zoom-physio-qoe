# vr2gather-zoom-physio-qoe

## Description
- This dataset contains subjective ratings collected during a user study comparing two systems: VR2Gather (HMD) and Zoom in a physiotherapy use case.

## SimulatorSickness_Raw_Ori file
- Subjects ID 1 to 18, Session_0 is filled after the pre-screening, Session_1 is filled after the HMD session, and Session_2 is filled after Zoom session
- Subjects ID 19 to 36, Session_0 is filled after the pre-screening, Session_1 is filled after the Zoom session, and Session_2 is filled after HMD session

## NASA_TLX_Raw_Ori_HMD file
- Subjects ID 1 to 18, filled in NASA TLX after the HMD session in session 1
- Subjects ID 19 to 36, filled in NASA TLX after the HMD session in session 2

## NASA_TLX_Raw_Ori_Zoom file
- Subjects ID 1 to 18, filled in NASA TLX after the Zoom session in session 2
- Subjects ID 19 to 36, filled in NASA TLX after the Zoom session in session 1

## All_Questions_Raw_Data file
- Each row represents a single response to a question answered by a participant after completing an exercise or a full session.
- Exercise: Indicates the ID of the exercise shown. Exercises appear in randomized order, reflecting the actual sequence experienced by each participant.
	- Values 0 and -1 are placeholders. These values do not correspond to actual exercises.
- Device: The system used — either HMD (VR2Gather) or Zoom.
- Group: The participant group (Group 1 or Group 2), used to balance order effects (some start with HMD, others with Zoom).
- Questions 1–3: Asked after each individual exercise.
- Questions 4–11: Asked once after all three exercises per device.
- Participants filled in three questions (1–3) after each exercise. After completing all three exercises with a device, they answered additional questions (4–11) regarding their overall experience with that system.

