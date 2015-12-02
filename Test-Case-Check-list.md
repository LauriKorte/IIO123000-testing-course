## Test case review checklist 

[According Qualiance](https://www.qualitance.com/blog/test-case-review-checklist)

"Quality Attributes:
  Accurate - tests what the description says it will test.
  Economical - has only the steps needed for its purpose
  Repeatable, self standing - same results no matter who tests it.
  Appropriate - for both immediate and future testers
  Traceable - to a requirement
  Self cleaning - returns the test environment to clean state"



| Checked topic | OK /NOK |
| :----: | :----: |
| Test Case name is self explanatory -  all scripts use same naming convention (ex: check_search_language) | :-1: |
| Detailed description in test case  - What is the test case supposed to check, detailed explanations for each test script | :-1: |
| Test script name is self explanatory  , easy to understand what module is the test subject, Test script type is defined. | |
| Action's are simple and clearly defined. | |
| Expected results are simple and clearly define. | |
| Quotes from specifications are presents in the expected results. | |
| Test script objective is defined or clear to understand. | |
| If pre-requisites (for executing ) are necessary they are clearly defined. | |
| Inter-case dependecies - list of test cases that must be executed before test case  | |
| Test data is embedded in test test script.  | |
| Ensure that too many things are not included to be verified under one expected output. (max 3)  | |
| Expected Results should clearly state how the system should respond to the user actions given in each step/action.   | |
| Ensure that separate cases are written for multiple verifications of the application’s behavior.- iteration | |
| Vague statements like “Appropriate message/value/screen” etc, should not be part of  expected result. Every detail should be clearly spelt out. No copy paste from UI Specs in   | |
| steps description is made. | |
| Test script leaves the testing enviroment clean  | |
| Does not take more then 20 minutes to execute test script ( per iteration, if test script  contains more then one)  | |
| Does not exceed more then 15 steps , excluding script initialization, termination and clean up(per iteration , if test script contains more then one)  | |
| Ensure the flow of the test is clear | |
| Naming convention : sections, tabs , elements are wrtitten in bold.  | |
| Naming convention: links are written with blue font  | |
| User name and password are present in scripts are extracted from a datapool.  | |