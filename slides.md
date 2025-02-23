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
Remember when "DevOps" meant throwing code (and maybe a few passive-aggressive emails, that thankfully weren’t meetings) over the wall? How "not my code, not my problem" was a common enough phrase?
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
layout: image
image: /img/slides/comms_overload.jpg
backgroundSize: contain
---

# Fostering Open and Honest Communication


<!--
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