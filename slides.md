---
titleTemplate: '%s - Slidev'
theme: the-unnamed
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
#background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: The Human Factor in DevOps
info: |
  # The Human Factor in DevOps...
  ## Because Even 🤖 Need Good Teammates (Almost)

  Remember when "DevOps" meant throwing code (and maybe a few passive-aggressive emails, that thankfully weren’t meetings) over the wall? We’d like to think that the last decade and a half has dispelled us of that notion, but has it really? Often when organizations begin their “DevOps Transformation” they focus so much on automation, but the component that is more often than not overlooked is the human element. Human connection.

  In this talk, Jeremy will dig into some strategies for building teams that actually work together, and might even come to like each other (though he can’t promise “meetings that are emails” will become a norm). He’ll talk about ways to encourage open communication, resolve conflicts, and create a team culture where everyone feels valued - because even the best automation tools can’t replace a team that actually works together.
conference: "DevNexus 2025"
socialimg: "/img/bluesky-jerdog-white.png"
favicon: "https://raw.githubusercontent.com/jerdog/jmeiss-me-website/main/assets/images/fav.png"
keywords: ""
presenter: true
download: true
exportFilename: human-factor-of-devops-slidevExport
export:
  format: pdf
  timeout: 30000
  dark: false
  withClicks: false
  withToc: false
remoteAssets: true
selectable: true
record: true
wakeLock: build
colorSchema: auto
aspectRatio: 16/9
fonts:
  sans: Roboto
  serif: Roboto Slab
  mono: Fira Code
drawings: # https://sli.dev/features/drawing
  persist: false
# apply unocss classes to the current slide
class: text-center
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
defaults:
  class: text-center
  transition: slide
#layout: cover
transition: slide-left  # slide transition: https://sli.dev/guide/animations.html#slide-transitions
### Key Notes
## You can have `style` tag in markdown to override the style for the current page. Learn more: https://sli.dev/features/slide-scope-style
## layoutClass: gap-16
## <Toc minDepth="1" maxDepth="1" />
## The <span v-mark.red="3"><code>v-mark</code> directive</span> also allows you to add <span v-mark.circle.orange="4">inline marks</span>
## <span v-mark.underline.orange>inline markers</span>

layout: image-right
image: /img/slides/humans_and_robot-teammates.jpeg
backgroundSize: contain
---

<span style="position: relative; top: 30%;">

# The Human Factor in DevOps...
## Because Even 🤖 Need Good Teammates (Almost)

</span>

<!--
Set the stage by highlighting the limitations of relying solely on AI in DevOps and emphasize the importance of human-centric approaches.
-->

---
layout: two-cols
layoutClass: gap-8
---

![alt text](/img/slides/code_over_wall.jpg)

::right::

![alt text](/img/slides/happy_diverse_team.jpg)

<!--
## Throwing code over the wall
Remember when "DevOps" meant throwing code (and maybe a few passive-aggressive emails, that thankfully weren’t meetings - but of course some were and still are) over the wall? How "not my code, not my problem" was a common enough phrase?
-->

---
layout: image
image: /img/slides/devops-foundational-books.png
backgroundSize: contain
---

<!--
I would like to think that the last 15 years have dispelled us of this notion, especially with the work of people like Gene Kim, Jez Humble, and Nicole Forsgren. But has it really? Often when organizations begin their “DevOps Transformation” they focus so much on automation, but the component that is more often than not overlooked is the human element. Human connection.
-->

---
layout: image
image: /img/slides/friendly_robot.jpg
backgroundSize: contain
---

<span style="position: relative; top: 90%;">

## DevOps is more than tools...

### It's about people

</span>

<!--
DevOps is not just about tools and automation, but about people and how they work together. In this talk, we will explore the importance of fostering open and honest communication, constructive conflict resolution, and building a culture of value and recognition within your DevOps team. Emphasizing the importance of the human element in DevOps, even in an increasingly automated world.
-->

---
layout: two-cols
---

<span style="position: relative; top: 20%;">

## Jeremy Meiss{style="color: deepskyblue; background: none;"}

<p style="font-weight: bold;">Director, DevEx & DevRel</p>
<p class="text-sm italic">OneStream Software</p>
<p style="font-weight: bold;">DevOpsDays KC Organizer</p>
</span>

::right::

![alt text](/img/profile-pic2.jpg){style="position: relative; margin: auto; width: 80%; border-radius: 15px 50px; "}

