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
conference: ""
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
  layout: center
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

layout: intro-image-right
image: /img/slides/humans_and_robot-teammates.jpeg
backgroundSize: contain
---

# The Human Factor in DevOps...
## Because Even 🤖 Need Good Teammates (Almost)

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

## DevOps is more than tools

### It's about people

<!--
DevOps is not just about tools and automation, but about people and how they work together. In this talk, we will explore the importance of fostering open and honest communication, constructive conflict resolution, and building a culture of value and recognition within your DevOps team. Emphasizing the importance of the human element in DevOps, even in an increasingly automated world.
-->

---
layout: two-cols
---

## Jeremy

::right::

---

## Communication & Teamwork breakdowns in the modern workplace


<!--
A multitude of factors can contribute to communication and teamwork breakdowns in the dynamic environment of software development. I'm sure everyone could come up with an example. Maybe you're sitting next to one right now... don't look, but blink twice if you can relate. What are some of the causes of communication breakdowns that you have seen (don't feel like you need to be specific)?
-->

---
layout: image-right
image: /img/slides/comms-breakdowns.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

### Common Causes of Communication Breakdowns

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

### Common Causes of Communication Breakdowns

<v-clicks>

* Conflicting Ideas and Poor Collaboration
* Barriers to Cross-Cultural and Linguistic Communication
* Ineffective Organizational Structures and Communication Processes
* Ambiguous Project Requirements and Technical Miscommunication
* Communication Skill Deficiencies and Overload

</v-clicks>

<!--
A multitude of factors can contribute to communication and teamwork breakdowns in the dynamic environment of software development. Some of the most prevalent causes are: [click]**Conflicting Ideas and Poor Collaboration:** Diverse perspectives are common in software development, but unresolved conflicts can lead to confusion, hinder progress, and significantly reduce productivity. [click]**Barriers to Cross-Cultural and Linguistic Communication:**Globalized teams face challenges due to varying cultural backgrounds and language proficiencies, causing misunderstandings and errors. [click]**Ineffective Organizational Structures and Communication Processes:** Complex team hierarchies and inadequate communication tools or protocols contribute to information silos, delayed decisions, and reduced transparency. [click]**Ambiguous Project Requirements and Technical Miscommunication:** Unclear project requirements and miscommunication between developers (e.g., technical jargon, poor documentation) result in assumptions, rework, and increased development time. [click]**Communication Skill Deficiencies and Overload:** Lack of effective communication skills, combined with information overload, leads to missed deadlines, overlooked issues, and overall team incohesion.
-->

---
layout: section
---

# The Human Factor in DevOps
## Fostering Open and Honest Communication

<!--

-->

---
layout: image-left
image: /img/slides/open-honest-comms.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Fostering Open and Honest Communication

### Active Listening

<!--
Active Listening: Encourage team members to truly listen and understand each other's perspectives.
-->

---
layout: image-left
image: /img/slides/psychological-safety.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Fostering Open and Honest Communication

### Active Listening
### Psychological Safety

<!--
Psychological Safety: Create a safe space where people feel comfortable expressing their ideas, concerns, and even mistakes without fear of judgment.
-->

---
layout: image-left
image: /img/slides/feedback-loop.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Fostering Open and Honest Communication

### Active Listening
### Psychological Safety
### Regular Feedback

<!--
Regular Feedback: Establish regular channels for giving and receiving constructive feedback, both individually and as a team.
-->

---
layout: image-left
image: /img/slides/clear-comms-channels.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Fostering Open and Honest Communication

### Active Listening
### Psychological Safety
### Regular Feedback
### Clear Communication Channels

<!--
Clear Communication Channels: Utilize appropriate communication tools and platforms for different purposes (e.g., chat for quick updates, video calls for in-depth discussions).
-->

---

# The Human Factor in DevOps
## Constructive Conflict Resolution

<!--
How many of you have been in a situation where a conflict arose within your team? Conflict is inevitable in any team, but how we manage it can make all the difference.
-->

---
layout: image-right
image: /img/slides/focus-on-shared-goals.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

## Constructive Conflict Resolution

### Focus on shared goals

<!--
Focus on Shared Goals: Remind the team of their common objectives and how resolving the conflict will help them achieve those goals.
-->

---
layout: image-right
image: /img/slides/different-perspectives.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

## Constructive Conflict Resolution

### Focus on shared goals
### Empathy and Perspective-Taking

<!--
Empathy and Perspective-Taking: Encourage team members to understand and appreciate different viewpoints.
-->

---
layout: image-right
image: /img/slides/collaborative-problem-solving.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

## Constructive Conflict Resolution

### Focus on shared goals
### Empathy and Perspective-Taking
### Collaborative Problem-Solving

<!--
Collaborative Problem-Solving: Frame conflict as a problem to be solved together, rather than a battle to be won.
-->

---
layout: image-right
image: /img/slides/mediation-facilitation.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

