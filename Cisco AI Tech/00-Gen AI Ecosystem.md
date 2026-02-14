## Start
Our deliverable in three weeks is a formal presentation to the leadership team that answers three core business questions:

- **Technology:** What is this technology, and what are the major, credible tools the organization should consider?
- **Application:** What are some realistic, low-risk use cases where we could apply this technology to improve productivity in areas like project management, system administration, or content creation?
- **Recommendation:** Based on your findings, what is the most practical "quick win" the team should pilot first?
---

## Diffusion Models: The Engines of Imagery

While LLMs are masters of text, a different class of model is responsible for the explosion of AI-generated art and imagery: the **diffusion model**. Diffusion models work through a fascinating two-step process. First, during training, they systematically add random noise to images from their training data until the original image is completely obscured. They learn this process at every step. Then, to generate a new image, the model reverses this process: starting with pure random noise, it skillfully removes the noise step-by-step until a coherent, high-quality image that matches the user's text prompt is formed.

This capability allows diffusion models to produce a range of powerful image-based outputs, including:

[![A central icon labeled Diffusion Model has arrows pointing out to various image icons labeled Photorealistic Images, Digital Art, Logos and Icons, Image Editing.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-Diffusion-00.svg "A central icon labeled Diffusion Model has arrows pointing out to various image icons labeled Photorealistic Images, Digital Art, Logos and Icons, Image Editing.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-Diffusion-00.svg)

As shown in the diagram, these are some of the common outputs from diffusion models:

- **Photorealistic Images:** Creating images that look like real photographs
    
- **Digital Art:** Generating illustrations, paintings, and concept art in various styles
    
- **Logos and Icons:** Designing basic graphical assets for branding
    
- **Image Editing:** Modifying existing images, such as removing objects or changing backgrounds (a process often called "inpainting")
    

## Specialized Models: Audio and Code

Beyond text and images, specialized models exist for other data types. **Audio generation models** are trained on vast datasets of sound, music, and speech. They can be used to produce novel outputs, as shown in the figure below:

[![A central icon labeled Audio Generation Mode has arrows pointing out to various image icons labeled Text to Speech, Music Composition, and Sound Effects.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-AudioModel-00.svg "A central icon labeled Audio Generation Mode has arrows pointing out to various image icons labeled Text to Speech, Music Composition, and Sound Effects.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-AudioModel-00.svg)

As illustrated in the diagram, these outputs include:

- **Text-to-Speech:** Converting written text into realistic human-like narration for things like training videos or accessibility tools
    
- **Music Composition:** Generating royalty-free background music in various genres based on a description
    
- **Sound Effects:** Creating custom sound effects for videos or applications
    

**Code generation models** are a specialized subset of LLMs that have been specifically trained on massive repositories of public source code in addition to natural language. This dual training allows them to understand a request in plain English and translate it into syntactically correct code in languages like Python, JavaScript, or C++, enabling a range of powerful capabilities:

[![A central icon labeled Code Generation Modes has arrows pointing out to various image icons labeled Function Writing, Boilerplate Code, Code Explanation, and Resolving Bugs.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-CodeModel-00.svg "A central icon labeled Code Generation Modes has arrows pointing out to various image icons labeled Function Writing, Boilerplate Code, Code Explanation, and Resolving Bugs.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-CodeModel-00.svg)

These models work by translating a natural language request into code. Here are some examples of the **prompts** a user would provide to achieve the outcomes shown in the diagram:

![Note icon](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/Prompt-Icon.png)

## Note

- **Function Writing:** _Write a Python function that takes a list of numbers and returns the average._
    
- **Boilerplate Code:** _Generate the basic HTML structure for a webpage with a header, footer, and main content area._
    
- **Code Explanation:** _Explain what this block of SQL code is doing._
    
- **Resolving Bugs:** _Review the following JavaScript code, identify the error that is causing it to fail, and suggest a correction._
    

## Multimodality: The Convergence of Models

The lines between these model types are beginning to blur with the rise of multimodality. A multimodal AI model is one that can understand and process information from multiple types of data – or modalities – at once. For example, instead of just accepting text as input, a multimodal model could be given an image and a text prompt simultaneously.

[![A central icon labeled Audio Generation Mode has arrows pointing out to various image icons labeled Text to Speech, Music Composition, and Sound Effects.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-Multimodal-00.svg "A central icon labeled Audio Generation Mode has arrows pointing out to various image icons labeled Text to Speech, Music Composition, and Sound Effects.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-Multimodal-00.svg)

Let's look at an example of a multimodal interaction.

|   |   |
|---|---|
|The model "sees" the image and "reads" the text, then generates a textual analysis based on its understanding of the visual diagram.|   |
|[![Focal point icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/FocalPoint-Icon.png "Focal point icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/FocalPoint-Icon.png)|This ability to combine different forms of data inputs to achieve a more comprehensive understanding is a significant advancement, making AI more versatile and powerful.|

![Note icon](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/Prompt-Icon.png)

## Note

**User Input:** (Uploads an image of a network diagram) + _In a bulleted list, describe the potential points of failure in this architecture._

## Conclusion

Understanding the distinction between the underlying model and the user-facing tool is the first step to demystifying Generative AI. LLMs are text-prediction engines that excel at language tasks, while Diffusion Models are noise-reduction engines that create stunning visuals. As these technologies converge in multimodal systems, their capabilities will only expand. With this foundational knowledge, you are now equipped to explore the specific tools built upon these powerful engines.

---
# Explore Key Generative AI Tools

|   |   |
|---|---|
|[![Real world scenario icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/RealWorldScenario-Icon.svg "Real world scenario icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/RealWorldScenario-Icon.svg)|Now that you understand the core AI model types, you can begin to map out the landscape of actual tools your team might use. Your manager, Maria, isn't interested in the theoretical science; she wants to know the major, credible players and what they're used for.|

This topic provides a high-level survey of the most prominent categories of Generative AI tools, organized by the type of content they produce. The specific products mentioned serve as current examples of tools within these broader categories. The figure below illustrates the basic workflow for this category of tools, where raw information is transformed by an AI into a structured, synthesized document.

[![Information being fed to the A I, it returns a synthesized document.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/AIBIZ-C11/AIBIZ-10-11-CompetitiveAnalysis-01.svg "Information being fed to the A I, it returns a synthesized document.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/AIBIZ-C11/AIBIZ-10-11-CompetitiveAnalysis-01.svg)

## Conversational AI and Text Generation Platforms

Conversational AI and text generation is the most mature and widely used category of Generative AI. These tools work by providing a conversational interface to a powerful underlying Large Language Model, making them incredibly versatile for a wide range of professional tasks. Think of them as multipurpose assistants for anyone who works with text-based information.

Click each tab below to explore the key capabilities of these platforms and see examples of well-known tools.

- Key Capabilities
- Examples

- **Drafting and Composition:** Creating first drafts of emails, reports, project plans, and marketing copy.
    
- **Summarization and Synthesis:** Condensing long documents, articles, or meeting transcripts into key bullet points or executive summaries.
    
- **Ideation and Brainstorming:** Acting as a creative partner to generate ideas, explore different angles on a topic, or overcome creative blocks.
    

[![Person sending multiple documents into an A I and receiving the output back.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/AISynthesizing.svg "Person sending multiple documents into an A I and receiving the output back.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/AISynthesizing.svg)

|   |   |
|---|---|
Use Case in Action: From Config to Documentation
|A **Network Engineer** has just implemented a complex set of firewall rules. Manually writing the documentation to explain these rules to the security compliance team is tedious and time-consuming.|   |
|**The Workflow**|The engineer pastes the raw, anonymized configuration script into an LLM and prompts it:|
|[![Prompt icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg "Prompt icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg)|_Act as a senior network security analyst. Explain what this set of firewall rules does, who it is for, and what threats it mitigates. Format the output for an internal wiki page._|
|**The Outcome:** The AI generates a clean, well-structured first draft of the documentation in seconds, translating cryptic code into human-readable policy. The engineer's job shifts from writing from scratch to simply reviewing and refining, saving hours of work.|   |

## Text-to-Image Synthesis Platforms

This category of tools uses diffusion models to translate natural language text descriptions (prompts) into new visual media. Their primary capability is to democratize visual creation, allowing users to generate high-quality imagery without needing specialized artistic skills or software. The differentiation between tools often comes down to the aesthetic style of their output, their ability to interpret complex prompts, and how users access the service (for example, via a web app, a chat client, or integrated into a larger creative suite).

Click each tab below to explore the key capabilities of these platforms and see examples of well-known tools.

- Key Capabilities
- Examples

- **Conceptual Art and Ideation:** Quickly visualizing concepts for product designs, architectural mockups, or character sketches.
    
- **Marketing and Presentation Graphics:** Creating custom images for slide decks, websites, and social media that are more specific than generic stock photos.
    
- **Design Element Generation:** Producing logos, icons, textures, and other graphical assets.
    

[![Person sending a document into an A I and receiving the output back.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/EvaluationgCredibilityDoc.svg "Person sending a document into an A I and receiving the output back.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/EvaluationgCredibilityDoc.svg)

|   |   |
|---|---|
Try It Yourself: Write an Image Prompt
|[![Do it yourself icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/DoItYourself-Icon.png "Do it yourself icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/DoItYourself-Icon.png)|Think about the last presentation you gave. What is one slide that would have been better with a custom image instead of a stock photo? In your notes, write the text prompt you would use to generate that perfect image. Be descriptive about the subject, style, and color. For example:|

![Note icon](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/Prompt-Icon.png)

## Note

_A clean, corporate-style icon of a secure data network, using blue and green colors._

## Integrated AI Code Assistants

While general-purpose conversational AIs are highly capable at coding tasks, this specialized category of tools focuses on integrating AI directly into a developer's Integrated Development Environment (IDE). The core capability is to act as a real-time "pair programmer," augmenting the developer's workflow without requiring them to switch contexts.

Click each tab below to explore the key capabilities of these platforms and see examples of well-known tools.

- Key Capabilities
- Examples

- **Intelligent Code Completion:** Suggesting entire lines or blocks of code as a developer types
    
- **Boilerplate Reduction:** Automating the creation of repetitive or standard code structures, such as functions, classes, and unit tests
    
- **In-context Debugging:** Offering explanations for error messages and suggesting potential fixes directly within the code editor
    

[![Person sending code prompts into an A I and receiving the output back.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/AIIdentifyConnections.svg "Person sending code prompts into an A I and receiving the output back.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/AIIdentifyConnections.svg)

|   |   |
|---|---|
Use Case in Action: Automating a SysAdmin Script
|A **Systems Administrator** needs to write a PowerShell script to automate a repetitive but critical task. They know the logical steps but are unsure of the exact syntax. Working in their code editor with an AI assistant enabled, the admin writes a comment:|   |
|[![Prompt icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg "Prompt icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg)|_// Function to disable user in Active Directory and archive home folder_|
|The AI immediately suggests the complete, syntactically correct PowerShell function to accomplish this, saving the admin from having to look up the specific commands.|   |

## Synthetic Media Generation Platforms

This rapidly evolving category focuses on creating audio and video content. The core capability involves using AI models trained on vast datasets of voice, music, and video to generate new media from text or other inputs. These tools are particularly powerful for creating scalable and customizable content without the traditional overhead of recording studios or video shoots.

Click each tab below to explore the key capabilities of these platforms and see examples of well-known tools.

- Key Capabilities
- Examples

- **Realistic Text-to-Speech:** Generating high-quality, human-like voiceovers for training materials, accessibility features, or product demos
    
- **AI-Avatar Video Creation:** Producing videos where a realistic digital avatar speaks a provided script, useful for corporate communications and instructional content
    
- **Music and Sound Generation:** Creating royalty-free background music or sound effects based on a descriptive prompt
    

[![Person sending various queries into an A I and receiving the output back.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/PersonCommunicationwithAI.svg "Person sending various queries into an A I and receiving the output back.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/PersonCommunicationwithAI.svg)

|   |   |
|---|---|
Use Case in Action: Creating a System Downtime Announcement
|[![A person holding a document in one hand and with the other gesturing representing speaking.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/CFO.svg "A person holding a document in one hand and with the other gesturing representing speaking.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/CFO.svg)|The **IT Communications Lead** needs to create a brief video to announce a planned weekend system maintenance window. Instead of coordinating a live-action video shoot, they type the announcement script into an AI video platform. They choose a professional AI avatar and a realistic text-to-speech voice. Within 30 minutes, they have a professional, ready-to-distribute video announcement.|

## Conclusion

Understanding the landscape of AI tools is best achieved by focusing on their core capabilities first. By grouping tools into categories – conversational text platforms, image synthesizers, integrated code assistants, and synthetic media generators – you can effectively map a business need to the right class of tool. Knowing the specific product names is useful for evaluation, but understanding the fundamental function of each category is what allows you to build a durable and adaptable AI strategy for your organization.

---
# Generative AI Tool Capabilities and Limitations

|   |   |
|---|---|
|[![Real world scenario icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/RealWorldScenario-Icon.svg "Real world scenario icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/RealWorldScenario-Icon.svg)|Your Director, Maria, made it clear that she needs a "clear-headed evaluation," not a sales pitch. Now that you know the major model types and tool names, the next critical step is to develop a realistic understanding of what they can and can't do. The biggest mistake a team can make is treating these tools as infallible magic boxes.|

This topic provides a balanced overview of AI tools general strengths and, more importantly, their critical limitations that demand human vigilance.

## General Strengths by Tool Category

Generative AI tools have demonstrated remarkable capabilities that can significantly augment professional workflows.

|   |   |
|---|---|
|**LLMs**|   |
|[![A I Brain and a document icons on a computer monitor labeled Text Generation.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-TextGenIcon-00.svg "A I Brain and a document icons on a computer monitor labeled Text Generation.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-TextGenIcon-00.svg)|The core strength of LLMs is speed and scale. They can produce a first draft of almost any text-based document—from a simple email to a complex report—in seconds. This is invaluable for overcoming "blank page" syndrome and creating a starting point for human refinement. They are also powerful synthesis engines, capable of reading and summarizing vast amounts of text far faster than a human could.|
|**Diffusion Models**|   |
|[![A I Brain and a camera icons on a computer monitor labeled Image Generation.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-ImageGenIcon-00.svg "A I Brain and a camera icons on a computer monitor labeled Image Generation.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-ImageGenIcon-00.svg)|The primary strength of diffusion models is ideation and accessibility. They allow anyone to visualize a concept without requiring artistic skills. This is a powerful tool for brainstorming, creating mood boards, and producing custom graphics for presentations or internal sites where stock photography feels too generic.|
|**AI Assistants**|   |
|[![A I Brain and a code snippet on a computer monitor labeled Code Generation.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-CodeGenIcon-00.svg "A I Brain and a code snippet on a computer monitor labeled Code Generation.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-CodeGenIcon-00.svg)|AI assistants excel at reducing boilerplate and cognitive load. They can automate the writing of repetitive, standard code, allowing developers to focus on the more complex logic of their application. They also act as powerful learning aids, providing instant examples and explanations of unfamiliar libraries or syntax.|

## Accuracy and Hallucination Risk

|   |   |
|---|---|
|One of the most significant limitations of Generative AI is that its output is not guaranteed to be factually accurate. Because LLMs work by predicting the next most likely word, they can sometimes generate text that sounds plausible and authoritative yet completely incorrect. This phenomenon is often called "hallucination."|[![A I Brain surrounded by question marks representing hallucinations.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/AIBrainQuestionHallucination.svg "A I Brain surrounded by question marks representing hallucinations.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/AIBrainQuestionHallucination.svg)|

|   |
|---|
Ineffective vs. Effective Comparison: Verifying a Technical Fact
|Click each tab below to understand the difference between an ineffective and an effective approach.|

- Ineffective Approach
- Effective Approach

A network administrator asks an LLM, "What is the default administrative distance for EIGRP?" The LLM confidently responds, "The default administrative distance for EIGRP is 90 for internal routes and 170 for external routes." The administrator accepts this and includes it in a network design document.

## Potential Bias in AI Outputs

AI models are trained on data created by humans, and that data contains the full spectrum of human biases. Consequently, the models can inadvertently learn and replicate these biases in their outputs. This can manifest in various ways, from reinforcing stereotypes in generated text to producing images that lack diversity.

Here are some examples of how bias can manifest:

- **Stereotyping in Text:** An LLM asked to write a story about "A doctor and a nurse" might default to making the doctor male and the nurse female.
    
- **Lack of Representation in Images:** An image generator prompted with "A group of CEOs" might produce an image of predominantly white men, underrepresenting women and people of color.
    
- **Skewed Analysis:** An AI analyzing resumes might favor candidates from certain backgrounds if its training data implicitly correlated those backgrounds with success.
    

|   |   |
|---|---|
|[![Focal point icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/FocalPoint-Icon.svg "Focal point icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/FocalPoint-Icon.svg)|**Strategic Foresight:** When using AI to generate content for external audiences (like customer-facing technical documentation or public API guides), it is absolutely critical to have a human review process specifically designed to check for biased language or imagery. An unchecked AI output that contains bias can create significant brand and legal risks.|

Most large language models have a "**knowledge cut-off**" date. This means the model's training data only includes information from the internet up to a certain point in time. It has no knowledge of events, discoveries, or software releases that occurred after that date.

[![A horizontal timeline. The left end is labeled Past, and the right end is labeled Present. About two thirds of the way down the timeline there is a, label Knowledge Cut Off. The area to the left of the cut off is shaded green and labeled Models Knowledge. The area to the right of the cut off is shaded red and labeled Knowledge Gap.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/AIBIZ-C11/AIBIZ-10-11-OutdatedInformation-01.svg "A horizontal timeline. The left end is labeled Past, and the right end is labeled Present. About two thirds of the way down the timeline there is a, label Knowledge Cut Off. The area to the left of the cut off is shaded green and labeled Models Knowledge. The area to the right of the cut off is shaded red and labeled Knowledge Gap.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/AIBIZ-C11/AIBIZ-10-11-OutdatedInformation-01.svg)

|   |   |
|---|---|
|[![Tips icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Tips-Icon.svg "Tips icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Tips-Icon.svg)|While some newer tools have live web-browsing capabilities to mitigate this, it's not a universal feature, and you should never assume an AI has the most current information.|

## Prompt Quality for Reliable Business Outputs

The principle of "Garbage In, Garbage Out" is magnified with Generative AI. The quality of the output is directly proportional to the quality of the input prompt.

[![Two professionals working, and one is using a simple prompt while the other one a structured prompt.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/SimplevsStructurePrompt.svg "Two professionals working, and one is using a simple prompt while the other one a structured prompt.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/SimplevsStructurePrompt.svg)

|   |   |
|---|---|
|**Vague Prompt:** A vague, ambiguous, or lazy prompt returns a generic, high-level, and often un-actionable response.|   |
|[![Prompt icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg "Prompt icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg)|_Write a Python script._|
|**Quality Prompt:** A quality prompt provides a clear role, context, a specific objective, and formatting constraints to return a structured, relevant, and actionable response.|   |
|[![Prompt icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg "Prompt icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg)|_Act as a senior DevOps engineer. I need to write a Python script that automates a daily backup process. The script must:_<br><br>- _Connect to a remote server via SFTP._<br>    <br>- _Copy all files from the /source/logs directory._<br>    <br>- _Compress the copied files into a single .tar.gz archive named with today's date (YYYY-MM-DD)._<br>    <br>- _Store the archive in the local /backups directory._<br>    <br>    _Please include comments in the code to explain each major step._|

## Human Oversight and Critical Evaluation

This is the single most important takeaway. Generative AI is a powerful assistant, not an autonomous expert. It should be seen as a tool to augment human intelligence, not replace it.

|   |   |   |   |
|---|---|---|---|
|[![Verification icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/expanded/AITECH-10-11-HumanOversight-01.svg "Verification icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/expanded/AITECH-10-11-HumanOversight-01.svg)|[![Review icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/expanded/AITECH-10-11-HumanOversight-02.svg "Review icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/expanded/AITECH-10-11-HumanOversight-02.svg)|[![Refine icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/expanded/AITECH-10-11-HumanOversight-03.svg "Refine icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/expanded/AITECH-10-11-HumanOversight-03.svg)|[![Secure icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/expanded/AITECH-10-11-HumanOversight-04.svg "Secure icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/expanded/AITECH-10-11-HumanOversight-04.svg)|
|Never trust an AI-generated fact, statistic, or technical specification without checking it against a primary source.|Read every line of AI-generated text or code. Do not blindly copy and paste. The AI can make subtle but critical errors.|Treat the AI's output as a first draft. Use your own expertise to correct, refine, and add nuance.|Never input sensitive, proprietary, or personally identifiable information into a public AI tool.|

Most public AI providers use user-submitted prompts to further train and improve their models. This means any proprietary data you input could potentially be stored, analyzed, and even exposed to other users in future outputs.

## Conclusion

A realistic assessment of Generative AI acknowledges its profound strengths in speed and ideation while respecting its critical limitations. The technology is prone to factual errors (hallucinations), can reflect societal biases from its training data, and may operate on outdated information. Therefore, reliable and responsible use is impossible without consistent human oversight. By treating AI as a highly capable but fallible junior partner, you can harness its power while mitigating its risks.

---
# Practical Generative AI Use Cases and Workflows

|   |   |
|---|---|
|[![Real world scenario icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/RealWorldScenario-Icon.svg "Real world scenario icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/RealWorldScenario-Icon.svg)|You've explored the models, the tools, and the critical limitations. Now it's time to connect it all back to Maria's core request: finding realistic, low-risk ways to improve productivity. The true value of Generative AI in a business context isn't just about generating novel content; it's about strategically integrating it into existing workflows to make them faster, more efficient, and more effective.|

This topic showcases concrete use cases across various professional roles, providing you with a menu of practical ideas to include in your presentation.

## Use Cases in Customer and User Support

This is one of the highest-impact areas for GenAI. Support teams are constantly managing large volumes of text-based communication and knowledge base articles.

[![A user working with A I on their computer.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/PersonCompTalktoAI.svg "A user working with A I on their computer.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/PersonCompTalktoAI.svg)

Click each tab to explore the use case.

- For the Support Agent
- For the System Administrator
- Workflow Enhancement

AI can analyze incoming customer queries, determine the issue's topic and urgency, and automatically route it to the correct support tier or agent. Before the agent even opens the ticket, the AI can provide a concise summary of the entire customer interaction history, saving valuable time.

## Use Cases in Content Creation and Automation

This is the most direct application of Generative AI, streamlining tasks for anyone who needs to write or create.

[![Three professionals labeled project manager, network engineer, and marketing team working with an A I.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-UseCasesContent-00.svg "Three professionals labeled project manager, network engineer, and marketing team working with an A I.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-UseCasesContent-00.svg)

Click each card to see how Generative AI can be applied to streamline tasks for different professional roles.

- Project Manager
- Network Engineer
- Marketing Team

Generating a first draft of a project charter, creating a list of potential risks for a new project, or drafting status update emails to stakeholders.

## Use Cases in Research and Competitive Analysis

Generative AI excels at synthesizing information, making it a powerful research assistant.

[![Two professionals labeled business analyst and technical lead working with an A I.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-UseCasesResearch-00.svg "Two professionals labeled business analyst and technical lead working with an A I.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-UseCasesResearch-00.svg)

Click each card to see how Generative AI can synthesizing information for different professional roles.

- Business Analyst
- Technical Lead

|   |   |
|---|---|
|Analyzing customer feedback by feeding hundreds of reviews into an LLM and asking it to:|   |
|[![Prompt icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/Prompt-Icon.svg "Prompt icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/Prompt-Icon.svg)|_Identify the top five recurring themes or complaints from this customer feedback._|

## Streamline Planning and Communication

AI can help structure thoughts and streamline the daily communication that keeps projects moving. Here are a few examples:

|   |   |
|---|---|
|[![Prompt icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg "Prompt icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Prompt-Icon.svg)|- **For Technical Project Managers:** After a sprint planning meeting, a TPM can take their raw notes (or a transcript) and use an AI to: _Organize these notes into a structured summary. Identify each user story discussed, list the key acceptance criteria, and assign action items to the engineers mentioned._<br>    <br>- **For System Administrators:** A sysadmin can use an AI to **draft a clear, user-friendly announcement for a planned system maintenance window**, ensuring all key details like downtime, impact, and contact information are included.<br>    <br>- **For Development Team Leads:** Before a code review session, a dev lead can provide the AI with a link to a specific merge request and ask it to: _Summarize the key changes in this code, identify potential areas for bugs or performance issues, and generate a list of questions to guide the code review discussion._|

## Simple Workflow Examples

A workflow is more than a single task; it involves a sequence of steps. Here are two simple examples of integrating AI into a multi-step process.

[![Two professionals labeled Support agent and system administrator working with an A I creating a workflow.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-UseCasesCustomer-00.svg "Two professionals labeled Support agent and system administrator working with an A I creating a workflow.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Artificial%20Intelligence/Modular/AITECH/v1.0/AITECH_C11/AITECH-10-11-UseCasesCustomer-00.svg)

Click each tab below to explore two simple examples of how AI can be integrated into a multi-step process.

- Project Kick-Off Workflow
- Blog Post Creation Workflow

1. (Human): A Project Manager writes a 3-paragraph project brief.
    
2. (AI): The PM inputs the brief into an LLM with the prompt: _Based on this brief, generate a detailed project task list, grouped by project phase._
    
3. (Human): The PM reviews, edits, and imports the AI-generated task list into their project management software.
    

## Conclusion

The most practical entry points for Generative AI in the enterprise are focus on targeted augmentation rather than full automation. By identifying high-friction, text-heavy tasks within existing workflows – such as summarizing, drafting, and documenting—teams can achieve significant efficiency gains with minimal risk. These use cases, which span roles from customer support to network engineering, provide the kind of tangible, low-risk starting points that will form the core of your recommendation to leadership.

---
# First Interactions with Generative AI Tools

## Mission Briefing

|   |   |
|---|---|
|[![Real world scenario icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/RealWorldScenario-Icon.png "Real world scenario icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/Learning%20at%20Cisco/Premium%20Certification%20Content/Networking/AISKILL/v1.0/Graphics/Generic/RealWorldScenario-Icon.png)|Maria was clear: she needs a practical, grounded assessment, not theoretical hype. Your presentation to leadership must be based on firsthand experience. Your mission is to get your hands on the technology and directly observe its behavior, strengths, and quirks.|

You will interact with two of the most common types of AI tools – an LLM chatbot and an image generator – to complete a series of foundational tasks. Your findings from this lab will provide the concrete examples and talking points you need to make your final presentation credible and compelling. It's time to move from reading about AI to actually using it.

|   |   |
|---|---|
|[![Practice lab icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/PracticeLab-Icon.svg "Practice lab icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/PracticeLab-Icon.svg)|You can complete this lab activity using any Large Language Model (LLM) of your choice.|
|You may need to create an account and log in to your selected LLM chatbot platform in order to complete this lab exercise.|

## Ask an LLM Chatbot for Factual Information

The goal is to evaluate the chatbot's ability to retrieve and present specific, verifiable information.

### Step 1

Access a general-purpose LLM chatbot. For this first lab, it is important to use a major, credible tool. If you do not already have one you use regularly, we recommend one of the following:

- Google Gemini (gemini.google.com)
    
- OpenAI's ChatGPT (chat.openai.com)
    
- Anthropic's Claude (claude.ai)
    

### Step 2

Show Me

Craft a prompt that asks the AI for a factual, technical comparison. A successful prompt will be specific and include a formatting request.

Your prompt must ask the AI to:

- Define the primary differences between the Transmission Control Protocol (TCP) and the User Datagram Protocol (UDP).
    
- Instruct the AI to present the answer specifically **in a markdown table**.
    

## Note

**Success Criterion:** The AI generates a response that includes a table comparing TCP and UDP.

### Step 3

Execute your prompt and review the generated table. Now, practice the critical skill of human verification.

- Choose at least two facts from the AI's response.
    
- Independently verify them using a trusted source, such as an Internet Engineering Task Force (IETF) Request for Comments (RFC) document or other official technical documentation. Note any discrepancies.
    

## Note

**Success Criterion:** You have confirmed whether the AI's factual claims are accurate. Note any discrepancies.

### Step 4

**Optional Step:** Try asking the same question to two different LLM chatbots and compare their answers. Are they identical?

## Note

This is a great way to see LLM model differences in action.

## Request Creative Text from an LLM Chatbot

This task demonstrates the model's ability to generate stylized, non-factual content and adhere to specific formatting instructions.

### Step 5

Show Me

In the chatbot interface you used initially, craft a prompt that asks the AI to generate a **brief** professional email. This tests its ability to adopt a persona and a specific tone.

Your prompt must instruct the AI to:

- Act as a specific **persona** (a project manager).
    
- Include specific **key information** (a server migration project was successful, on time, and under budget).
    
- Adopt a specific **tone** (professional but celebratory).
    

## Note

**Success Criterion:** The AI generates an email that follows all the instructions in the prompt, including the persona, key information points, and specified tone.

### Step 6

Analyze the response and evaluate it with the following criteria:

- Did it follow all instructions (persona, key information, length)?
    
- Is the tone appropriate for the context (an internal newsletter)?
    

## Generate an Image from a Simple Descriptive Prompt

Now, you will interact with a text-to-image generator to understand the basic process of creating visual content from a prompt.

### Step 7

Access a text-to-image generation tool (such as those available in Microsoft Copilot, Gemini, or a standalone tool like Midjourney).

### Step 8

Show Me

Craft a prompt to generate a conceptual, abstract image suitable for a corporate presentation.

Your prompt should describe four key elements:

- **Subject:** What the image is about (data flowing through a secure network).
    
- **Style:** The overall artistic feel (abstract, minimalist digital art).
    
- **Color Palette:** The desired colors (cool colors like blue and green).
    
- **Mood/Context:** The intended use (clean and corporate).
    

## Note

**Success Criterion:** The tool generates one or more images that attempt to visualize the concepts described in the prompt.

|   |   |
|---|---|
|[![Tips icon.](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Tips-Icon.svg "Tips icon.")](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Tips-Icon.svg)|Note how the AI interprets subjective words like "minimalist" and "clean." This is where the art of prompting comes into play.|

### Step 9

Observe the generated image and evaluate it with the following criteria:

- How well did the tool interpret all the elements of your prompt?
    
- Are there any strange artifacts or unrealistic details?
    

### Step 10

**Optional Step:** Try regenerating the same prompt multiple times.

The response demonstrates the "generative" nature of the tool and is a good strategy if you don't like the first result.

## Note

Most tools will produce a different image each time.

## Compare Outputs Based on Slight Prompt Variations

This crucial task will highlight how small changes in a prompt can lead to significant differences in the AI's output.

### Step 11

Show Me

In your image generation tool, modify your previous image prompt to create a completely different artistic style. A good refinement adds more specific details and changes the mood.

Your new prompt should change the style from "abstract" to "photorealistic" and from "clean" to "cinematic and dramatic." Be sure to add more descriptive details to help the AI achieve this new style (for example, "glowing light trails inside glass tubes").

## Note

**Success Criterion:** The tool generates a new set of images based on the modified prompt.

### Step 12

Compare the new images to the ones generated in **Generate an Image from a Simple Descriptive Prompt** task. Note the differences in style, composition, and overall mood.

## Note

**Success Criterion:** You have a clear before-and-after comparison showing the impact of prompt specificity on the output.

## Challenge: Feedback from a Design Lead

|   |   |
|---|---|
|**Design Lead**||
|[![](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/PersonHalf-01-R.svg)](https://ondemandelearning.cisco.com/apollo-alpha/ai-tech-genaiecosystem-10/assets/BrandingAssets/CustomNoteIcons/Illustrations/PersonHalf-01-R.svg)|"_The first image was too generic. The second is more visually interesting but might be too intense for a corporate slide deck."_|
||How would you write a prompt to find a middle ground between 'clean corporate' and 'cinematic'?|

## Reflect on Tool Capabilities and Ease of Use

Now it's time to synthesize your observations into the key insights you will include in your presentation to Maria.

### Step 13

Consider your answers to the following key reflection questions. These will become the core talking points for your final report.

- How easy was it to get a useful result from each tool?
    
- Why was the verification step in Ask an "LLM Chatbot for Factual Information" task so important?
    
- How would you describe the quality of the AI's "first draft" for the creative tasks?
    
- What was the most surprising or unexpected thing you observed during your hands-on work?
    

## Conclusion

You have successfully moved from theoretical knowledge to practical, firsthand experience. By directly observing the core behaviors of LLMs and Image Generation tools, you have practiced the non-negotiable skill of human verification and experienced the critical relationship between prompt quality and output quality.

You now have the credible, experience-based insights needed to answer your Director's questions. You are no longer just relaying what you've read about AI; you are reporting what you have seen for yourself, prepared to deliver the practical, grounded assessment she requested.