---
layout: section
---

# The Human Factor in DevOps
## It starts with people...

<!--
I will say this now, and then I will say it again, that DevOps is not just about tools and automation - it all starts with people and how they work together. But that's not always an easy thing to do because - everyone look around you - often us humans suck. So I am going to first explore common breakdowns in communication and teamwork, and how we can work to overcome them. Then, I'll look at ways that AI/ML can help... and hurt... our teams.
-->

---
layout: section
---

# The Human Factor in DevOps
## Communication & Teamwork breakdowns

<!--
A multitude of factors can contribute to communication and teamwork breakdowns in the dynamic environment of software development. I'm sure everyone could come up with an example. Maybe you're sitting next to one right now... don't look, but blink twice if you can relate. What are some of the causes of communication breakdowns that you have seen (don't feel like you need to be specific)?
-->

---
layout: image-right
image: /img/slides/comms-breakdowns.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

### Common Causes of _Communication_ Breakdowns

<v-clicks>

* Conflicting Ideas and Poor Collaboration
* Barriers to Cross-Cultural and Linguistic Communication
* Ineffective Organizational Structures and Communication Processes
* Ambiguous Project Requirements and Technical Miscommunication

</v-clicks>

<!--
A multitude of factors can contribute to communication and teamwork breakdowns in the dynamic environment of software development. Some of the most prevalent causes are: [click]**Conflicting Ideas and Poor Collaboration:** Diverse perspectives are common in software development, but unresolved conflicts can lead to confusion, hinder progress, and significantly reduce productivity. [click]**Barriers to Cross-Cultural and Linguistic Communication:**Globalized teams face challenges due to varying cultural backgrounds and language proficiencies, causing misunderstandings and errors. [click]**Ineffective Organizational Structures and Communication Processes:** Complex team hierarchies and inadequate communication tools or protocols contribute to information silos, delayed decisions, and reduced transparency. [click]**Ambiguous Project Requirements and Technical Miscommunication:** Unclear project requirements and miscommunication between developers (e.g., technical jargon, poor documentation) result in assumptions, rework, and increased development time.
-->

---
layout: center
---

![alt text](/img/slides/mars-orbiter.jpg){width=600px;}

>"_The 'root cause' of the loss of the spacecraft was the failed translation of English units into metric units in a segment of ground-based, navigation-related mission software..._"

Arthur Stephenson, chairman of the Mars Climate Orbiter Mission Failure Investigation Board

<span style="position: absolute; top: 8%; right: 10px; color: yellow; font-style: italic; font-size: 1rem;">Source: <a href="https://www.jpl.nasa.gov/missions/mars-climate-orbiter/">JPL, NASA</a></span>

<!--
Any of you remember the Mars Climate Orbiter Mission that ended abruptly in 1999 when it crashed into the surface because Americans use feet and pounds and the rest of the world uses meters and kilograms?

"The 'root cause' of the loss of the spacecraft was the failed translation of English units into metric units in a segment of ground-based, navigation-related mission software...""
-->


---
layout: image-right
image: /img/slides/comms-breakdowns.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

### Common Causes of _Communication_ Breakdowns

* Conflicting Ideas and Poor Collaboration
* Barriers to Cross-Cultural and Linguistic Communication
* Ineffective Organizational Structures and Communication Processes
* Ambiguous Project Requirements and Technical Miscommunication
* Communication Skill Deficiencies and Overload

<!--
**Communication Skill Deficiencies and Overload:** Lack of effective communication skills, combined with information overload, leads to missed deadlines, overlooked issues, and overall team incohesion.
-->

---
layout: image-left
image: /img/slides/teamwork-breakdowns.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

### Common Causes of _Teamwork_ Breakdowns

<v-clicks>

* Lack of shared understanding and commitment
* Team size and dynamics

</v-clicks>

<!--
[click]**Lack of Shared Understanding and Commitment:** Teams struggle when members don't share a clear vision of project goals and individual responsibilities. This misalignment leads to confusion and hinders effective collaboration. [click]**Team Size and Dynamics:** In larger teams, individual effort often diminishes, leading to the "Ringelmann Effect" and decreased productivity. Who's heard of the Ringelmann Effect?
-->

---
layout: two-cols-header
layoutClass: gap-8
---

### The Ringlemann Effect

::left::

![alt text](/img/slides/ringlemann-effect.jpg)