## Constructive Conflict Resolution

### Focus on shared goals
### Empathy and Perspective-Taking
### Collaborative Problem-Solving
### Mediation and Facilitation

<!--
Mediation and Facilitation: When necessary, utilize neutral third parties to help facilitate constructive conversations.
-->

---

# The Human Factor in DevOps
## Building a Culture of Value and Recognition

<!--

-->

---
layout: image-left
image: /img/slides/regular-appreciation.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Building a Culture of Value and Recognition

### Regular Appreciation

<!--
Regular Appreciation: Implement consistent practices for recognizing and appreciating individual and team efforts, both big and small.
-->

---
layout: image-left
image: /img/slides/growth-opp.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Building a Culture of Value and Recognition

### Regular Appreciation
### Growth Opportunities

<!--
Growth Opportunities: Provide opportunities for professional development, mentorship, and skill-building to show investment in team members' growth.
-->

---
layout: image-left
image: /img/slides/inclusive-environment.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Building a Culture of Value and Recognition

### Regular Appreciation
### Growth Opportunities
### Inclusive Environment

<!--
Inclusive Environment: Foster an inclusive environment where everyone feels respected, valued, and empowered to contribute their unique perspectives.
-->

---
layout: image-left
image: /img/slides/celebrating-successes.webp
backgroundSize: contain
class: my-cool-content-on-the-right
---

## Building a Culture of Value and Recognition

### Regular Appreciation
### Growth Opportunities
### Inclusive Environment
### Celebrate Successes

<!--
Celebrate Successes: Celebrate both individual and team accomplishments, creating a shared sense of achievement.
-->

---
layout: section
---

# AI's impact on teams

<!--
How many of your companies have implemented AI in some form or another? AI has become a valuable tool in DevOps, helping teams automate repetitive tasks, analyze data, and make more informed decisions. But as AI becomes more integrated into our workflows, it's essential to consider its impact on team communication and dynamics.
-->

---
layout: statement
---

> "...even in a task where AI outperforms humans, the replacement of a human player by an automated videogame agent decreases team performance. <br>
> While automation may improve performance in tasks suited to machine learning, we posit that their introduction presents a larger trade-off by disrupting these routines."

<span class="text-sm" style="float:left; text-align:left;">_Dell'Acqua, Fabrizio_ and _Kogut, Bruce_ and _Perkowski, Patryk_ (December 21, 2022).<br />
Super Mario Meets AI: Experimental Effects of Automation and Skills on Team Performance and Coordination.<br />
Review of Economics and Statistics, Available at SSRN: https://ssrn.com/abstract=3746564<br /></span>

<!--
A study was conducted at Columbia Business School where they had participants play Super Mario Party, a video game, with a mini-game called "Dash and Dine" which has the players perform different tasks with a teammate. Then they randomly replaced a human player with an automated agent from the game They found that even in a task where AI outperformed humans, the replacement of a human player by an automated videogame agent decreased team performance. While automation may improve performance in tasks suited to machine learning, the introduction of AI presents a larger trade-off by disrupting routines.
-->

---

<!--

-->


---
layout: two-cols-header
layoutClass: gap-8
---

## AI's impact on team communication and function

::left::

### Positive Impacts

<v-clicks>

* Enhanced communication
* Automated scheduling and coordination
* Shared knowledge bases
* Improved collaboration and efficiency
* Data-driven decision-making and innovation

</v-clicks>

::right::

### Negative Impacts

<v-clicks>

* Reduced casual interactions
* Over-reliance on technology
* Potential job displacement
* Bias and discrimination
* Distrust of AI

</v-clicks>

<!--

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
layout: default
---

## Ethical considerations for AI in team communication

* Data privacy and security
* Transparency
* Fairness and bias
* Accountability
* Employee involvement

<!--

-->

---
layout: image
image: /img/slides/comms_overload.jpg
backgroundSize: contain
---

# Fostering Open and Honest Communication


<!--
How many of you have had a conversation with a chatbot or AI assistant and thought, "Wow, they really get me"? Probably not many. While AI has made significant strides in understanding and responding to human language, it still falls short in capturing the nuances of human emotions and interactions.
Start with a humorous anecdote about the limitations of AI in understanding and addressing human emotions and complexities.
Transition to the core message: While AI is a valuable tool in DevOps, true success comes from prioritizing human connection, communication, and collaboration.


Effective communication is the bedrock of any successful team, especially in the fast-paced world of DevOps. This section will explore practical techniques for creating a safe and transparent communication environment.

Sub-points:
Establishing clear communication channels (e.g., chat, regular meetings).
Promoting active listening and giving constructive feedback.
Creating a culture where it's okay to make mistakes and ask for help.
Examples: Implementing daily stand-ups, blameless postmortems, and regular feedback sessions.
-->

---
layout: two-cols
layoutClass: gap-4
---

