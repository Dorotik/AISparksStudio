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

<sup>**Supported Operating Systems:** Windows 10 (64-bit), Windows 11 - [Installation Tips](#installation-tips)</sup><br>
<sup>**Release Date:** June 10, 2024 - [Release Notes](#ai-sparks-studio-15---release-notes)</sup><br>
<sup>**Version:** 1.5</sup><br>

## About AI Sparks Studio

AI Sparks Studio is a **completely free** desktop application designed to provide users with a seamless interface for interacting with state-of-the-art AI services. This project is a labor of love by a solo developer passionate about AI and user experience. 

### Why is it Free?
This application is a passion project, created to enhance my own interactions with AI and shared freely with the community. There are no hidden costs, ads, or spyware. Your trust and feedback are my greatest rewards.

## Security and Privacy

Your security and privacy are paramount. AI Sparks Studio is designed with a strong focus on user data protection.

- **Local Storage of API Keys:** Your API keys are stored locally on your machine and are never transmitted elsewhere. The application is transparent about where these keys are stored. You can view the path to the configuration file containing your keys at any time from the application's Settings screen.
  
- **User Control Over Data:** All user data, including API keys and any content created by the user, is stored in a location under the user's control. You have full control over the security of this data.

- **Third-Party Services:** The application allows you to connect to third-party AI web services using API keys generated from your own accounts with these services. The application sends user data to these services only when you initiate a command to do so, such as by clicking a button. The application merely facilitates your interaction with these services and does not control or assume any responsibility for the content, policies, or practices of these third-party services.

- **End User License Agreement:** AI Sparks Studio comes with a clear and comprehensive End User License Agreement (EULA) that outlines your rights and responsibilities. You can view the EULA during the installation process and at any time from the application's Settings screen. [Read the EULA]({{ site.baseurl }}{% link _pages/eula-en.md %})

Please note that while AI Sparks Studio takes measures to protect your data, you are solely responsible for the security of your locally stored data and for complying with the terms and conditions of any third-party services you choose to connect with.

## Your feedback is appreciated

As a passion project by a solo developer, AI Sparks Studio may lack certain features or extensive testing. Your feedback is always welcome at <span id="email"></span>

## Explore the Upcoming Game Development Version on Steam: ##
<iframe src="https://store.steampowered.com/widget/2612210/?utm_source=homepage&utm_campaign=SteamRelease" frameborder="0" width="646" height="190"></iframe>

## Installation Tips ##
AI Sparks Studio is a free, non-monetized passion project and, as such, **does not carry an expensive signature from a certification authority**. This lack of certification may trigger warnings from the [Microsoft SmartScreen filter](https://en.wikipedia.org/wiki/Microsoft_SmartScreen) and various antivirus software. 

If you trust this application and wish to proceed with the installation but Windows blocks the process, click *More info* and then *Run anyway*, as shown in the example below:

![Example of how to bypass the Microsoft SmartScreen filter](/assets/images/SmartScreenHelp.webp)

## API Access and Trademark Notice

AI Sparks Studio is **an independently developed tool** designed to enhance your experience with cutting-edge AI technologies by providing a user-friendly interface for accessing OpenAI's and ElevenLabs' APIs. **Please note that AI Sparks Studio is not affiliated with, endorsed, or sponsored by OpenAI or ElevenLabs.** It is crafted to facilitate seamless interaction with these services, **assuming users have their own API access**. 

This project aims to empower users by simplifying the process of engaging with these powerful AI models, enhancing creativity and productivity in game development and beyond. **All trademarks, service marks, trade names, product names, and logos appearing in AI Sparks Studio are the property of their respective owners.**

## AI Sparks Studio 1.5 - Release Notes ##
**Release Date: June 10, 2024**

### Improvements
1. **Markdown Support:** Discussion notes now automatically recognize and format text using Markdown syntax, enhancing readability and text styling. This includes automatic conversion of shortcode emojis and text smileys into graphic symbols.
2. **Keyboard Navigation Enhancements:** Pressing the ESC key now closes any current screen. Additionally, when editing a discussion note, using the Page Down and Page Up keys will scroll the view to the cursor's position, ensuring the cursor is always visible.
3. **Updated API Key Instructions:** Improved the instructions shown to users who attempt to start text generation without a configured OpenAI API key, or text-to-speech generation without a configured ElevenLabs API key. The instructions provide clear guidance on how to obtain the necessary keys using their respective accounts.

### Changes
1. **API Key Validation Feedback:** The app now specifically reports issues with OpenAI API keys that do not start with 'sk-', replacing the previous generic error message.

### Fixes
1. **Hotkey Handling with Dialogs:** Fixed an issue where discussion note operations could be triggered using hotkeys even when a dialog window was open.
2. **Discussion Note Panel Glitch:** Resolved a graphical glitch where the discussion note floating panel displayed with incorrect sizing momentarily after initiating a text generation.

<br>

## AI Sparks Studio 1.4 - Release Notes ##
**Release Date: May 16, 2024**

### Improvements
1. **Added support for the new OpenAI models:** GPT-4o 'Omni' (gpt-4o-2024-05-13) and GPT-4 Turbo (gpt-4-turbo-2024-04-09).
2. **Introduced a dark theme:** Users can now switch to a dark user interface theme.
3. **Enhanced emoji support:** Extensive emoji support is now available through the implicit use of the Noto Emoji font.
4. **Optimized font rendering:** Improved performance and quality of font rendering.
5. **Boosted scrolling performance:** Significant performance improvements during scrolling, especially noticeable in longer discussions. This update is also energy-efficient, benefiting users on battery-powered devices.

### Changes
1. **Removed character limit:** There is no longer a maximum character limit for a single discussion note.
2. **Unified model information:** Extra information about OpenAI models has been simplified and unified in the models list.

### Fixes
1. **Text control character handling:** Prevented text control characters from being interpreted incorrectly, ensuring they do not inadvertently affect displayed texts.
2. **Text-to-speech model filtering:** Resolved the text-to-speech unsupported model error by filtering the ElevenLabs models list to show only models that support text-to-speech.

<br>

## AI Sparks Studio 1.3 - Release Notes ##
**Release Date: February 16, 2024**

### Improvements
1. Added support for the new OpenAI models: gpt-3.5-turbo-0125, gpt-4-0125-preview, and the model name alias gpt-4-turbo-preview.
2. Added support for the Seed parameter in OpenAI text generation.

### Changes
1. Changed the gpt-3.5-turbo model name alias to automatically switch to the gpt-3.5-turbo-0125 model pricing on 02/16/2024.
2. Improved the sorting of the list of OpenAI models.
3. Switched the positions of the 'Generate a new note' button and the 'Create a new note' button to prevent accidental text generation when attempting to use the 'Browse notes…' button.
4. Ensured automatic scrolling to the beginning of the text of a note opened from the 'Browse notes…' selection screen.

### Fixes
1. Prevented the implicit creation and saving of a new named discussion during the removal of a named discussion.
2. Prevented the display of an exception window when a gaming device (a gamepad or joystick) gets disconnected.
3. Prevented text from overlapping their respective window areas (e.g., the Note details window) when the user interface is greatly magnified.
4. Prevented the brief, invalid display of the 'Play this note' button immediately after the start of text generation.
5. Prevented the display of the 'Generate a new note' button for an Assistant note that is the first in a discussion, aligning with the application's limitation of not starting text generation in an empty discussion.

<br>

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
4. Corrected the calculation of chat completion tokens for the new GPT-3.5 models (0613 and above, including 16k), allowing for slightly more tokens to be used before reaching the context size limit of a model.


<script>
window.onload = function() {
    var user = 'ai';
    var domain = 'aisparksstudio';
    var element = document.getElementById('email');
    element.innerHTML = '<a href="mailto:' + user + '@' + domain + '.com">' + user + '@' + domain + '.com</a>';
};
</script>