---
title: Mixed Reality
keywords: HCI
sidebar: home_sidebar
permalink: hci_mixedreality.html
last_updated: March 29, 2018
folder: HCI
---

## Mixed Reality - about the market 
**(Note: This is Microsoft Confidential and for internal usage only)**

### What are customers asking for?
 
This topic can be split into 2 things on MR: commercial and consumer.

Let's focus on commercial as this is where we as CSE invest the most. According to IDC, Forrester and such:
- By 2018, AR will be largely confined to social and gaming, which will build awareness among consumers. The increase in demand will be in tandem with the increase in the demand for smartphones that will be compatible with VR headsets and it is expected to attain approximately 2.5 billion, The cloud could provide a bridge between offline and online. 
- In 2019 : Commercial spending on VR and AR will surpass consumer spending, 20% of all new entreprise IT mobile apps will include AR
- Between 2018 – 2020, major smartphone manufacturers will launch AR smart glasses and headsets, that will be tethered to smartphones (like smartwatches are currently).
- By 2021, one-third of information workers will leverage AR on the desktop or on mobile to manipulate digital information, interact with real-world objects, and to collaborate with colleagues.

We are at the gate of the VR and AR era. In the commercial space last year or so was mainly early adopters with Hololens and lately immersive headsets.
 
### What is current state of the art?
 
Mixed Reality is the name we, as Microsoft, give to the field in general. You have to see it as a spectrum that goes from AR to VR with everything in the middle. Devices, platforms and experiences that are, or will be created are positioned somewhere on this spectrum. Sometimes its only AR, sometimes only VR, and sometimes a mix of both. This applies for our platform or for others. It is not just a marketing buzz word, it is a clear definition of what exist today and what will exist in the future.

Today, most devices and experiences are positioned mostly on each of the 2 ends of the spectrum:
- AR is mainly mobile phone on iOS or Android. Experiences are mainly created using Unity and ARCore for Android or ARKit for iOS.
- VR is mainly on computers and gaming console(s). For computers, the main ones are HTC Vive , Occulus , and Windows Mixed Reality Immersive devices. For consoles, it is mainly Playstation. In Q3 last year 1 million headsets were shipped with this split of the market: 49% sony, 21% occulus, 16% HTC, 14% Others (microsoft was shipped after that, not included)
- Holographic (Hololens) is somewhere in the middle, more on the AR side. It includes more features than just AR as Spatial Mapping, Spatial Audio, speech etc.

Apps are distributed mainly via Steam (or Windows store in our case).
 
### Where Microsoft is in that area and where are we relative to the industry?
 
Microsoft is in a very innovative space on the Holographic side of things. Hololens has not yet a real competitor. It is the most complete offer for doing AR and more on Commercial scenarios.

On VR, we are late in the game: Vive first release was April 2016, Occulus March 2016, Mixed Reality headsets: November 2017. This does not mean we cannot have a good market share in the future but it also means we have to be clever as a company to show how different we are.
Here are some examples of our advantages:
- We are the first doing inside-out tracking. This means you don't have to setup a room with captors or beacons to position your headset (and you) in the room. The headset uses a subset of hololens features that does a light version of spatial mapping.
- We don't create devices for VR (Immersive) ourselves but we use the OEM channel for that. This means we have a very wide offer and that prices are competitive and we are taking the market lower in prices (occulus and vive lowered these prices following this). It kind of means that we are trying to be in the same position as Android for phone: wide offer with low prices options.
- We have a bridge which allows users to use experiences from Steam even if they were not built for Mixed Reality. It is in beta but globally works well

Microsoft has an "Enterprise Council"  including a lot of commercial companies that are doing work around Hololens or Immersive. It includes areas like: Manufacturing, Education, Healthcare, Defense/PS, Retail and Architecture/Engineering. Most of scenarios are cross areas with Remote Expert, Training&Development, Space planning, Design and prototype and IOT Data Access. This is a good representation of the global market too.

Most of these experiences are created using Unity. Some can be done with Unreal or other engines but it is way more complex. We provide a toolkit called Mixed Reality Toolkit which is open source. This toolkit is not cross platform and lack features but is a good start of where we should be.
 
### What is the most important thing that CSE should be doing in this area? 
 
We have 3 workstreams on this:
- Documentation (identifying gaps)
- MRTK: Making sure it's modular and cross platform
- Azure / Cogservices SDKs: enabling compatibility with MR

One of our roles in CSE is making sure that our cloud and services (Azure, cognitive services,…) are easy to use in client-side applications. This is why our main focus should be (and is) about making sure that azure sdks are easy to use in Mixed Reality (and also in other platforms leveraging Unity as a dev tool). We are investigating with partners in hackfests on relevant scenarios and helping the product group teams to improve the building blocks to enable these scenarios.

Right now, the status on MR + Azure/cogservices is red. Fixing it is the most important thing to do. There are a lot of issues that are a mix of Unity using a forked version of mono in their editor, Microsoft not having Azure sdks on a compatible .NET version, Unity not generating the latest version of UWP, issues with UWP. Sometimes it is only one of these, sometimes all of it at once.

Unity has partnered with Unity to release IBM watson sdk to Unity https://blogs.unity3d.com/2018/02/20/bringing-the-power-of-ai-to-developers-with-the-ibm-watson-unity-sdk/

There is already work going around this and discussions with the right product group teams already started. Anything that adds weight to this to help us influence roadmaps is welcome (identifying partners that want to try to use this, finding more issues)
 
### How does that most important thing relate to the current product team?
  