![alt text](/img/slides/group_chat_sentiment.jpg)

::right::

![alt text](/img/slides/ai_meeting_summaries.jpg)

<!--
While AI is a valuable tool in DevOps, true success comes from prioritizing human connection, communication, and collaboration. AI can summarize lengthy threads, translate messages in real-time for global teams, suggest quick replies, and even detect sentiment in messages to identify potential communication breakdowns - but it can't replace the human touch or understanding of complex emotions and interactions.
Briefly outline the key points of the talk: open communication, conflict resolution, and building a culture of value and recognition, with AI as a supporting tool.
-->

---
layout: image-right
image: /img/slides/open-honest-comms.webp
backgroundSize: contain
class: my-cool-content-on-the-left
---

## Fostering Open Communication

<v-clicks>

- Active Listening
- Psychological Safety
- Regular Feedback
- Clear Communication Channels

</v-clicks>


<!--
Discuss the crucial role of open communication in DevOps and provide practical strategies for cultivating it within teams.

Emphasize the importance of open and honest communication in breaking down silos and building trust.
Provide actionable strategies for fostering open communication:
Active Listening: Encourage team members to truly listen and understand each other's perspectives.
Psychological Safety: Create a safe space where people feel comfortable expressing their ideas, concerns, and even mistakes without fear of judgment.
Regular Feedback: Establish regular channels for giving and receiving constructive feedback, both individually and as a team.
Clear Communication Channels: Utilize appropriate communication tools and platforms for different purposes (e.g., chat for quick updates, video calls for in-depth discussions).


## Effective communication is crucial, and AI can help enhance it.
AI-powered Communication Platforms: Tools like Slack, Microsoft Teams, and Google Workspace are integrating AI features.
Usage: AI can summarize lengthy threads, translate messages in real-time for global teams, suggest quick replies, and even detect sentiment in messages to identify potential communication breakdowns.

Sentiment Analysis Tools: Standalone tools or APIs (e.g., Google Cloud Natural Language API, Amazon Comprehend) can analyze text and voice data.
Usage: These can be used to monitor team communication channels for negative sentiment or signs of stress, allowing managers to proactively address issues.

AI-driven Meeting Summarization: Tools like Otter.ai, Fireflies.ai, and Zoom's smart summaries.
Usage: These tools automatically generate transcripts and summaries of meetings, ensuring everyone is on the same page and reducing the need for extensive note-taking. This also allows for searching meeting content later for key decisions or action items.

Emphasize the importance of open and honest communication in DevOps, especially in a fast-paced, ever-changing environment.
Discuss the challenges of communication in remote and hybrid teams, and how AI can help bridge the gap.
Introduce the concept of AI-powered communication tools and how they can facilitate more effective communication.

-->

---

# Constructive Conflict Resolution


<!--
Conflict is inevitable in any team. This section will focus on strategies for managing conflict constructively and turning potentially negative situations into opportunities for growth.

Sub-points:
Recognizing different conflict styles and communication preferences.
Developing strategies for de-escalating tense situations.
Focusing on solutions rather than assigning blame.
Examples: Using collaborative problem-solving techniques, mediation, and establishing clear guidelines for conflict resolution.
-->

---

## AI can help identify potential conflict triggers and facilitate more objective discussions.

<!--
AI-powered Conflict Detection: Using sentiment analysis and communication pattern analysis to identify early signs of conflict.
Usage: By analyzing communication patterns (e.g., increased negativity, decreased communication frequency, changes in tone), AI can alert managers to potential conflicts before they escalate.

AI-facilitated Mediation: While not fully replacing human mediators, AI tools can provide objective data and insights to help guide discussions.
Usage: AI can analyze communication during mediation sessions to identify areas of agreement and disagreement, suggest potential solutions, and ensure that all parties are being heard.

Bias Detection Tools: Tools that analyze text for unconscious bias.
Usage: These can be used to review communication and ensure that language is inclusive and respectful, reducing the potential for misunderstandings and conflict.
-->

---

# Building a Culture of Value and Recognition


<!--
A team that feels valued and appreciated is more likely to be engaged and productive. This section will explore ways to create a positive and supportive team culture.

Sub-points:
Recognizing individual and team accomplishments.
Providing opportunities for professional development and growth.
Creating a sense of belonging and shared purpose.
Examples: Implementing peer-to-peer recognition programs, providing training opportunities, and organizing team-building activities.
-->

---

## AI can help ensure recognition is fair and consistent.

<!--
AI-driven Performance Analytics: Tools that analyze performance data to identify top performers and areas for improvement.
Usage: These tools can help ensure that recognition is based on objective data rather than subjective opinions, promoting fairness and transparency.

Automated Recognition Platforms: Platforms that use AI to personalize recognition and rewards.
Usage: These platforms can analyze employee preferences and suggest personalized rewards and recognition, making the process more meaningful and impactful.
-->

---

# Conclusion

---

## Thank you!