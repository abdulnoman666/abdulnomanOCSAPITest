# abdulnomanOCSAPITest
Instruction to run the API tests
Clone the project on the appropiate directory
Download NUnit console runner from https://github.com/nunit/nunit-console/releases/tag/v3.12
Download the msi NUnit.Console-3.12.0.msi and install it
NUnit console should be installed in C:\Program Files (x86)\NUnit.org\nunit-console
Run the command prompt with Administrator mode and run the following command
go to C:\Program Files (x86)\NUnit.org\nunit-console and run the below command with the appropiate directory where you put the project
nunit3-console.exe "<Path where you put the Visual Studio project>\bin\Debug\AthletesAPITest.dll"
  if console finds the project dll then it should run the project and generate TestResult.xml file in the C:\Program Files (x86)\NUnit.org\nunit-console directory