Doing dev on Mixed Reality means : using Unity, the Mixed Reality Toolkit and Azure SDKs. It is basically involving 3 teams, one being another company. Of course: they all want to enable partners and projects and it is our role as CSE to influence their roadmaps to make sure they focus their effort on what we think is the most important.

As Mixed Reality is a Windows and client side tech, we are working in collaboration with PAX on all this.

## Community

[Teams](https://teams.microsoft.com/l/channel/19%3aff70f60a124748ff8aa3b5410e8cf268%40thread.skype/HCI%2520-%2520Mixed%2520Reality?groupId=dff0a70d-6316-4124-ae5a-e9d06f63ec34&tenantId=72f988bf-86f1-41af-91ab-2d7cd011db47) channel available!

<!-- Add in any communities worth following: blogs, twitter, etc. -->
---
<!-- Here, add in any links to useful resources. The structure is not fixed, it can be grouped by scenario, by tech, or set up as a learning path -->

## Mixed Reality Courses

- [MR Academy](https://developer.microsoft.com/en-us/windows/mixed-reality/academy) (Tools Docs - Oct 2017)

## Mixed Reality and Azure / AI 

- [Mixed Reality Azure Samples](https://github.com/Microsoft/mixedreality-azure-samples) (code samples, available soon)
- [Unity and Azure documentation sandbox](https://docs.microsoft.com/en-us/sandbox/gamedev/) (Unity packages and documentation)
- [Building a Holographic Assistant with Bot Framework, LUIS & Mixed Reality](https://content.microsoftready.com/FY18Q3/session/CD-DEV-DRT303) (Ready Session - Feb 2018)

## Basic & Reference Content

Get started quickly with the content here

### Courseware

- Unity Training Content
  - [Developing 2D & 3D Games with Unity for Windows Jump Start](https://mva.microsoft.com/en-US/training-courses/developing-2d-3d-games-with-unity-for-windows-jump-start-8350?l=gA67AvEz_8104984382) (MVA Course - Jan 2015)
  - Adam Tuliper Resourcecs: [Blog](http://www.adamtuliper.com/2015/10/some-awesome-learning-resources-for.html) and [Cross-Plat Game Dev](https://msdn.microsoft.com/magazine/dn879350.aspx) (Connect() Article - 2014)
- [App Development Course for Hololens](https://www.linkedin.com/learning/app-development-for-microsoft-hololens)(LinkedIn Course - Sept 2017)
- [Internal Hack Guidance for Immersive](https://microsoft.sharepoint.com/teams/wdg-pax-mr/Shared%20Documents/Forms/AllItems.aspx?slrid=1477249e%2D00c2%2D0000%2D598c%2D88ed0d6a14af&RootFolder=%2Fteams%2Fwdg%2Dpax%2Dmr%2FShared%20Documents%2Fpublic%2FMixed%20Reality%20Hacks&FolderCTID=0x012000080848EBD599CF4BBF2ED51E206D7CE8) (MS INTERNAL ONLY - Docs repo)

### Reference Materials

- [Windows MR Developer Site](https://developer.microsoft.com/en-us/windows/mixed-reality) hosts docs and videos to guide you through designing and building Immersive and Holographic apps
- [Windows Mixed Reality SharePoint - MS INTERNAL ONLY](https://microsoft.sharepoint.com/teams/Mixedreality/SitePages/Home.aspx)

### Additional Content to Explore

- [Coding Unity Tutorials](https://unity3d.com/learn/tutorials/topics/scripting/coding-unity-absolute-beginner) (Tools Docs)
- [Building Win10 Games with Unity 5](https://mva.microsoft.com/en-US/training-courses/building-windows-10-games-with-unity-5-12572) (MVA Course - Sept 2015)
- [Building Blocks: Game Development](https://mva.microsoft.com/en-US/training-courses/building-blocks-game-development-16063) (MVA Course - Mar 2016)

## Apps and Samples

- [Galaxy Explorer](https://github.com/Microsoft/GalaxyExplorer) (GitHub Repo) Open Source application available in the store. Useful end to end demonstration of how to build a Unity app for Windows MR.
- [MixedRealityToolkit-Unity](https://github.com/Microsoft/MixedRealityToolkit-Unity) (GitHub Repo) The Mixed Reality Toolkit is a collection of scripts and components intended to accelerate development of applications targeting Microsoft HoloLens and Windows Mixed Reality headsets. The project is aimed at reducing barriers to entry to create mixed reality applications and contribute back to the community as we all grow.
- [Coding4Fun: Mixed Reality Lunar Module](https://github.com/Microsoft/MRDesignLabs_Unity_LunarModule) (GitHub repo) This HoloLens project comes to us from [Microsoft Mixed Reality Design Labs](https://developer.microsoft.com/en-us/windows/mixed-reality/design). This repo is where Microsoft's Windows Mixed Reality Design team publishes examples and explorations. The goal is to inspire creators and help them to build Mixed Reality experiences. We share sample app projects here that demonstrate how to use various types of common controls and patterns in Mixed Reality. Find out details about common controls and sample apps on https://developer.microsoft.com/en-us/windows/mixed-reality/design.

## Presentations and Recordings

- [Building Windows MR Experiences with HoloToolkit and Unity](https://digital.microsoftready.com/FY18/Session/TECH-WAD324) (Ready 2017 Session)

### Ignite 2017 Sessions

- [So You Want To Do Mixed Reality](https://myignite.microsoft.com/sessions/56023?source=sessions)
- [Building Windows Mixed Reality Experiences with Unity](https://myignite.microsoft.com/sessions/53542?source=sessions)

### Channel 9 Highlights

- [Windows Mixed Reality at 90FPS](https://channel9.msdn.com/events/dotnetConf/2017/T227?term=Mixed%20Reality)