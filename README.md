# AAA-521_Group6_FinalProject
Introduction to Computer Vision (AAI-521-02) Group 6 Final Project Repository 
# Computer Vision Detection: Edge IOT Device for Counting People in a Region of Interest
This project is a part of the AAI-521 course (Introduction to Computer Vision) in the Applied Artifical Intelligence Program at the University of San Diego (USD).  

-- Project Status: Active

## Installation
To use this project, clone the repo on your device using the following commands:

git init
git clone https://github.com/ChristiMoncrief/AAA-521_Group6_FinalProject.git

Selected, required Python packages/libraries:
- Ultralytics
- OpenCV
Built for use on Google Colab

Some sample MP4 files for testing the application are available here:
https://drive.google.com/drive/folders/1zoxgqLXM8NqyILnVPmslzfABh32uInDW

## Project Intro
In an era where managing space occupancy is crucial for both safety and efficiency, our
project embarks on solving a pertinent problem: accurately counting and monitoring the number
of people in designated regions of interest. This challenge, prevalent in scenarios ranging from
public events to private gatherings, demands a solution that is not only precise but also adaptable
to different environments. This solution offers a number of uses case capabilities.
- Monitor the count of people in various zones within a site and get predictable analytics
for customer arrival pattern
- Controlling maximum entry numbers in a particular area and thereby adhere to social
distancing guidelines
- Capture images/video for a customer’s demographics or interest profile, their shopping
journey to get analytics
- Ability to understand busiest and quietest hours
- Set queue occupancy levels, no. of cash counters and measure customer billing/ service
time
- Set and receive alerts and/or notifications via audio, visual, email or text when these
capacity limits are approaching or reached

**Contributors:**
- Adam Graves
- Christi Moncrief
- Reed Oken

**Methods Used:**
- Computer vision
- Machine learning
- IoT

**Project Schedule**

## Meeting 1
- Introductions of the team members
- Discussion/Brainstrom the project ideas, resources, strength and weaknesses
- Next step; Meet 2 on 11/19/23 @ 6:00 PM
## Meeting 2
 - Discussion about project ideas and next steps
   -  Action Items:
      - write up initial draft/framework for project proposal (tonight) [Reed]
      - update ReadMe (tonight) [Christi]
      - contribute to project proposal (tomorrow) [Adam/Christi]
      - approve attaching Adam's IOT project to the proposal for prof reference [Adam]
      - CV Coding [Adam]
      - submit project proposal on behalf of team by tomorrow evening [Christi]
## Project Assignment 4.2 submission
- Submitted 11/20/23
- Christi set meeting #3 for 11/22/23 @ 6:00 PM
## Meeting 3
- Approve the project for the IoT device
- Discuss the approach to Strategy, Design, and Execution
- Assign tasks: Christi to work on documentation of the strategy and code review, Adam to work on code and IoT design, Reed to work on documentation of the design.
- GitHub has been updated and linked into the Colob code
- Next call and due dates set for 11/28/23 @ 5:00 PM PST.
## Code progress
- Test MP4 have been coded to count people in an ROI and assign tranction direction along with confidence scores
- Still need to review issue with identifying the confidence scores on people that no tranction was identified
- Once design for camera use is completed the code will follow
- Initial IoT design is in place, based on Camera, Lidar, Sound, and CO2 sensors.
- Create and export Excel data file for using as a dataset for a monitoring system
## Documentation
- Initial Project documentation is in place and shared
## Meeting 4
- Review project documentation
- Review code and question about:
-   - Frame size
    - Dynamic frame sizing
- Update documentation with IoT design
- Set meeting for 12/7/23 @ 5:00 PM
## Meeting 5
- Christi presented the Slides (PP)
- Dividing the presentations (C:1-3, A:4-6, R:7-9)
- Reed to review the code Adam made and add general camera code
- Christi to complete the Project documentation and review sections that Adam added
- Set up meeting for 12/9/23 @ 5:00 PM
## 12/10/2023 Progress Report
- Finalizing the files required for the project:
  - AAI 521 Team 6 Final Report.docx: Project report
  - AAI521-ProjectRequirements.pdf: Original requirements
  - AAI521_Team6_Final.ipynb: Python Code (Version control)
  - Score-ManualCount-t6.xlsx: The manual counting for setting a test ground truth values
  - people_count.xlsx: The file export from code to the use of the Tableau monitoring system
  - rep_result.mp4: The output MP4 file from the code with tracking and people count
  - Tableau link: https://public.tableau.com/app/profile/adam.graves8577/viz/AAI521-T6/Dashboard1#1
 ## Meeting 6 12/10/2023
 - Finalize code updates
 - Finalize the Project documentation
 - Finalize the Video Presentation
 - Organize the GitHub
## Final Day 12/11/2023
- Organize last changes
- Add the Video presentation to a YouTube link
- Check all links make sure all work
- Finalize the GitHub repository, clean as needed
- Last verifications
- Team sign-off
- Submission of project
## END
