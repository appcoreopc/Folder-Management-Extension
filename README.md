# Folder-Management-Extension

![](https://almrangers.visualstudio.com/DefaultCollection/_apis/public/build/definitions/7f3cfb9a-d1cb-4e66-9d36-1af87b906fe9/97/badge)

> ![Gears](Gears.png) Interested how our CI/CD pipeline works? Read [Set up a CI/CD pipeline for your Team Services extension](https://blogs.msdn.microsoft.com/visualstudioalmrangers/2017/04/17/set-up-a-cicd-pipeline-for-your-team-services-extension/) to learn more. 

## What
Easily and quickly create new folders in Code Explorer through the Web Access for TFVC and Git.

## Why
Previously you could only create new files from web access. To add a folder, you would need to use your local Git or TFVC repository. This meant that people who aren’t comfortable using Git or Visual Studio, could not add a folder. This extension helps solve that problem.

## Steps
1. Clone this repo
2. Browse to the folder of the extension
3. Publish the contents of the extension to a local or cloud web server
4. The root of the extension should be at the root of the web server, for example: https://myserver/images/fabrikam-logo.png
5. Update the extension manifest file (extension.json). To do this, update the  namespace field to a globally unique value. For example: johnsmith.samples.foldermanagement. Also, update the  baseUri  field to be the fully qualified URL to the root of your web server, for example:  https://myserver 
8. Install the extension into your Visual Studio Team Services account (see https://www.visualstudio.com/en-us/integrate/extensions/publish/overview)

## Find out more
Check out [Wouter de Kort's](http://blogs.msdn.com/b/willy-peter_schaub/archive/2014/01/21/introducing-the-visual-studio-alm-rangers-wouter-de-kort.aspx) blog post [here](http://blogs.msdn.com/b/visualstudioalmrangers/archive/2015/07/01/folder-management-visual-studio-online-extension-by-wouter-de-kort.aspx), where he walks through the process and how it works.

![](https://github.com/ALM-Rangers/VSO-Extension-FolderManagement/blob/master/media/FolderManagementExtension.PNG)
![](https://github.com/ALM-Rangers/VSO-Extension-FolderManagement/blob/master/media/FolderManagementExtension_Dialog.PNG)

<table>
  <tr>
    <td>
      <img src="https://github.com/ALM-Rangers/VSO-Extension-FolderManagement/blob/master/media/VSALMLogo.png"></img>
    </td>
    <td>
      The Visual Studio ALM Rangers provide professional guidance, practical experience and gap-filling solutions to the ALM community. Visit <a href="http://aka.ms/vsarblog">aka.ms/vsarblog</a> to find out more.
    </td>
  </tr>
</table>

## Contributors

We thank the following contributor(s) for this extension: Abel Wang and Wouter de Kort. 

## Contribute
Contributions to Folder Management are welcome. Here is how you can contribute to Folder Management:  

- Submit bugs and help us verify fixes  
- Submit pull requests for bug fixes and features and discuss existing proposals   

Please refer to [Contribution guidelines](.github/CONTRIBUTING.md) and the [Code of Conduct](.github/COC.md) for more details.

## Data/Telemetry
This project collects usage data and sends it to Microsoft to help Microsoft improve its products and services. For more information about how Microsoft uses telemetry data, read the Microsoft [privacy statement](http://go.microsoft.com/fwlink/?LinkId=521839). 

This telemetry is used for A|B testing and troubleshooting. 

To turn off telemetry you need to fork this repo, publish, and use your own version of the project without replacing the \_\_InstrumentationKey\_\_ configuration key.
