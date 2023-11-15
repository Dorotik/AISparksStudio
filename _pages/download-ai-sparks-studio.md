---
permalink: /download-ai-sparks-studio/
title: "Download AI Sparks Studio - Free AI User Interface"
title_hero: "Download"
description: "Download AI Sparks Studio for free. Experience full control over discussions with your AI. Available for Windows 10 and 11."
classes: wide
layout: splash
header:
  overlay_image: /assets/images/splash-page-main.webp
---

Thank you for choosing **AI Sparks Studio**! To download the **installer**, please click the button below:

<a href="/assets/AISparksStudioSetup.exe" class="btn btn--success btn--large" onclick="window.goatcounter.count({path: 'download', title: 'Download Clicked', event: true})">
  <i class='fas fa-download'></i> AISparksStudioSetup.exe
</a>

<sup>**Supported Operating Systems:** Windows 10 (64-bit), Windows 11</sup><br>
<sup>**Release Date:** November 15, 2023 ([Release Notes](#ai-sparks-studio-12---release-notes))</sup><br>
<sup>**Version:** 1.2</sup><br>

As a passion project by a solo developer, AI Sparks Studio may lack certain features or extensive testing. Your feedback is always welcome at <span id="email"></span>

This application is **completely free, without any ads or spyware.**

AI Sparks Studio is a free, non-monetized passion project and, as such, **does not carry an expensive signature from a certification authority**. This lack of certification may trigger warnings from the [Microsoft SmartScreen filter](https://en.wikipedia.org/wiki/Microsoft_SmartScreen) and various antivirus software. 

If you trust this application and wish to proceed with the installation but Windows blocks the process, click *More info* and then *Run anyway*, as shown in the example below:

![Example of how to bypass the Microsoft SmartScreen filter](/assets/images/SmartScreenHelp.webp)

## AI Sparks Studio 1.2 - Release Notes ##
**Release Date: November 15, 2023**

### Improvements
1. Added full support for the GPT-4 Turbo 128K (gpt-4-1106-preview) and gpt-3.5-turbo-1106 models, and limited support for the GPT-4V Turbo 128K (gpt-4-vision-preview) model.
2. Implemented a feature allowing the generation of multiple notes with a single API request (Text Generation - Number of Generated Notes), optimizing costs as the input text is processed only once per request.
3. Enhanced the user interface (UI) resizing functionality by adding standard hotkeys for resizing controls, and enabling continuous size adjustment by holding the respective button/hotkey.

### Changes
1. Increased the default scale of the UI for displays with resolutions wider than 1920p, improving readability right from the start.
2. Modified text generation request creation to include the max_tokens parameter only if the Text Generation - Maximum Token Count option is set above zero.

### Fixes
1. Resolved occasional text generation communication errors with the OpenAI service.

<br>

## AI Sparks Studio 1.1 - Release Notes ##
**Release Date: October 11, 2023**

### Improvements
1. Added the ability to edit discussions. To use this feature, click on an existing discussion note and then select the new "Edit this note" option in the Actions floating panel on the right.
2. Enabled the removal of discussions via the Discussion details window. (In keeping with AI Sparks Studio's commitment to data preservation, files are not deleted but relocated to the "Removed" folder in the application's working directory).
3. Added the ability to effectively remove discussion notes. This new feature, called "Permanently hide this note", can be accessed during note editing. While the note will no longer be visible in the application interface, it will be preserved within the discussion file in line with our non-destructive approach to data handling.
4. Improved ElevenLabs audio clips caching. The current voice settings, retrieved from an ElevenLabs account, are now considered when searching for a corresponding cached audio clip. Cached audio clips also now store the Style & SpeakerBoost settings used during their creation.
5. Implemented the storage of text generation input & output token counts in discussion files.

### Changes
1. Adjusted the default OpenAI text generation temperature from 0.7 to 0.25 to facilitate higher-quality results in expert discussions.
2. Enabled text selection and context menu for dialog windows and the About section, making it easier to copy or search for any referenced links or information.
3. Altered the "Go to the concept note" action hotkey to Ctrl+O, freeing up Ctrl+E for the newly added "Edit this note" action.

### Fixes
1. Removed the display of the newly introduced OpenAI GPT Instruct models in the list of available text generation models, as they are incompatible with chat.
2. Eliminated unintentional activation of auto-scrolling upon the completion of text generation.
3. Rectified issues with auto-scrolling when set to a low speed.
4. Corrected the calculation of chat completion tokens for the new ChatGPT models (0613 and above, including 16k), allowing for slightly more tokens to be used before reaching the context size limit of a model.


<script>
window.onload = function() {
    var user = 'ai';
    var domain = 'aisparksstudio';
    var element = document.getElementById('email');
    element.innerHTML = '<a href="mailto:' + user + '@' + domain + '.com">' + user + '@' + domain + '.com</a>';
};
</script>