::right::

![alt text](/img/slides/tugofwar.jpg)

<span style="position: absolute; bottom: 10%; left: 25px; color: yellow; font-style: italic;">Source: <a href="https://en.wikipedia.org/wiki/Ringelmann_effect">Wikipedia</a></span>

<!--
Maximilien Ringelmann was a French agricultural engineer in the late 19th Century. While studying the relationship between process loss (i.e., reductions in performance effectiveness or efficiency) and group productivity, he found that having group members work together on a task (e.g., pulling a rope) actually results in significantly less effort than when individual members are acting alone. Ringelmann discovered that as more and more people are added to a group, the group often becomes increasingly inefficient, ultimately violating the notion that group effort and team participation reliably leads to increased effort on behalf of the members.
-->

---
layout: image-left
image: /img/slides/teamwork-breakdowns.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

### Common Causes of _Teamwork_ Breakdowns

* Lack of shared understanding and commitment
* Team size and dynamics

<v-clicks>

* Lack of trust
* Insuffient resources
* Unclear goals and expectations

</v-clicks>

<!--
This can also cause communication breakdowns and a general decline in team cohesion. [click]**Lack of Trust:** Without trust, team members hesitate to communicate openly and honestly. This inhibits problem-solving, stifles creativity, and can lead to unresolved conflicts. [click]**Insufficient Resources:** Teams require adequate resources, including time, budget, and tools, to complete tasks effectively. A lack of resources can lead to burnout, missed deadlines, and subpar results. [click]**Unclear Goals and Expectations:** When team members don't understand project objectives or their roles within the team, they struggle to prioritize tasks, make decisions, and work together effectively.
-->

---
layout: image-right
image: /img/slides/improve-human-factor.jpg
backgroundSize: contain
class: my-cool-content-on-the-left
---

## Communication & Teamwork breakdowns?
### Improve the Human Factor.

<!--
As we've seen, communication and teamwork breakdowns pose significant challenges in modern software development, potentially leading to project delays, increased costs, and even project failures. By understanding these common causes, we can take some proactive steps to mitigate the risks by implementing some solutions to improve the human factor - BEFORE we start thinking about AI and automation.
-->

---
layout: section
---

# Improving the Human Factor in DevOps
## Fostering Open and Honest Communication

<!--
We can start by fostering open and honest communication within our teams.
-->

---
layout: image-right
image: /img/slides/clear-comm-channels.jpg
backgroundSize: contain
class: my-cool-content-on-the-left
---

## Fostering Open and Honest Communication
### Establish Clear Communication Guidelines

<v-clicks>

* Appropriate communication channels
* Expected response times
* Meeting etiquette
* Concise and solution-oriented communication

</v-clicks>

<!--
Some key things to think about when establishing clear communication guidelines. [click]**Appropriate Communication Channels:** Specify which channels to use for different types of communication (e.g., email for formal announcements, instant messaging for quick questions, project management tools for task updates). [click]**Expected Response Times:** Set clear expectations for response times to messages, ensuring timely communication and preventing delays. [click]**Meeting Etiquette:** Establish guidelines for effective meetings, including agenda setting, time management, and encouraging active participation. [click]**Concise and Solution-Oriented Communication:** When communicating with managers or stakeholders, prioritize concise and solution-oriented messages. Focus on providing clear summaries, highlighting key issues, and offering potential solutions.
-->

---
layout: image-right
image: /img/slides/knowledge-sharing.jpg
backgroundSize: contain
class: my-cool-content-on-the-left
---

## Fostering Open and Honest Communication
### Break Down Information Barriers

<v-clicks>

* Encourage Documentation
* Use Knowledge Sharing Platforms
* Promote Cross-Team Communication
* Simplify Technical Talk

</v-clicks>

<!--
To prevent information silos and promote knowledge sharing:
[click]**Encourage Documentation:** Ensure all project details are recorded and accessible to prevent confusion. [click]**Use Knowledge Sharing Platforms:** Centralize information through platforms to enhance team access and collaboration. [click]**Promote Cross-Team Communication:** Facilitate inter-team communication to share knowledge and avoid conflicts. [click]**Simplify Technical Talk:** Avoid jargon wherever possible, or have a central location where it's explained. Use visuals to illustrate complex concepts. Make sure the necessar context and background is clear for all participants in conversations, discussions, and decisions.
-->

