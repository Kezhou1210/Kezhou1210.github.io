---
title: Research Interest
summary: 
date: 2024-10-07
type: docs
math: false
tags:
  - JavaScript
image:
  caption: ''
---
## Introduction:

With the advancement of technology, human-computer interaction has evolved from simple text entry through the Command Line Interface (CLI) to the widely recognized and utilized WIMP (Windows, Icons, Menus, Pointer) interaction paradigm. In recent years, the emergence of Virtual Reality (VR), Augmented Reality (AR), and Mixed Reality (MR) has further expanded the boundaries of human-computer interaction. These technologies transcend traditional two-dimensional screens, immersing users in three-dimensional virtual environments where interaction can be achieved through a variety of modalities, including gesture recognition, voice commands, and even haptic feedback. This shift has paved the way for more natural user interfaces, where individuals can interact with digital content in ways that mimic real-world interactions. Despite the potential of VR/AR/MR technologies, their current applications remain largely confined to niche areas such as gaming, entertainment, and specific professional training scenarios. This limited scope has led to questions about how these immersive technologies can be further developed to enhance user experiences across various domains. My goal is to make the use of VR/AR/MR technologies as ubiquitous and immersive as depicted in popular media, such as Ready Player One and Sword Art Online, ultimately transforming how individuals interact with digital content in their everyday lives.
In order to enhance user immersion in VR/AR/MR environments, my research interests are primarily focused on the following four aspects:

## Individual interaction

In VR/AR/MR experiences, users often encounter sensory conflict, where discrepancies between visual input and real input (such as position, motion direction, and speed) lead to perceptual and cognitive dissonance. This issue arises in various contexts, such as remote surgeries where VR assists surgeons in controlling robotic arms for precise operations, or in rehabilitation therapy, where VR helps amputees simulate missing limbs for faster recovery. Similarly, in VR/AR games, users' virtual avatars may undergo changes, triggering sensory conflict. These conflicts can create a sense of unease or discomfort and, when combined with physical movement, may result in symptoms like motion sickness or dizziness.

To address these issues, the best way is to study the different types of sensory conflict and develop targeted intervention strategies. By systematically analyzing the commonalities across these interventions, we could propose solutions that minimize external interference, alleviating sensory conflicts and enhancing user immersion in VR/AR/MR. We could explore how users' experiences change when their hand or head movements are separated from their proprioception, and how interventions like the rubber hand illusion can be employed to reduce the dissonance. By understanding how to effectively address these conflicts with minimal external input, we can create more immersive and comfortable VR/AR/MR experiences.


## Interaction Between human-environments

VR/AR/MR technologies expand the interaction space from two-dimensional planes to three-dimensional environments, presenting new opportunities and challenges. A key research focus is how to organize and manage virtual windows effectively in these environments to avoid the clutter and occlusion problems common in traditional WIMP interfaces. For instance, in AR environments, virtual windows can be semantically linked to real-world objects, allowing for intuitive placement within the physical space. By associating virtual windows with the corresponding real-world locations, users can quickly find the relevant window based on their familiarity with the environment. 

Additionally, when users transition between different environments, how the layout of virtual windows should adapt and evolve during these transitions remains an open research question. Through reinforcement learning, various environmental factors—such as task characteristics, the level of environmental congestion, and the placement of real-world objects—can be iteratively considered to optimize virtual window layouts. By continuously learning from these factors, the system can dynamically adjust and achieve the most optimal window arrangement for different environments. This approach aims to minimize the movement and number of window repositioning actions during transitions between environments, ensuring a smoother and more efficient user experience. 

Also, managing virtual windows efficiently in VR/AR/MR is critical. Most current window management systems rely on controllers or raycasting for basic actions like opening and closing windows. These methods tend to offer limited interaction options and focus on single-point actions, which can restrict the flexibility and efficiency of managing windows in VR/AR/MR environments. Just as iOS system allows users to swipe up to access the window management system, similar gestures can be applied in immersive environments instead of dragging the virtual windows in space. Window management could be integrated into the user's palm, turning the hand into an interaction surface. This approach not only provides tactile feedback but also reduces interaction complexity, improving overall efficiency. 

In AR/MR environments, immersion can also be enhanced by incorporating real-world objects to provide haptic and multimodal feedback. For example, rotating a bottle cap could function as a switch for a lamp, or sliding a finger along the edge of a table could simulate adjusting volume with a virtual slider. To improve immersion, research needs to explore how physical affordances of real-world objects can be utilized for interaction, as well as what other factors—beyond physical similarity—should be considered when choosing objects as interactive interfaces in AR/MR environments.

Another major future application of VR/AR/MR will involve presenting everyday data in a visualized, interactive format. However, the format, placement, and duration of this data visualization significantly affect the user experience. It is essential to study how users interact with these data visualizations, such as how they split or merge datasets, or conduct focused analysis on specific data points.


## Interaction between human-human

When people from different regions communicate in VR/AR/MR environments, simply presenting the other party as a virtual avatar adds an extra dimension to the typical 2D video call but does little to enhance the depth of interaction. To improve immersion in such interactions, additional modalities can be introduced. For example, using small robots to locally simulate the movements of a remote user can replace traditional virtual interaction. The local user interacts with the robot, which mirrors the actions of the remote participant, enhancing the sense of presence through haptic feedback. This approach allows physical interaction to complement the visual and auditory components, creating a more immersive experience.

In multi-person conversations, the absence of physical constraints in virtual environments can lead to challenges, such as all voices being transmitted equally, resulting in a chaotic and noisy atmosphere. To address this, a combination of gestures and gaze tracking could enable users to engage in focused conversations with specific individuals or small groups without disrupting the larger discussion. This selective interaction can greatly enhance immersion by mimicking the natural flow of real-world conversations, where attention is often directed through visual and physical cues.


## Interaction between human-AI

The integration of AI into VR/AR/MR systems offers numerous opportunities to enhance user experiences across various dimensions. Besides the familiar applications of AI in data visualization and window management. AI has the potential to act as a surrogate for human users in experiments, allowing researchers to gather and analyze larger datasets than would be feasible through traditional user experiments. This capability addresses the common issue of small sample sizes in user studies, ultimately leading to more robust and quantifiable findings that can substantiate experimental conclusions.

However, several critical questions must be addressed when considering the use of AI in user experiments. Firstly, what types of user experiments are suitable for AI integration? Identifying experiments that can benefit from AI's data processing capabilities is essential for maximizing its effectiveness. Additionally, it is crucial to determine how to adjust AI algorithms to align with the experimental logic, ensuring that the AI's behavior accurately reflects realistic user interactions. Furthermore, incorporating variables and disturbance factors that simulate real user behaviors is vital for enhancing the validity of AI-driven experiments. Researchers must explore how to introduce these interference factors effectively, allowing the AI to engage in experiments that mirror actual user experiences.

