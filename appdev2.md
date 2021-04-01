# Syllabus

<p class="lead font-italic">Full-Stack Application Development II</p>

Application Development II (BUSN 36111) continues where Application Development (BUSN 36110) ends.

In 36110, we started from “I’ve never seen a line of code before” and ended at “I can come up with, write, and deploy a functional software-as-a-service application.”

36111 is intended for students who want to continue writing software after graduation, whether it’s to launch prototypes for entrepreneurial ventures, contribute to codebases as a technical team lead, or build side projects to stay current on tech trends.

To start with, we’ll learn ways to improve the beginner-focused code we wrote in 36110. Once you can write idiomatic, industry-standard code, you will be able to more easily read and use libraries, books, and blog posts written by professionals; and have your code understood by them. We’ll also dig deeper into the workflows that software engineering teams use for collaboration, deployment, and feedback.

With that, you will be well-positioned to join the community of professional developers, and continue learning whatever you need to ship your ideas on your own.

Specifically, we will:

 - Learn more advanced and concise ways to use the Ruby language and the Rails framework.
 - Write automated tests, which are essential for the long-term performance and code quality of a project.
 - Learn JavaScript, which will enable us to improve the responsiveness of our applications with real-time updates.
 - Add robust APIs to our applications, to enable additional third-party or first-party clients.
 - If time permits, add native iOS and Android apps using a cross-platform framework.

## Assessments

Learning assessment and your final grade will be based on the following:

 - 40% asynchronous / self-paced / at-home / introductory material.
    - You will have videos, readings, and accompanying walkthrough projects and exercises to complete to learn new concepts at your own pace outside of class.
 - 40% synchronous / collaborative / classtime / enrichment material.
    - During class meetings, we'll work together on various exercises to deepen your understanding of concepts; usually in groups. Most of these exercises can be completed after class; some[^cannot_attend] of them can only be done during class.
 - 20% capstone project.
    - In the last week or two, you'll devote most of your time to an individual capstone project.

[^cannot_attend]: If you _cannot_ attend class synchronously, e.g. because you're located in a timezone on the other side of the planet from Chicago, or had unexpected childcare obligations, etc; then contact the instructor and we'll work something out to make up for these.

There is no curve[^a_plus] in this course. Potentially, everyone could get an `A`; or, everyone could get a `D`. So don't worry if it seems like others came in with more experience; don't compare yourself to anyone else. Only compare yourself to yourself from yesterday. The course is designed for beginners; if you ask lots of questions, learn a little bit each day, and don't fall behind, then you'll be fine.

[^a_plus]: Since there is no curve, we also do not award `A+`s. Many students could, and often do, earn `100%`; and we do not make efforts to create artificial separation just so that we can limit the number of `A+`s.

**Note:** For this course, when you're looking at assignments in Canvas, it's much more helpful to Show **by Type** rather than Show By Date (click the button in the top-right corner):

![](/assets/show-by-type.png)

Showing by Type will **group and order** the assignments, and will display the weight of each group.

_Assignments will be posted by 5pm CT the day after your section meets._ I will make every effort to post at least some parts of the assignment within an hour of your section ending, but since we're writing new materials as we go to adapt to the new format, we may have to make some adjustments before posting.

## Expectations & time commitment

This course is going to be much more demanding than Application Development I. We're going to try to get as far as we can, as quickly as we can, with a group of students who are interested in doing so. Expect to invest at least ten hours per week, not including class time. The material will be difficult and there will be a lot of it, so you should expect to book multiple office hours slots each week to talk through things.

## Required materials

We will be using cloud-based software to write and run our applications entirely within our web browsers, so that everyone's environments are the same (no Windows vs Mac inconsistencies) and no one has to worry about e.g. going through their IT department to install Ruby on a work-issued laptop. Also, if your computer dies part-way through the quarter, no problem; you can borrow any old laptop or Chromebook and pick up right where you left off.

Primarily, we'll be using a service called Gitpod for this. The regular subscription price is $9/month. If you jump through some hoops you may be able to get a student discount.

All other required materials are free. There are some books, online courses, and other paid tools that I will recommend that you might find helpful, but that are not required. We'll provide step-by-step instructions for signing up for Gitpod and other required services during Week 1.

Many students have reported that it's helpful to have a second screen to watch course videos on while writing code on your main computer. This could be an iPad or Android tablet, a TV that you [AirPlay](https://support.apple.com/en-us/HT204289#mirrormac){:target="_blank"} or [Chromecast](https://support.google.com/chromecast/answer/3228332?co=GENIE.Platform%3DAndroid&hl=en){:target="_blank"} to, a second computer or Chromebook that you borrow, or a second monitor that you connect to your main computer.

## Canvas

Canvas is our home base. Everything that you need can be found by starting from the course's Home Page on Canvas and looking through the links there — assignments, Piazza, office hours, class recordings, reference materials, etc.

## Remote class over Zoom