---
layout: image-left
image: /img/slides/right-tools.jpg
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Fostering Open and Honest Communication
### Use the Right Tools

<v-clicks>

* Choose Tools that Meet Team Needs
* Integrate Tools for Seamless Workflow
* Provide Training and Support

</v-clicks>

<!--
Selecting appropriate communication and collaboration tools is essential.
[click]**Choose Tools that Meet Team Needs:** Select tools that align with the team's size, project complexity, and communication preferences. [click]**Integrate Tools for Seamless Workflow:** Ensure chosen tools integrate seamlessly to avoid complexity and context switching. [click]**Provide Training and Support:** Offer training and ongoing support to team members on effective tool usage.
-->

---
layout: image-right
image: /img/slides/critical-thinking.jpg
backgroundSize: contain
class: my-cool-content-on-the-left
---

## Fostering Open and Honest Communication
### Promote Critical Thinking

<v-clicks>

* Encourage Questioning and Analysis
* Provide Opportunities for Collaborative Problem-Solving
* Emphasize Continuous Improvement

</v-clicks>

<!--
Critical thinking is essential for effective communication and problem-solving. [click]**Encourage Questioning and Analysis:** Promote a culture where team members freely question and critically analyze information. [click]**Provide Opportunities for Collaborative Problem-Solving:** Facilitate team activities that enhance collaborative problem-solving and critical thinking. [click]**Emphasize Continuous Improvement:** Instill a mindset of ongoing evaluation and enhancement of communication practices.
-->

---
layout: image-left
image: /img/slides/open-comms-active-listening.jpg
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Fostering Open and Honest Communication
### Practice Open Communication and Active Listening

<v-clicks>

* Encourage Feedback and Open Dialogue
* Value Diverse Perspectives
* Provide Training on Active Listening Techniques
* Address Conflicts Constructively

</v-clicks>

<!--
Creating a supportive and inclusive environment, along with active listening, is crucial for effective communication.
[click]**Encourage Feedback and Open Dialogue:** Create a safe space for open and honest communication. [click]**Value Diverse Perspectives:** Embrace diverse viewpoints and actively listen to all team members. [click]**Provide Training on Active Listening Techniques:** Equip team members with active listening skills to enhance communication. [click]**Address Conflicts Constructively:** Establish clear processes for resolving conflicts effectively.
-->

---
layout: image-right
image: /img/slides/focus-on-shared-goals.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

## About Constructive Conflict Resolution...

<v-clicks>

* Focus on Shared Goals
* Empathy and Perspective-Taking
* Collaborative Problem-Solving
* Mediation and Facilitation

</v-clicks>

<!--
How many of you have been in a situation where a conflict arose within your team? Conflict is inevitable in any team, but how we manage it can make all the difference.
[click]**Focus on Shared Goals:** Remind the team of their common objectives and how resolving the conflict will help them achieve those goals. [click]**Empathy and Perspective-Taking:** Encourage team members to understand and appreciate different viewpoints. [click]**Collaborative Problem-Solving:** Frame conflict as a problem to be solved together, rather than a battle to be won. [click]**Mediation and Facilitation:** When necessary, utilize neutral third parties to help facilitate constructive conversations. Make sure that is not a company/HR resource.
-->

---
layout: image-left
image: /img/slides/regular-appreciation.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

# The Human Factor in DevOps
## Building a Culture of Value and Recognition

<v-clicks>

* Regular Appreciation
* Growth Opportunities
* Inclusive Environment
* Celebrate Successes

</v-clicks>

<!--
In order to really foster a positive and productive team environment, it's essential to build a culture of value and recognition. [click]**Regular Appreciation:** Implement consistent practices for recognizing and appreciating individual and team efforts, both big and small. [click]**Growth Opportunities:** Provide opportunities for professional development, mentorship, and skill-building to show investment in team members' growth. [click]**Inclusive Environment:** Foster an inclusive environment where everyone feels respected, valued, and empowered to contribute their unique perspectives. [click]**Celebrate Successes:** Celebrate both individual and team accomplishments, creating a shared sense of achievement.
-->

---
layout: section
---

# The _Human_ Factor in DevOps
## Even 🤖's Can be a Good Teammate (Mostly)

