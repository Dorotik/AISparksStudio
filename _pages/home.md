---
title_hero: "AI Sparks Studio"
layout: splash
description: "AI Sparks Studio is a user interface for state-of-the-art AI models. Engage in expert discussions with AI models like OpenAI's ChatGPT or GPT-4, convert speech to text using the Whisper model, and transform discussions into lifelike speech audio with the ElevenLabs service."
permalink: /
hidden: true
header:
  overlay_color: "#000000"
  overlay_image: /assets/images/splash-page-main.webp
  actions:
    - label: "<i class='fas fa-download'></i> Free Download"
      url: "/download-ai-sparks-studio/"
excerpt: 'Experience full control over discussions with your AI.'
intro: 
  - excerpt: "AI Sparks Studio is **a user interface** that allows you to **efficiently utilize your own API access** to state&#8209;of&#8209;the&#8209;art AI models like GPT-4 or ChatGPT - a polished alternative to OpenAI Playground.<br/><br/>Engage in expert discussions with AI models like **OpenAI's GPT&#8209;4 or ChatGPT**, have your speech converted to text using the capable **Whisper** model, and transform discussions into lifelike speech audio with the **ElevenLabs** service.<br/><br/>"
feature_model_input:
  - title: "Maintain full control and transparency over your AI interactions"
    excerpt: > 
      With AI Sparks Studio, **you have full control** over your AI interactions. Every time you hit the Generate button, the AI reads the entire discussion and generates an appropriate response. This process is **fully transparent** - your discussion and the generated response remain unchanged. **You're in charge** of managing the model's context memory limitation, with clear insight into its usage, limit, and the estimated cost of generation.

      ![AI Sparks Studio in action, demonstrating expert-level AI discussion](/assets/images/ExampleDiscussion.webp)
feature_model_processing:
  - title: "Customize how your AI processes input"
    excerpt: > 
      Specify which large language model (LLM snapshot) to use for text generation and control every parameter the API provides. Gain more control over the parameters than with OpenAI Playground, as this UI adheres strictly to the official API specification.


      ![Overview of the various AI configuration options available in the application's settings](/assets/images/SettingsOverview.webp)
feature_model_output:
  - title: "Understand the Details of AI Processing"
    excerpt: > 
      AI Sparks Studio lets you inspect how each part of the discussion was created, the LLM snapshot used, and the parameter values. You can also assess the impact on the model's context memory and the estimated cost of text generation.


      ![Example of navigating to a specific message in a discussion, invoking a UI panel of message-related functionalities, and showing the message details dialog.](/assets/images/MessageDetailsExample.webp)      
feature_discussion_branching:
  - title: "Experiment Freely with AI Using Discussion Branching"
    excerpt: > 
      Branch out a discussion from any point to **experiment with different AI models or settings**. Rewrite the discussion without losing previous texts and **partially circumvent the context memory limitation** of an AI model. It's easy to notice, inspect, and navigate through any existing discussion branching.


      ![Example of discussion branching in AI Sparks Studio](/assets/images/DiscussionBranchingExample.webp)          
feature_results_storage:
  - title: "Secure Data with Local Storage"
    excerpt: > 
      All discussion files are **stored exclusively on your machine**. AI Sparks Studio makes it easy to find these files and change the storage location.


      By design, nothing can get lost - the files are updated in an additive manner, ensuring that **no text can be deleted or corrupted**. Furthermore, the files use the standard JSON format, making them easy to inspect with any text editor. 


      **AI Sparks Studio communicates directly and exclusively with AI services for which API keys are provided**, upon request. It sends a request to the pre-authorized AI service, receives a response, and stores it locally on your machine. **The configured API keys are also stored exclusively on your machine**, within the application’s configuration JSON file, easily located via the Settings dialog.
feature_elevenlabs_details:
  - title: "Monitor Your ElevenLabs Service Usage"
    excerpt: > 
      **Know how many characters a text&#8209;to&#8209;speech generation will use from your ElevenLabs monthly quota before issuing the request**. Avoid unnecessary regeneration with automatic speech audio caching. The generated audio files are stored locally in a folder adjacent to their respective discussion file.


      ![Example of navigating to a specific message in a discussion, invoking a UI panel of message-related functionalities, and showing the text-to-speech details.](/assets/images/TTS_tooltip_example.webp)        
give_feedback:
  - title: "Your Feedback is Welcome"
    excerpt: > 
      AI Sparks Studio is a passion project by a solo developer. As such, it might lack certain features or extensive testing. Your feedback is always welcome at <span id="email"></span>
    btn_label : "Download AI Sparks Studio"
    btn_class: "btn--success"
    url: "/download-ai-sparks-studio/"    
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_model_input" type="center" %}

{% include feature_row id="feature_model_processing" type="center" %}

{% include feature_row id="feature_model_output" type="center" %}

{% include feature_row id="feature_discussion_branching" type="center" %}

{% include feature_row id="feature_results_storage" type="center" %}

{% include feature_row id="feature_elevenlabs_details" type="center" %}

{% include feature_row id="give_feedback" type="center" %}

<script>
window.onload = function() {
    var user = 'ai';
    var domain = 'aisparksstudio';
    var element = document.getElementById('email');
    element.innerHTML = '<a href="mailto:' + user + '@' + domain + '.com">' + user + '@' + domain + '.com</a>';
};
</script>