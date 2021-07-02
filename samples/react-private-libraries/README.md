# Private Folder Manager

## Summary

This sample provides a webpart that can be used to manage Document Libraries with Secured Subfolders. The use case this was developed for is a Request for Proposal site. A Document library is created for each RFP and subfolders are created within that Library for each external supplier invited to participate in that RFP.

The application manages all the security groups set up for the various libraries and folders so that suppliers only see RFP's they were ivited to participate in and only thier folders.


![mainpanel](.assets/Home Screen.PNG)

![AddingAlibrary](assets/Add a library.PNG)

![ManagingFolders](assets/ManageFolders.png)

![AddingAfolder](assets/Add A folder.png)

![Configuration](assets/Configuration)



## Compatibility

![SPFx 1.12.1](https://img.shields.io/badge/SPFx-1.12.1-green.svg)
![Node.js LTS v14 | LTS v12 | LTS v10](https://img.shields.io/badge/Node.js-LTS%20v14%20%7C%20LTS%20v12%20%7C%20LTS%20v10-green.svg) 
![SharePoint Online](https://img.shields.io/badge/SharePoint-Online-yellow.svg)
![Teams N/A: Untested with Microsoft Teams](https://img.shields.io/badge/Teams-N%2FA-lightgrey.svg "Untested with Microsoft Teams") 
![Workbench Local | Hosted](https://img.shields.io/badge/Workbench-Local%20%7C%20Hosted-green.svg)

> Don't worry if you're unsure about the compatibility matrix above. We'll verify it when we approve the PR. 
>
> If using an older version of SPFx, update the SPFx and Node.js compatibility tag accordingly:
> SPFx 1.11
>    ![SPFx 1.11](https://img.shields.io/badge/SPFx-1.11.0-green.svg) 
>    ![Node.js LTS 10.x](https://img.shields.io/badge/Node.js-LTS%2010.x-green.svg) 
>
> SPFx 1.4.1
>    ![SPFx 1.4.1](https://img.shields.io/badge/SPFx-1.4.1-green.svg)
>    ![Node.js LTS 6.x | LTS 8.x](https://img.shields.io/badge/Node.js-LTS%206.x%20%7C%20LTS%208.x-green.svg)
>
> If you built this sample specifically for SharePoint 2016, or SharePoint 2019 support, update the SharePoint compatibility tag accordingly:
>    ![SharePoint 2019 | Online](https://img.shields.io/badge/SharePoint-2019%20%7C%20Online-yellow.svg)
>    ![SharePoint 2016 | 2019 | Online](https://img.shields.io/badge/SharePoint-2016%20%7C%202019%20%7C%20Online-green.svg)
> If you know your web part only works on the hosted workbench, you can use this for the workbench compatibility tag:
>    ![Workbench Hosted: Does not work with local workbench](https://img.shields.io/badge/Workbench-Hosted-yellow.svg "Does not work with local workbench")
>
> If you specifically built and tested this web part to work with Teams, use this for the Teams compatibility tag:
>    ![Teams Yes: Designed for Microsoft Teams](https://img.shields.io/badge/Teams-Yes-green.svg "Designed for Microsoft Teams")
> And if you know for sure that it is NOT compatible with Teams, use this:
>    ![Teams No: Not designed for Microsoft Teams](https://img.shields.io/badge/Teams-No-red.svg "Not designed for Microsoft Teams")
>
> DELETE THIS PARAGRAPH BEFORE SUBMITTING

## Applies to

* [SharePoint Framework](https://docs.microsoft.com/sharepoint/dev/spfx/sharepoint-framework-overview)
* [Microsoft 365 tenant](https://docs.microsoft.com/sharepoint/dev/spfx/set-up-your-development-environment)

> Update accordingly as needed.
> DELETE THIS PARAGRAPH BEFORE SUBMITTING

## Solution

> We use this section to recognize and promote your contributions. Please provide one author per line -- even if you worked together on it.
> We'll only use the info you provided here. Make sure to include your full name, not just your GitHub username.
> Provide a link to your GitHub profile to help others find more cool things you have done.
> If you provide a link to your Twitter profile, we'll promote your contribution on social media.
> 
> DELETE THE TEXT ABOVE BEFORE SUBMITTING

Solution|Author(s)
--------|---------
react Private Folder Manager | [Russell Gove](https://github.com/russgove) ([@russgove](https://twitter.com/russgove))

## Version history

Version|Date|Comments
-------|----|--------
1.0|July 2, 2021|Initial release

## Prerequisites

> Any special pre-requisites? Include any lists, permissions, offerings to the demo gods, or whatever else needs to be done for this web part to work.
> 
> Please describe the steps to configure the pre-requisites. Feel free to add screen shots, but make sure that there is a text description of the steps to perform.
> 
> DELETE THE TEXT ABOVE BEFORE SUBMITTING

## Minimal Path to Awesome

* Clone this repository
* in the command line run:
  * `npm install`
  * `gulp serve`

> Include any additional steps as needed.
> DELETE THIS PARAGRAPH BEFORE SUBMITTING

## Features

Description of the web part with possible additional details than in short summary. 
This Web Part illustrates the following concepts on top of the SharePoint Framework:

* topic 1
* topic 2
* topic 3

> Note that better pictures and documentation will increase the sample usage and the value you are providing for others. Thanks for your submissions in advance! You rock ❤.
> DELETE THIS PARAGRAPH BEFORE SUBMITTING

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

## Help

We do not support samples, but we this community is always willing to help, and we want to improve these samples. We use GitHub to track issues, which makes it easy for  community members to volunteer their time and help resolve issues.

If you encounter any issues while using this sample, [create a new issue](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=bug-report.yml&sample=YOUR-SOLUTION-NAME&authors=@YOURGITHUBUSERNAME&title=YOUR-SOLUTION-NAME%20-%20).

For questions regarding this sample, [create a new question](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=question.yml&sample=YOUR-SOLUTION-NAME&authors=@YOURGITHUBUSERNAME&title=YOUR-SOLUTION-NAME%20-%20).

Finally, if you have an idea for improvement, [make a suggestion](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&template=suggestion.yml&sample=YOUR-SOLUTION-NAME&authors=@YOURGITHUBUSERNAME&title=YOUR-SOLUTION-NAME%20-%20).

<img src="https://telemetry.sharepointpnp.com/sp-dev-fx-webparts/samples/YOUR-SOLUTION-NAME" />

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

### Build options

gulp clean - TODO
gulp test - TODO
gulp serve - TODO
gulp bundle - TODO
gulp package-solution - TODO
