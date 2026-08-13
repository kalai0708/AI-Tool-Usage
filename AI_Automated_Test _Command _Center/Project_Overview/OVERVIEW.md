# AI-Tool-Usage
    AI Tool Usage in Test
# Problem Statement:
    In many projects testers spend time on:
        Taking meeting notes / Go through requirements 
        Writing test cases
        Logging defects
        Creating reports
        Sending status updates
        Preparing release presentations

# Architecture:

          Requirement Meeting
               ↓
           Fireflies
               ↓
        Requirement Summary
               ↓
           Wispr Flow
               ↓
        Test Cases + Bug Reports
               ↓
             Jira
               ↓
              Make
               ↓
        Automated Workflow
               ↓
         Defect Data Export
               ↓
          DataSquirrel
               ↓
         QA Dashboard
               ↓
         ChronicleHQ
               ↓
         Release Presentation

# Use Case 1: Smart Requirement Analysis
  # Tool:
    Fireflies
  # Scenario:
    Suppose a Product Owner explains:
      User login should support password, OTP and Microsoft SSO
      Upload a recorded meeting or attend a Zoom/Teams meeting.
  # What Fireflies Does:
    Generates:
      Transcript
      Summary
      Action Items
      Decisions
  # Example:
    Requirement:
    1. User Login
    2. Microsoft SSO
    3. OTP validation
    4. Forgot Password

# Use Case 2: AI Test Case Creation:
  # Tool
    Wispr Flow
  # Scenario
      Open Word or Notepad.
  # Sample Test Case creation:
    Speak:
      Verify valid login
      Verify invalid login
      Verify expired OTP
      Verify locked account
  # Output:
      TC001 Verify valid login
      TC002 Verify invalid login
      TC003 Verify expired OTP
      TC004 Verify locked account

# Use Case 3: Automated Bug Workflow
  # Tool
      Make
  # Scenario
      Create free accounts:
      Jira
      Gmail
      Microsoft Teams
      Google Sheets
  # Workflow:
    New Critical Bug
          ↓
    Make detected issue
          ↓
    Send Teams Alert
          ↓
    Create Excel Entry
          ↓
    Email Lead
    
  # Deliverable Screenshot
  Show:
    Bug Created → Notification Sent
    
# Use Case 4: Defect Analytics Dashboard:
  # Tool
    DataSquirrel
  # Sample Data By uploading CSV file:
    DefectID,Severity,Module,Status
    D101,High,Login,Open
    D102,Medium,Cart,Closed
    D103,Critical,Payment,Open
    D104,High,Login,Closed
  # DataSquirrel automatically:
    Cleans data
    Creates charts
    Generates insights
    Produces dashboards

# Use Case 5: AI Release Readiness Presentation
  # Tool
    ChronicleHQ
  # Input:
    Project: Ecommerce App
      Total Test Cases = 500
      Passed = 470
      Failed = 20
      Blocked = 10
      
      Defects:
      Critical = 2
      High = 5
      Medium = 8
  # Output:
    Slides will be created with the below topics:
      Project Overview
      Test Coverage
      Defect Summary
      Risks
      Release Recommendation



                                                  # END
    




  
