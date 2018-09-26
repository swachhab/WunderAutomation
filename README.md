# WunderAutomation
Wunder Automation task to do write automation test scenarios on Android mobile application.

# Selected App
FasTip

# Quick Start (MAC Machine)
* Clone git
* pip install -r requirements.txt
* appium -p 4723
* cd Batch
* Execute "Run_Command.command"

# Tools/Languages Used
* Robot Framework
* Python
* Android SDK
* Xcode(In case to automate iOS)
* Mac Machine(Only Mac Support - I don't have windows machine with me, So created and tested on mac only)
* Python Libraries

# Requirements
* All the above tools and mac machine
* Environment Path Settings in Bash_Profile for (Java, Android, Python)SDKs.
* 

# Test Cases
* Test Case 1: 
  # Summary: Test Case to Calculate Tip
  # Test Steps:
  * Launch Application
  * Validate All UI Elements
  * Enter Bill Amount
  * Get Tip Percentage
  * Calculate Total Amount
  * Click On Calculate Tip
  Validations
  * All UI Elements must be present
  * Total Amount on UI Should Be Equal To Calculated Amount
  
* Test Case 2: 
  # Summary: Test Case to Change Default Tip
  # Test Steps:
  * Launch Application
  * Validate All UI Elements
  * Navigate To Settings Page
  * Click Enter New Tip Amount
  * Get Back To Home Screen
  
  Validations
  * All UI Elements must be present
  * Value Of Tip Should be Changed on Home Page As On Settings Page
  * Total Amount Should be correct based on new Tip Percentage.
 
 # Folder Structure
 
 
 
 
 # How To Execute Test Cases
 FrameworkArchitecture.png
 ![alt text](https://github.com/swachhab/WunderAutomation/blob/master/FrameworkArchitecture.png)
 
 
 * Execution Reports
 [Report](http://robotframework.org/robotframework/latest/libraries/BuiltIn.html)



* Important Links
[Keyword Documentation](http://robotframework.org/robotframework/latest/libraries/BuiltIn.html)
