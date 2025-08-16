# Pet-Feeder-Project
This project test our knowledge and skills in applying the Solving Problem Process taught during lecture and tutorial. The tasks involved are understanding the problem’s business rules, tackling the challenge by implementing the problem-solving process, and proposing a suitable solution using nothing else than common sense. 

## 📘 Project Overview
This project is a logic simulation for an **automated pet feeder system**, developed as part of Assignment 1 for the University of Canberra's Introduction to Information Technology course. The system is designed to dispense food at scheduled times, monitor consumption, and alert staff if issues arise.

## 🚀 Features
- Dispense food at scheduled times (e.g., 08:00 and 18:00)
- Monitor food level and bowl weight
- Alert staff if food is not eaten or bin is empty
- Continuous operation with real-time checks

## 🧠 System Design
### Inputs
- Feeding Time (RTC)
- Food Level Sensor
- Bowl Weight Sensor

### Outputs
- Servo Motor (dispense food)
- Alert System (notify staff)

### Logic Flow
1. Check current time
2. If feeding time:
   - Check food level
   - If sufficient:
     - Dispense food
     - Wait 10 minutes
     - Check bowl weight
     - If unchanged → Send alert
   - Else → Send alert

## 📁 Folder Structure
├── Step1_Analysis/         # Problem definition and system sketch
├── Step3_Flowchart/        # Flowchart diagram of the logic
├── Step4_Word_Code/        # Word code implementation
├── TestCases/              # Test scenarios and expected outcomes
└── README.md               # Project documentation

## 🚀 Usage Instructions
1. Clone the repository:
   git clone https://github.com/yourusername/pet-feeder-project.git

2. Navigate to the project directory:
   cd pet-feeder-project

3. Explore the folders to view analysis, flowchart, and word code.

4. Use Draw.io to open the flowchart and edit as needed.

5. Review the Word Code and test cases to understand the logic.

## 🙏 Acknowledgments
- University of Canberra – Introduction to Information Technology (IIT) Course
- Microsoft Copilot – for logic refinement, documentation, and AI integration
- Draw.io – for flowchart creation