<!--
As I stated earlier, I'm saying this again: DevOps is not just about tools and automation - it all starts with people and how they work together. We have to get that all functioning first before we throw some computer and some ML models in the form of a hipster SaaS company that promises that you'll never have another issue with communication again. Just like we don't throw an AI Agent at any data without first understanding the data, the problem we're trying to solve, and even if the data is correct, as well as the potential biases that could be introduced. So start there.
-->

---
layout: section
---

## AI's impact on teams

<!--
Now, with that being said, how many of your companies have implemented AI in some form or another? AI has become a valuable tool in DevOps, helping teams automate repetitive tasks, analyze data, and make more informed decisions. But as AI becomes more integrated into our workflows, it's essential to consider its impact on team communication and dynamics.
-->

---
layout: image-right
image: /img/slides/ai-positive-impacts.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

## AI's impact on teams
### Positive Impacts

<v-clicks>

* Enhanced communication
* Automated scheduling and coordination
* Shared knowledge bases
* Improved collaboration and efficiency
* Data-driven decision-making and innovation

</v-clicks>

<!--
AI can have a real positive impact on team communication and function in several ways. [click]**Enhanced Communication:** AI fosters seamless and inclusive communication through real-time translation and personalized experiences. [click]**Automated Scheduling and Coordination:** AI streamlines workflows and prioritizes communication, maximizing team efficiency. [click]**Shared Knowledge Bases:** AI ensures quick access to essential information, promoting effective knowledge sharing and collaboration. [click]**Improved Collaboration and Efficiency:** AI enhances teamwork and productivity by automating tasks and providing integrated workspaces. [click]**Data-Driven Decision-Making and Innovation:** AI empowers informed decisions and creative solutions through data analysis and insight generation.
-->

---
layout: image-left
image: /img/slides/ai-negative-impacts.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

## AI's impact on teams
### Negative Impacts

<v-clicks>

* Reduced casual interactions
* Over-reliance on technology
* Potential job displacement
* Bias and discrimination
* Distrust of AI

</v-clicks>

<!--
However, there are some definite negative impacts as well. [click]**Reduced Casual Interactions:** AI-driven tools may reduce the need for casual, face-to-face interactions, potentially weakening informal workplace relationships. [click]**Over-Reliance on Technology:** Over-dependence on AI in communication risks diminishing human connection and creating a disconnect between employees and the organization. [click]**Job Displacement:** AI-powered automation may lead to job displacement in certain roles, causing anxiety and uncertainty among employees. [click]**Bias and Discrimination:** AI algorithms can perpetuate existing biases, leading to unfair outcomes in communication and decision-making. [click]**Distrust of AI:** Human workers may dislike working with AI agents due to a lack of trust and suspicion, potentially hindering AI adoption and team cohesion.
-->

---
layout: statement
---

> "...even in a task where AI outperforms humans, the replacement of a human player by an automated videogame agent decreases team performance. <br>
> While automation may improve performance in tasks suited to machine learning, we posit that their introduction presents a larger trade-off by disrupting these routines."

<span class="text-sm" style="float:left; text-align:left; padding-bottom: 40px;">_Dell'Acqua, Fabrizio_ and _Kogut, Bruce_ and _Perkowski, Patryk_ (December 21, 2022).<br />
Super Mario Meets AI: Experimental Effects of Automation and Skills on Team Performance and Coordination.<br />
Review of Economics and Statistics, Available at SSRN: https://ssrn.com/abstract=3746564<br /></span>

![alt text](/img/slides/super-mario-party.jpg)

<!--
A study was conducted at Columbia Business School where they had participants play Super Mario Party, a video game, with a mini-game called "Dash and Dine" which has the players perform different tasks with a teammate. Then they randomly replaced a human player with an automated agent from the game They found that even in a task where AI outperformed humans, the replacement of a human player by an automated videogame agent decreased team performance. While automation may improve performance in tasks suited to machine learning, the introduction of AI presents a larger trade-off by disrupting routines.
-->

---
layout: center
---

![alt text](/img/slides/unesco-ai-recommendation.jpg)

<span style="position: absolute; bottom: 10%; right: 10px; color: yellow; font-style: italic;">Source: <a href="https://unesdoc.unesco.org/ark:/48223/pf0000385082.locale=en">UNESCO</a></span>

<!--
UNESCO in 2023 acknowledged the opportunity for AI, but also warned that AI  raises "profound ethical concerns, arising from the potential AI systems have to embed biases, contribute to climate degradation, threaten human rights and more. Such risks associated with AI have already begun to compound on top of existing inequalities,  resulting in further harm to already marginalised groups.
-->

