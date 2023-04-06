---

layout: col-sidebar
title: OWASP iGoat Tool
tags: igoat
level: 2
type: tool

---
## OWASP iGoat - A Learning Tool for iOS App Pentesting and Security [![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](https://twitter.com/OWASPiGoat/)

iGoat is a learning tool for iOS developers (iPhone, iPad, etc.) and mobile app pentesters. It was inspired by the WebGoat project, and has a similar conceptual flow to it.

As such, iGoat is a safe environment where iOS developers can learn about the major security pitfalls they face as well as how to avoid them. It is made up of a series of lessons that each teach a single (but vital) security lesson.

### The lessons are laid out in the following steps: ###

1. Brief introduction to the problem.
1. Verify the problem by exploiting it.
1. Brief description of available remediations to the problem.
1. Fix the problem by correcting and rebuilding the iGoat program.

Step 4 is optional, but highly recommended for all iOS developers. Assistance is available within iGoat if you don't know how to fix a specific problem.

## OWASP iGoat (Swift) - A Damn Vulnerable Swift Application for iOS [![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](https://twitter.com/OWASPiGoat/)

__Vulnerabilities Covered (version 1.0):__ [![Download iGoat](https://img.shields.io/badge/Download-iGoat-orange.svg)](https://codeload.github.com/OWASP/iGoat-Swift/zip/master) Documentation: https://docs.igoatapp.com/

<img src="https://github.com/swaroopsy/test/blob/master/h1.gif?raw=true" width="256" title="iGoat App">

__Documentation:__ <a href="https://github.com/OWASP/iGoat-Swift/wiki">iGoat Wiki</a>

__iGoat Quick Setup__ `git clone https://github.com/OWASP/iGoat-Swift.git`and open iGoat-Swift.xcodeproj with xcode.
__Setup iGoat Server__ Navigate to server > docker_packaging and then use command `docker compose up` <br>
__Using Cydia Repo__ - Open Cydia -> Sources -> Edit and add source http://swiftigoat.yourepo.com/ and then search for iGoat and install it.

__Project Lead__ - Swaroop Yermalkar [![Twitter Follow](https://img.shields.io/twitter/follow/espadrine.svg?style=social&label=Follow)](https://twitter.com/swaroopsy)

## Architecture
![Architecture](https://github.com/swaroopsy/test/blob/master/Architecture.png?raw=true)


<!-- Standard Chapter Page Template
This is an example of a Project or Chapter page.
Please change these items to indicate the actual information you wish to present. In addition to this information, the 'front-matter' above the text should be modified to reflect your actual information.  An explanation of each of the front-matter items is below:

{front matter for this file}

```
- layout: This is the layout used by project and chapter pages.  You should leave this value as col-sidebar
- title: This is the title of your project or chapter page, usually the name.  For example, OWASP Zed Attack Proxy or OWASP Baltimore
- tags: This is a space-delimited list of tags you associate with your project or chapter.  If you are using tabs, at least one of these tags should be unique in order to be used in the tabs files (an example tab is included in this repo) 
- region: This is the region you are in according to our data
```

{copy for this file (index.md)}
Replace the text above the commented area with your information in the format below:
```
## Welcome
Include some information here about your chapter

## Participation
The Open Web Application Security Project (OWASP) is a nonprofit foundation that works to improve the security of software. All of our projects ,tools, documents, forums, and chapters are free and open to anyone interested in improving application security. 

Chapters are led by local leaders in accordance with the [Chapter Leader Handbook](/www-policy/rules-of-procedure/chapter-handbook). Financial contributions should only be made online using the authorized online donation button. To be a SPEAKER at ANY OWASP Chapter in the world simply review the [speaker agreement](/www-policy/speaker-agreement) and then contact the local chapter leader with details of what OWASP Project, independent research, or related software security topic you would like to present.

Everyone is welcome and encouraged to participate in our [Projects](/projects), [Local Chapters](/chapters), [Events](/events), [Online Groups](https://groups.google.com/a/owasp.com/){:target='_blank'}, and [Community Slack Channel](https://owasp.slack.com/){:target='_blank'}. We especially encourage diversity in all our initiatives. OWASP is a fantastic place to learn about application security, to network, and even to build your reputation as an expert. We also encourage you to be [become a member](/membership) or consider a [donation](/donate) to support our ongoing work.

## Local News
- Meeting Location
- Everyone is welcome to join us at our chapter meetings.

```
{info.md}

This separate file is where you should place links to your Google Group and Meetup page. It will be automatically rendered in the column sidebar.

{leaders.md}

Another separate file that should simply include each leaders name with mailto link as a list. It will also be automatically rendered in the column sidebar.

-->
