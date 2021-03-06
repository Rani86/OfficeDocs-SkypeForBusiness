---
title: Microsoft Teams resources for Education admins
author: MicrosoftHeidi
ms.author: heidip
manager: serdars
ms.topic: reference
ms.service: msteams
audience: admin
ms.reviewer: karsmith
description: Remote learning startup guidance for Microsoft Teams for EDU.
localization_priority: Priority
search.appverid: MET150
f1.keywords:
- NOCSH
ms.collection: 
  - M365-collaboration
  - Teams_ITAdmin_RemoteWorkers
appliesto: 
  - Microsoft Teams
---
# Get started with Microsoft Teams for remote learning

> [!NOTE]
> This article is a great resource for getting your school set up for remote learning. If you are an educator or a school leader, these resources may help:
>
> - A collection of articles written for teachers including how-to guidance for the most important [**first steps in teaching in Teams**](https://support.office.com/article/microsoft-teams-5aa4431a-8a3c-4aa5-87a6-b6401abea114).
> - A 1-hour online course in the Microsoft Educator Center shows how teachers use Teams in their professional lives. [**Transform Learning with Microsoft Teams**](https://education.microsoft.com/course/9c9f5c11/overview).
> - A 1-hour online course in the Microsoft Educator Center leads teachers through teaching in Class Teams. [**Crafting a Collaborative Learning Environment with Class Teams**](https://education.microsoft.com/course/b1e15cfc/overview).
> - If you're a teacher, student, or a parent or guardian, get more guidance on [**teaching and learning remotely with Office 365**](https://aka.ms/RemoteLearningHelp).
> - Parents and guardians can also go to our [**Parent Support Page**](https://support.office.com/article/remote-learning-with-office-365-guidance-for-parents-and-guardians-89d514f9-bf5e-4374-a731-a75d38ddd588) for help with remote learning.

Don't miss the March 4, 2020 blog, [How schools can ramp up remote learning programs quickly with Microsoft Teams](https://aka.ms/teamseduremoteblog).

Learning online can be just as personal, engaging and socially connected as learning in a classroom. Students and teachers can stay in touch and help each other using conversations, and can feel like they are meeting in person using live meetings. Teachers can track student progress in their daily work using Assignments. No one needs to feel out of touch. Many students who learn online say they feel they have more of a voice, and they feel more connected to their teachers and peers than they did in the classroom. And, just like in a classroom, teachers can use the apps and functions of Teams to support how they work best.

Microsoft Teams is a digital hub that brings conversations, content, assignments, and apps together in one place, letting teachers create vibrant learning environments. Build collaborative classrooms, connect in professional learning communities, and connect with colleagues – all from a single experience.

Within Teams, teachers can quickly converse with students, share files and websites, create a OneNote Class Notebook, and distribute and grade assignments. Built-in OneNote Class Notebooks and end-to-end assignment management allow teachers to organize interactive lessons and provide effective and timely feedback. School administrators and staff can stay up-to-date and collaborate using Staff Teams for announcements and topical conversations. Educators can share instructional material using Professional Learning Communities.

Use the best practices in this article to start using Teams for your educational needs to enable remote learning capabilities. Class Teams can be used to create collaborative class spaces, provide a virtual meeting platform, facilitate learning with assignments and feedback, and lead live calls with students.

Teams has [clients](get-clients.md) available for desktop (Windows, Mac, and Linux), web, and mobile (Android and iOS) to make sure all your staff and students can stay connected.

Learn more about Teams usage scenarios at the [Teams for education webinar series](https://aka.ms/TeamsEDUWebinars).

## User accounts, licenses, and identity security

Teams leverages Microsoft 365 capabilities to authenticate users and provide services. Staff, instructors, and students should have identities established to facilitate collaboration. If identities do not already exist, follow this process to establish them.

[Teams licenses need to be enabled for users](https://docs.microsoft.com/microsoft-365/education/intune-edu-trial/enable-microsoft-teams) and then [licenses need to be assigned to the users](teams-edu-licensing.md) before they can use Teams capabilities. Teams relies on additional Microsoft 365 capabilities such as [Office 365 groups](Office-365-groups.md), [Exchange](Exchange-Teams-interact.md), [SharePoint and OneDrive](SharePoint-OneDrive-interact.md) to enable collaborative scenarios. Users receive the best Teams experience if all these services are also enabled. [Teams is supported for users who have email hosted by Google](https://docs.microsoft.com/microsoft-365/education/deploy/enabling-teams-for-education-for-google-users).

Microsoft Teams is included in Office 365 A1, which is free for educational institutions. For IT guidance on how to deploy Office 365 and get your entire school started on Teams, check out [this page](https://docs.microsoft.com/microsoft-365/education/intune-edu-trial/set-up-office365-edu-tenant). For support, you can file a ticket [here](https://signup.microsoft.com/Signup?OfferId=03ee83a5-5cb4-4545-aca9-33ead43f222a,d764709a-7763-45ef-a2a8-db5b8b6ae704&DL=ENTERPRISEPREMIUM_FACULTY&ali=1) and for trainings on Teams, visit your local Microsoft Store to speak with a Specialist.

## Easily set up Teams

These are the two things you need to do to get up and running with Teams:

### 1. Allow users to create teams

Students and educators will get the most out of Teams when they can use it with minimal barriers and have the flexibility to tailor it to their needs. One way users can tailor their Teams experience is by having the ability to create teams that meet their needs. **By default, everyone can create Office 365 groups and Teams**. There are times when this capability may not be appropriate; for example, some customers may want to restrict primary-secondary students from creating Teams. If needed, Office 365 group and Team creation can be [restricted to certain security groups](https://docs.microsoft.com/microsoft-365/admin/create-groups/manage-creation-of-groups) within your environment.

Higher education customers benefit when you let everyone, including students, create teams for classes, research, group projects, and study groups. Primary-secondary schools may want to restrict students from creating Teams to make sure that all student to student communications are happening within a forum that include an adult. In this case, Office 365 group and Team creation can be restricted to all educators and staff.

### 2. Configure user experiences using policies

[Teams policies](teams-policies.md) provide the ability to control the options available for specific users or groups of users. Policies can be applied to define who should be allowed to use private chat, private calling, meeting scheduling, content types that can be shared, and more.

**Higher education staff, educators, and students** benefit from the capabilities included with the default (global) policies. Some additional policy settings can be enabled to add more functionality to Teams, including [enabling translate capabilities in the messaging policy](messaging-policies-in-teams.md#messaging-policy-settings) and [allowing for automatic meeting transcription](meeting-policies-in-teams.md#allow-transcription) in the meeting policy.

**Primary-secondary school students** may need restricted capabilities provided to students. Policies set boundaries on what the students can do. Because the student population is often the largest set of users and they often receive the most restrictive settings, it is recommended that student policy changes be made to the 'Global (Org-wide default)' polices.

Here's a set of common non-default policy configurations that would be assigned to primary-secondary students to limit unmoderated communication between students:

#### Messaging policy

- Change set to 'off'
- Giphy content rating set to 'strict'
- Translate messages set to 'on'
- Send urgent messages using priority notifications set to 'off'
- Remove users from group chats set to 'off'

#### Meeting policy

- Allow Meet now in channels set to 'off'
- Allow the Outlook add-in set to 'off'
- Allow channel meeting scheduling set to 'off'
- Allow scheduling of private meetings set to 'off'
- Allow Meet now in private meetings set to 'off'

#### Live events policy

- Allow scheduling set to 'off'

#### Calling policy

- Make private calls set to 'off'

#### Teams policy

- Create private channels set to 'off'

**Primary school staff and educators** should be assigned policies that grant the core capabilities that may be restricted for students. Create new policies that allow the for private chat and meeting scheduling (the default settings for a new policy). [Assign these policies in bulk to your staff and educators via batch policy assignment](batch-policy-assignment-edu.md).

## Start using Teams

### Create Class teams for secure classroom use

Microsoft Teams for Education offers [specific team types](https://support.office.com/article/choose-a-team-type-to-collaborate-in-microsoft-teams-0a971053-d640-4555-9fd7-f785c2b99e67) for educational use. The [Class team type](https://support.office.com/article/create-a-class-team-in-microsoft-teams-fae422eb-58b7-4431-9ff2-a4b9b6ae7c5b) is designed for classrooms with specific features, including: Assignments, a OneNote classroom notebook, a [class materials folder](https://support.office.com/article/Use-folders-to-create-read-only-files-for-students-or-other-team-members-0e7791d7-8c9c-4749-9bca-984289477988) for securing read-only content for students, and the ability to mute disruptive students. There are a couple of ways in which class teams can be deployed:

1. [School Data Sync](https://sds.microsoft.com/) (SDS) can be **setup by IT**, allowing class teams to be created for all classes based on information in the school information system. This process will provision teams for each section and keep your instructor and student rosters in sync. [Educators will have the ability to prepare their team](https://support.office.com/article/activate-early-access-class-teams-created-with-school-data-sync-0d154696-66ab-4fcf-b22f-c3d9a82aaf78) before admitting students. Alternatively, if an educator doesn't use the team, students won't be admitted into the team because the educator never clicks 'activate'. SDS supports over 80 different School Information Systems (SIS systems) for data import, and the [SDS support team](https://aka.ms/SDSSupport) is ready to assist you in planning and configuration. You can also view our [Fast Deployment Guide for Remote Learning](https://docs.microsoft.com/SchoolDataSync/fast-deployment-guidance) to get started quickly.
1. **Educators set up** their own class type team and invite students. Educators can do this via [adding students to the team](https://support.office.com/article/add-a-student-to-a-class-team-b88263bb-ace1-4702-8a48-f8a2cf4af954), [sharing a join code](https://support.office.com/article/Create-a-link-or-a-code-for-joining-a-team-11b0de3b-9288-4cb4-bc49-795e7028296f), or [sharing a link to the team](https://support.office.com/article/Create-a-link-or-a-code-for-joining-a-team-11b0de3b-9288-4cb4-bc49-795e7028296f). If possible, it's best to have educators add their students to the team to ensure the students get access, and are notified that they've been added to a team.

After team setup, team owners can [customize their team's settings](https://support.office.com/article/find-your-class-team-s-settings-in-microsoft-teams-2592d4de-581d-4952-9028-02317880c158) including adding a [team picture](https://support.office.com/article/change-your-team-picture-02ea2af6-b49d-4de8-9551-1a5e472993c0), [create channels](https://support.office.com/article/create-student-project-groups-channels-in-microsoft-teams-f85b3c07-fb87-4b94-883b-9be55f4b1e45) for class subjects or group collaboration areas, [add an app](https://support.office.com/article/add-an-app-to-teams-b2217706-f7ed-4e64-8e96-c413afd02f77) like Quizlet/Flipgrid/Kahoot to surface existing educational content, and [mention their team for their first post](https://support.office.com/article/using-the-conversation-tab-in-microsoft-teams-53d1c530-3797-4a6f-9892-6760f8763df2) to notify everyone and start the conversation.

### Create Staff teams for staff communication and collaboration

[Staff type teams](https://support.office.com/article/create-a-staff-team-in-microsoft-teams-314ac9d5-36a9-408e-8ae4-7ef20e9f1ddf) are designed for school administrators and staff to easily share information and work together on school-wide initiatives, including making announcements, settings up meetings, sharing content, and bringing in external apps, like [Planner for task tracking](https://support.office.com/article/create-a-plan-with-planner-d000976a-7490-4ddf-b9af-09ee764891e2). School administrators can add school staff members to the team via the team creation wizard, [adding members after the team is created](https://support.office.com/article/add-members-to-a-team-in-teams-aff2249d-b456-4bc3-81e7-52327b6b38e9), or by [sharing a join code or link to the team](https://support.office.com/article/create-a-link-or-a-code-for-joining-a-team-11b0de3b-9288-4cb4-bc49-795e7028296f). [Creating channels](https://support.office.com/article/create-a-channel-in-teams-fda0b75e-5b90-4fb8-8857-7e102b014525) is a great way to organize conversation and files by workstream or subject. [The Go-to guide for team owners](https://support.office.com/article/go-to-guide-for-team-owners-75f9669b-bd8f-457d-b60b-ac2ac9c8ead4) is an excellent place to learn about team owner duties and capabilities.

## Teams meeting scenarios

### Collaborative meetings for virtual classes

[Microsoft Teams meetings](https://docs.microsoft.com/MicrosoftTeams/tutorial-meetings-in-teams) support up to 250 concurrent attendees, including the ability to have audio, video, [content sharing](https://support.office.com/article/show-your-screen-during-a-meeting-90c84e5a-b6fe-4ed4-9687-5923d230d3a7), whiteboards, and shared notes. Meetings can be scheduled within the Teams client for [meeting within a private space or within a team channel](https://docs.microsoft.com/MicrosoftTeams/tutorial-meetings-in-teams), so all team members know about it. Meetings can be recorded and saved for attendees to review later. These recordings can also be [transcribed to easily find content](https://support.office.com/article/Microsoft-Stream-automatically-creates-closed-captions-for-videos-8d6ac353-9ff2-4e2b-bca1-329499455308) that had been discussed. A laptop or mobile phone webcam, microphone, and speaker can be used for meetings, and you can get premium audio/video quality from [Microsoft Teams optimized devices](https://products.office.com/microsoft-teams/across-devices/devices).

### District/University events or updates

Some instruction needs larger audiences and additional production capabilities. These meetings often have defined presenters, producers, and moderated Q&A. Teams supports these sessions using [Microsoft Teams live events](teams-live-events/what-are-teams-live-events.md). Live Events can be used for scenarios, such as district or university-wide updates, leadership addresses, and for instruction to large classes or student groups, or extend to your community. Learn more about conducting live sessions at: [plan and schedule a live event](https://support.office.com/article/video-plan-and-schedule-a-live-event-f92363a0-6d98-46d2-bdd9-f2248075e502), [produce a live event](https://support.office.com/article/video-produce-a-live-event-34c89e79-ffd4-4a6a-baf6-77055e0709cb), [attend a live event](https://support.office.com/article/video-attend-a-live-event-d837ad8d-ce34-44d0-9744-9beb50e943ac), and [moderating a Q&A](https://support.office.com/article/video-moderating-a-q-a-4984e582-8c66-4ea3-aaaf-d93cf62e1b76).

## Recommended Tips & Tricks

You can learn more about how Teams is used in Education at: [Microsoft Teams for Education](https://support.office.com/article/Teams-5aa4431a-8a3c-4aa5-87a6-b6401abea114).

> [!NOTE]
> Some key Teams features are not specific to education. Tips and tricks for core Teams capabilities can be found at: [Teams Help and Learning](https://support.office.com/teams).

## Adoption content

Microsoft has developed [adoption content](https://support.office.com/article/video-moderating-a-q-a-4984e582-8c66-4ea3-aaaf-d93cf62e1b76) and strategy guidance for deploying Teams. The [Teams adoption guide](https://teamworktools.azurewebsites.net/tft/index.html) provides a good overview of available content and the [Teams Customer Success Kit](https://aka.ms/TeamsCustomerSuccess) provides many templates that can be used for Teams awareness. The Microsoft Educator Center provides education specific training on how [Microsoft Teams](https://education.microsoft.com/learningPath/18793af1) and [OneNote](https://education.microsoft.com/learningPath/b6e3b5f2) are used in the classroom.

Additional adoption resources include:

- ["You can in :90" quick tip videos](https://www.youtube.com/playlist?list=PLiluTszfwwMKx-yVe7ekBX6gsLIHf1Z8k)
- [Teams for Education video playlist](https://www.youtube.com/playlist?list=PLiluTszfwwMKicAo6agloFALEB5WvYNYs)
- [BLOG: See how this school uses Teams for distance learning](https://www.wellingtoncollege.cn/tianjin-international/teaching-and-learning-update/)

## Support Readiness

IT professionals and support staff can get up to speed with Teams architecture and underlying use of Microsoft 365 capabilities with the [Teams IT architecture posters](teams-architecture-solutions-posters.md) and [admin technical training](itadmin-readiness.md).

Additional support resources include:

- [Troubleshoot Microsoft Teams installation and update issues](troubleshoot-installation.md)
- [File a support ticket (can be used by educators and staff)](https://aka.ms/edusupport)
- [Support and Help center for educators using Teams](https://support.office.com/article/microsoft-teams-5aa4431a-8a3c-4aa5-87a6-b6401abea114)
- [Student Help center](https://support.office.com/article/student-help-center-395ab230-55bf-44c6-b265-e832d729b694)
- [Teams for Virtualized Desktop Infrastructure](https://docs.microsoft.com/microsoftteams/teams-for-vdi)
- [How to quickly optimize Office 365 traffic for remote staff](https://techcommunity.microsoft.com/t5/office-365-blog/how-to-quickly-optimize-office-365-traffic-for-remote-staff-amp/ba-p/1214571)
- [Monitor and manage call quality](monitor-call-quality-qos.md)
- [Verify service health for Teams](service-health.md)
- [Support resources for Teams](https://docs.microsoft.com/microsoft-365/admin/contact-support-for-business-products)
- [Team help center](https://support.office.com/teams)
