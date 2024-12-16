---
layout: essay
type: essay
title: “In5pired”
# All dates must be YYYY-MM-DD format!
date: 2024-12-09
published: true
labels:
  - Coding Standards
  - Communication
  - Client Interaction
  - React
  - Meteor
  - Javascript
essayurl: https://ssunoo2.github.io/essays/in5pired.html
---
Like all endeavors in life, software engineering is riddled with its caveats, hidden complications and opportunities to grow professional skills. Working with our clients as a team of eight proved no different as we juggled the responsibilities of designing the application (with feedback from clients) and combatted issues that arose as best as we could.

	Working with a react front-end library for our application and using meteor as our designated framework, we were tasked with developing an application for an accounting firm that was intended to emulate an excel sheet to forecast financial health of autonomous organizations. 

	Gone were the training wheels and railroad that so determined our direction in previous university projects. As a team, we were given free reign to design the application how we wished. A little trip down memory lane to the modules of previous software engineering courses and some extensive googling and consumption of documentation would refresh my mind as to the ins and outs of our development platform.

	But a lot changes in a year! The last time I took the mantle of software developer during my junior year of university, the react components were set in front of me, urging development as predefined by the instructors. This led to some complications, as joining eight minds to one vision can be a little bit tricky, particularly when technical preferences differ from one developer to the next. 

	A few weeks into development, I began to review what others were working on and saw some discrepancies in the way the code was written. For instance, one developer may have opted to use class components, whereas I was brushing up on functional components and react hooks. Integrating functionalities I deemed crucial for the success of the application would require the tools I had recently learned and so mitigating the discrepancies in code would add considerable overhead to our development time. In this particular case, I opted to create a wrapper around pages with class components as I was dismayed that I could not introduce functional components directly to the pages without seriously overhauling the codebase. 

	Small conflicts of mind like the above stress the importance of regular and clear communication. At some points in the project, some developers would push code to deprecated pages scheduled for deletion as they were not present in the meetings. There was considerable confusion around the various functionality requirements and client specifications. In the end, half of our team proved to be reliable and proficient with the code base, while the other half decided to slink in the background and no longer attend.

	It is an unfortunate reality that there is an inequality in contributions to various projects, both contained within a university setting as well as in the professional world. But I get it. Things come up. Other responsibilities rear their heads. In the end, all we could do was to continue to maintain open channels for communication and encourage participation with a friendly and open demeanor.

The importance of cohesion within a team is absolutely vital to its success. While in this case, the project was successfully completed, the cohesion seemed isolated to a couple hard-working members. We managed to maintain good communication and request feedback, help and code reviews to make sure that milestones were completed on schedule and expressed any apprehensions or confusion about features to be implemented.

This brings me to the issue of clear and cogent communication between our development team and the client. To put it bluntly, our communication was sparse. We had about five minutes face-to-face each month.  This may have been the intention as there were five teams building the same product and each completed application was implemented in a novel way. This variation allows the client to judge from a basket of five applications which features and implementations they liked and did not like and allow teams to glean insight from others.

There were, however, some unforeseen complications in the way in which the demo excel sheet, which our goal was to emulate, was presented. The use of some included pages was not adequately defined. Presented as dummy sheets with no data input functionality from which financial data was to be retrieved and input into the application, it was discovered that some of the financial projection formulas actually pulled data from these sheets, a surprise to most of our team. Further, the financial projection formulas were heavily embedded in the sheets and took a considerable amount of time to parse. Upon attempting to gain clarification, we were met with conflicting information that led to more confusion.

Other functionalities were not clearly defined until later milestones such as the intention to have various permissions pertaining to different roles in the company. For instance, an admin, accountant, and analyst would all have view/edit access to different sheet pages based on their role. 

Given that our understanding was not clear, we deemed it best to make the components of the financial calculations as modular as possible. This would allow the code to be easily altered in the future when the definitions were better understood and could be implemented with ease. 

The functionalities described were eventually made clear and implemented into our final product, though it does merit reflection on what could have been improved to ensure adequate understanding of the client specifications, as this was our main bottleneck in development. The excel sheet contained hundreds of inputs, thousands of data values and convoluted formulas, so it would have been valuable to opt the client, perhaps, to hold our hand as we roleplay an anonymous organization attempting to use the spreadsheet to allow us to put ourselves in the shoes of a user. Further, it should be stressed that we are proficient in software engineering and unexplained ambiguities relating to accounting may stymie our progress.

There is a reason that many jobs are very specialized. From UX designers, to creative teams, to marketing, etc.; each of these are hired for one role in which they can focus their energy. While diversifying development and employing many skills is a great educational experience, it may be closer to optimal to allow the engineers to do engineering and make sure that specifications and ambiguities do not contribute overhead to the project, when they can be easily demystified. Just like an engineer’s job is to wear the shoes of their application’s user, it may be equally important for a client to view the project from the engineer’s eyes so as to make sure they are using their time with great efficiency. 

The client interactions remind me of a prospective client I encountered earlier this year. I cited a few hundred dollars for a quick prototype given adequate specifications. The client became excited at this price and exclaimed that they had none; they were happy to let me deal with all the creative and concept design myself! I then added a zero to the end of my price. 

Overall, this was a great project and I had a blast learning the updated react hooks, functional programming, etc. Aside from the sheer technical education it provided, I was reminded once again the importance of cohesion and frequent and clear communication both from within the team as well as the clients. 
