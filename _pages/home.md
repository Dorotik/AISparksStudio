---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#000000"
  overlay_image: /assets/images/splash-page-main.webp
  actions:
    - label: "<i class='fas fa-download'></i> Free download"
      url: "/download/"
excerpt: 'User interface that allows you to have<br/>full control over discussions with your AI.<br/>'
intro: 
  - excerpt: "**Use your own API access** to state&#8209;of&#8209;the&#8209;art AI models efficiently with this user interface. For example, you can have discussions with **OpenAI's GPT&#8209;4**, have your speech converted to text using their capable **Whisper** model and discussion converted to lifelike speech audio using the **ElevenLabs** service."
feature_model_input:
  - title: "Know exactly what is sent to your AI"
    excerpt: > 
      Each time you hit the Generate button, your AI starts fresh by first reading the entire discussion and then generating an appropriate response. This process is **fully transparent** - nothing gets changed in you discussion so far or in the generated response. The model's context memory limitation still applies, but **you're in charge** of its management - you know exactly what's its usage, its limit, and the estimated cost of generation.

      ![test](/assets/images/test.webp)
feature_model_processing:
  - title: "Have complete control over how your AI processes the input"
    #image_path: /assets/images/test.webp
    excerpt: > 
      Have possibility to specify which large language model (LLM snapshot) shall be used for text generation and have control over every parameter the API provides. Have more control over the parameters that by using OpenAI Playground, as this UI exactly adheres to the official API specification.


      ![test](/assets/images/test2.webp)
feature_model_output:
  - title: "Know the details of a performed processing"
    excerpt: > 
      Have possibility to inspect how each part of the discussion was created, which LLM snapshot was used for its generation and what were the parameter values. Also, have means to inspect the impact on the model's context memory and cost estimation of the text generation.


      ![test](/assets/images/test3.webp)      
feature_discussion_branching:
  - title: "Feel free to experiment with your AI using discussion branching"
    excerpt: > 
      AI Sparks Studio makes it easy to branch out a discussion from an arbitrary point. This allows to **conveniently experiment how a different AI model responds or how different settings affect its output** or to rewrite the discussion without losing any previous texts. Also, this allows to partly **circumvent context memory limitation** of an AI model by branching out the discussion from its earlier relevant point. In AI Sparks Studio, it's **easy to notice, inspect, and navigate through any existing discussion branching.**


      ![test](/assets/images/test4.webp)          
feature_results_storage:
  - title: "Know that your data is safe"
    excerpt: > 
      All discussion files are stored **exclusively locally on your machine**. AI Sparks Studio makes it easy to locate these files and to change the storage location. 
      
      
      By design, nothing could get lost - the files are updated additively, so **no text could get deleted or corrupted**. Also, the files use the standard JSON format and are easy to inspect with any text editor. 
      
      
      **AI Sparks Studio communicates exclusively and directly with AI services for which you provide API keys**, on your demand. It sends a request to the AI service which you have previously authorized, receives a response and stores it locally on your machine. **The configured API keys are also stored exclusively locally on your machine**, in the application's configuration JSON file, made easy to locate using the Settings dialog.
feature_elevenlabs_details:
  - title: "Keep track of your ElevenLabs service usage"
    excerpt: > 
      Easily inspect how many characters a text&#8209;to&#8209;speech generation **would take up from your monthly quota before issuing the request**. Prevent unnecessary re-generation with the **automatic speech audio caching** (generated audio files are stored locally next to their respective discussion file).


      ![test](/assets/images/test5.webp)         
give_feedback:
  - title: "Feel free to give feedback"
    excerpt: > 
      This application is a solo developer passion project. Thus it lacks extensive testing and features that perhaps many people would find essential. Any feedback is welcome at <span id="email"></span>
    btn_label : "Download AI Sparks Studio"
    btn_class: "btn--success"
    url: "/download/"    
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