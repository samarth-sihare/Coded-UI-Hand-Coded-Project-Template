# CodedUI Hand Coded Project Template

## Coded UI Hand Coding Project.zip
The zip file is a Visual Studio Project Template that can be imported and used to create a simple Coded UI Project for hand coding 

This is a simple CodedUI Project Template for hand coding with simple Data-drive approach and POM

## How to import project templates in Visual Studio?
By default, Visual Studio searches two locations for project and item templates.

1. <b>Installed Templates:</b> By default, templates installed together with the product are located in: \<VisualStudioInstallationDirectory>\Common7\IDE\ProjectTemplates\<Language>\<Locale>\
2. <b>Custom Templates:</b> By default, custom templates are located in: ...\My Documents\Visual Studio <_version>\Templates\ProjectTemplates\<Language>\

<p>So in our case we will paste the zip file at: ...\My Documents\Visual Studio <_version>\Templates\ProjectTemplates\Visual C#\Test</p>

For more details refer- <a href="http://msdn.microsoft.com/en-us/library/y3kkate1.aspx">How to: Locate and Organize Project and Item Templates</a>

## How to use the Project Template?
After importing the template as mentioned above you can create a new project by following steps

1. Navigate to FILE --> New --> Projects... (or simply hit Ctrl+Shift+N)
2. Under Templates --> Visual C# --> Test 
3. Select <b>Coded UI Hand Coding Project</b>

<strong>Note:</strong>You may have to remove lot of pre-existing sample code snippet and rename the files, methods etc.


## TIPS
<strong>1. Error in DataDriven Test using Excel:</strong>

If you get a connection error, it's most likely due to the fact that you don't have the 2007 Office System Driver installed for the OLEDB provider. You can download it from the following Microsoft link: http://www.microsoft.com/en-us/download/details.aspx?id=23734