---

## Ethical considerations for AI in team communication

<span style="text-align: center;">

<v-clicks>

* Data privacy and security
* Transparency
* Fairness and bias
* Accountability
* Employee involvement

</v-clicks>

</span>

<!--
If you're implementing AI in your organization, in any way, here are some ethical considerations to think about: [click]**Data Privacy:** Protect employee data and ensure compliance with data protection regulations. [click]**Transparency:** Be transparent about how AI tools are used and the data they collect. [click]**Fairness:** Ensure AI systems are free from bias and do not discriminate against any individuals or groups. Use a third-party to verify or an internal ERG. Continually review. [click]**Accountability:** Establish clear lines of responsibility and accountability for AI-driven decisions and actions. [click]**Employee Involvement:** Involve employees in the decision-making process for AI implementation to foster excitement, engagement, and responsible AI usage.
-->

---
layout: two-cols
layoutClass: gap-8
---

![alt text](/img/slides/group_chat_sentiment.jpg)

::right::

![alt text](/img/slides/ai_meeting_summaries.jpg)

<!--
While AI is a valuable tool in DevOps, true success comes from prioritizing human connection, communication, and collaboration. AI can summarize lengthy threads, translate messages in real-time for global teams, suggest quick replies, and even detect sentiment in messages to identify potential communication breakdowns - but it can't replace the human touch or understanding of complex emotions and interactions.
-->

---
layout: center
---

# The _Human_ in DevOps

## Applying DevOps Principles to AI

<v-clicks>

* **Collaboration:** Break down silos and foster teamwork to ensure AI success.
* **Automation:** Streamline workflows by automating tasks to boost productivity.
* **Continuous Improvement:** Iteratively refine AI tools through constant monitoring and feedback.
* **Feedback Loops:** Use AI to gather and implement customer feedback to enhance user experience.

</v-clicks>

<!--
DevOps principles, with their emphasis on collaboration, automation, and continuous improvement, can be instrumental in maximizing the benefits of AI in team settings: [click]**Collaboration:** Encourage cross-functional collaboration between development, operations, and other teams to ensure AI tools are implemented effectively and ethically. [click]**Automation:** Automate repetitive tasks using AI tools to free up time for more strategic work and improve efficiency. [click]**Continuous Improvement:** Continuously monitor and evaluate the performance of AI tools, gather feedback, and make adjustments to optimize their effectiveness. [click]**Feedback Loops:** Use AI to gather and implement customer feedback to improve products and services and enhance user experience.
-->

---
layout: center
---

# The _Human_ in DevOps...
## Can also apply to your 🤖 teammate

<!--
- The future will see increased AI integration in teamwork, requiring organizations to adapt and learn for responsible and ethical use.
- Creating a human-centered workplace with AI demands ongoing investment in training, ethical guidelines, and fostering collaboration and trust.
- Organizations must strategically and ethically implement AI, using DevOps principles to maximize benefits and minimize risks.
-->

---
layout: two-cols
layoutClass: gap-8
---


<div style="padding-top:200px; align-items: center; justify-content: center; margin: 0 auto; display: flex;">

  <h2>Thank you!</h2>

</div>

::right::

<div class="text-left" style="padding-left: 75px;">
  <p><img src="/img/bluesky-logo.svg" style="vertical-align: middle; display: inline; margin: 5px; max-height:50px; padding-right:10px">@jerdog.dev</p>
  <p><img src="/img/linkedin.png" style="vertical-align: middle; display: inline; margin: 5px; max-height:50px; padding-right:10px">/in/jeremymeiss</p>
  <p><img src="/img/devto.png" style="vertical-align: middle; display: inline; margin: 5px; max-height:50px; padding-right:10px">@jerdog</p>
  <p><img src="/img/mastodon.png" style="vertical-align: middle; display: inline; margin: 5px; max-height:50px; padding-right:10px">@jerdog@hachyderm.io</p>
  <p><img src="/img/www.png" style="vertical-align: middle; display: inline; margin: 5px; max-height:50px; padding-right:10px">jmeiss.me</p>
  <p style="text-decoration: line-through;"><img src="/img/twitter.png" style="vertical-align: middle; display: inline; margin: 5px; max-height:50px; padding-right:10px;">@IAmJerdog</p>
</div>

---
layout: end
---
