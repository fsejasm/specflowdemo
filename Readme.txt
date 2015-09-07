 
Welcome to SpecFlow and Coded UI integration!

1. Go to "CodedUITestProject7" sample VS2012 project with the Specflow and Coded UI integration sample demo
2. Go to "Presentation" folder to review the PDF document related to the presentation.
3. Follow the minimal steps to setup Specflow with the below steps:
  
First Steps
  
This section guides you through the first steps of setting up your SpecFlow project and creating your first scenario. In the example, we will use SpecFlow with NUnit, but you can choose from many other test execution frameworks, including SpecFlow+Runner, which provides specialized execution features, Visual Studio Test Window and Team Foundation Server (TFS) Build integration for SpecFlow.

Get your first SpecFlow test running in just a few steps:
Step 1 
Create a class library project: MyProject.Specs


If you want to use SpecFlow with MsTest in VS2012, you should start with a “Specflow Project”

Step 2 
Add SpecFlow for NUnit through NuGet


Instead of NUnit, you can also use other test engines, like MsTest, xUnit, MbUnit or SpecFlow+Runner


PM> Install-Package SpecFlow.NUnit

Step 3 
Add your first feature file

 


We are writing yet another StackOverflow clone: SpecOverflow



Add a new feature file to the project

Step 4 
Describe the first scenario in your application



The first scenario

Step 5 
Generate step definition skeletons


Cool new feature in v1.9!



Invoke step definition skeleton generation from the context menu

Step 6 
Run your test – it is not green yet


Use your favorite test runner, like the VS2012 test runner below; but it works well with ReSharper too…



Running the test returns an inconclusive result

Step 7 
Implement automation & application logic until the test is green



The test finally passes

Step 8 
Celebrate the good work and continue with the next scenario!


SpecFlow - Cucumber for .NET

2015 © All Rights Reserved


       