For those joining class remotely, we'll be using Zoom.

 - You'll find a link for your section's Zoom "classroom" in Canvas, on the home page, and under Zoom in the sidebar. It's the same link all quarter; they don't change.
 - You should attend the section that you are registered for.

    If for some reason you can't attend your own section, then it might be okay to attend a different section that week instead, but you should post on Piazza for instructor approval (it might affect the group exercises that we're planning).
 - Class is intended to be an interactive, question-filled conversation, so **please turn on your camera**.
 - We will be making heavy use of Zoom's Breakout Rooms for group activities. 
 - In general, it's a good idea to keep your microphone muted, and use Push-To-Talk when you have something to say. Press and hold the <kbd>space</kbd> bar to unmute/talk, and then release to re-mute yourself. Like a walkie-talkie (remember those?).

    This makes it easier to pipe up with questions whenever one occurs to you, without having to fumble around with your mouse for the tiny <i class="fas fa-microphone-slash"></i> icon. Watch out, though: if you were chatting, your cursor might be in the chat still, in which case pressing and holding <kbd>space</kbd> might just type a bunch of spaces into the chat instead of unmuting you.
 - Alternatively, you can memorize the keyboard shortcut for muting/unmuting yourself: <kbd>cmd</kbd>`+`<kbd>shift</kbd>`+`<kbd>A</kbd> (Mac) or <kbd>ctrl</kbd>`+`<kbd>A</kbd> (Windows). [Make it a Global Shortcut in your Zoom settings](https://support.zoom.us/hc/en-us/articles/205683899-Hot-Keys-and-Keyboard-Shortcuts-for-Zoom){:target="_blank"} so that you can use it from everywhere, not just within Zoom.
 - Either way, with Push-To-Talk or with the unmute keyboard shortcut, please speak up often! Remember that this course is _question-driven_ and relies on you to be looking out for and asking questions.
 - However, sometimes you might not be sure if it's a good time to interrupt or maybe you want to share a link with your classmates that's not directly relevant to the lecture. In those cases, you can:
    - Use the Raise Hand button. I or the TAs will call on you at an opportune moment.
        - Please edit your Zoom profile and make sure your preferred name is in there.
    - Type into Zoom's chat. The TAs will be watching the chat and they will interrupt me and read your question/comment. So, if you're not sure, don't hesitate to type your questions or comments into the chat and let the TAs decide whether to escalate them.
 - Use Zoom's Nonverbal Feedback to let me know if e.g. things are moving too fast or too slow. Or hey, throw in a 👏/👎/👍 here and there.
   
We're all figuring this out[^social-distance] as we go along. If you have any suggestions or tips, please let us know.

## Self-paced lectures

Most "lecture" will be consumed at your own pace outside of class time, not over Zoom. You'll have videos that you can speed up, pause, skip back, and watch as many times as you like; which is very helpful when you're learning to code. There will also be some written material where it makes sense.

The videos will all be available within Canvas under Assignments. There will be in-video questions in the videos, and they will have due dates like any other assignment. It is essential that you complete the videos before their due dates, so that you're prepared for our in-class exercises.

## Q&A with Piazza

Most of our asynchronous communication with each other will occur over Piazza, a Q&A forum that you'll find in Canvas. (You should prefer Piazza over email; the instructors check Piazza much more frequently than email.)

Remember that in this course, _**your primary responsibility is to always be looking for questions to ask, and asking them**_. So Piazza is a crucial tool. Here are some guidelines for using it effectively:

 - You can make your questions visible to everyone, or just to instructors.
 - You can be anonymous to classmates.
 - If you have a question about something, it’s almost guaranteed that someone else has the same question. You'd be doing everyone a favor by being the first one to ask it — don't be afraid of looking silly!
 - That said, please do everyone a favor and:
   - Make your question visible to everyone rather than to instructors only (be anonymous if you want to).
   - Browse the list of older questions and see whether your question has already been asked and answered.
   - Give your question a descriptive subject line, so that it’s easier to browse for.
 - Prefer Piazza over email — the instructors check Piazza much more frequently.
 - When you're working on your own, _you’re only allowed to get stuck for 15 minutes_ before asking a question on Piazza. Just type up what you're stuck on in a Piazza post, and then get back to struggling. Don't struggle for longer than 15 minutes without at least asking the question.
 - Whatever you do, just _**ask lots of questions**_!

## Office hours

We are lucky to have professional developers as teaching assistants in this course. You can book one-on-one appointments with them for individual help. You'll find links to calendars for making these appointments on the Canvas homepage. Utilize this amazing resource! In the real world, developer time is expensive.

Even if you only have one or two questions, or you're not even sure what to ask, it's okay to book a slot. We're happy to talk through anything with you.

## Tentative schedule

_Week 1_

 - AppDev I review
 - Improving the UX of a `draft:resource`
 - Leveling up: Ruby

_Week 2_ 

 - Writing automated tests
 - Improving the code of a `draft:resource`
 - Introducing: The Rails `scaffold`

_Week 3_

 - Leveling up: Git
 - The importance of Code Review
 - Authentication with the Devise gem
 - Authorization with the Pundit gem

_Week 4_

 - It's finally time: JavaScript

_Week 5_

 - Partial page updates with Ajax

_Week 6_

 - Building a Robust JSON API

_Week 7_

 - Leveling up: Deployment
    - Heroku Pipelines
    - Continuous integration
    - Performance and error monitoring

_Week 8_

 - Native iOS and Android development
    - A taste of Swift
    - Cross-platform development with React Native

_Weeks 9 & 10_

 - Final projects

<u>The schedule above is highly subject to change.</u> All materials will be accessible to you after the quarter is over.
