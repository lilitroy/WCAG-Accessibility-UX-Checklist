# WCAG Accessibility UX Checklist 

![alt text](world_open_source_day_social_2x.png)

This Accessibility UX checklist serves as a method for designers and developers to assess the WCAG compliance of their work.
	


## UX Accessibility Checklist
WCAG 2.1 Verification – 116 Questions  |  Cumulative list

<br>

### Links Defined
*Description of each type of citation paired with checklist questions*

**Level A** = complies with this specific Level A WCAG 2.1 guideline

**Level AA** = complies with this specific Level AA WCAG 2.1 guideline

**Level AAA** = complies with this specific Level AAA WCAG 2.1 guideline

**Recommendation** = additional UX consideration inspired by various WCAG 2.1 guidelines


<br>


### 1. Perceivable 	


_Information and user interface components must be presentable to users in ways they can perceive._


#### 1.1   Text alternatives -  Provide text alternatives for any non-text content so that it can be changed into other forms people need, such as large print, braille, speech, symbols or simpler language. 

- [ ] Have we provided descriptive alt text to all functional and informative images, as well as data visualizations, so that all users can understand the content? [Level A](https://www.w3.org/WAI/WCAG21/quickref/?showtechniques=111#non-text-content)
- [ ] Have we provided descriptive alt text that accurately conveys their meaning to all functional and informative graphics, such as icons? [Level A](https://www.w3.org/WAI/WCAG21/quickref/?showtechniques=111#non-text-content)


#### 1.2   Time-based Media -  Provide alternatives for time-based media [such as video, sound, slideshows, etc.] 

- [ ] Have we provided a transcript of prerecorded audio and video recordings? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#audio-only-and-video-only-prerecorded)
- [ ] Have we provided captions and descriptions for prerecorded audio and videos? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#captions-prerecorded)
- [ ] Are live captions available for live audio and video recordings? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#captions-live)
- [ ] Have we provided audio recordings that describe the contents of all video recordings in real-time? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#audio-description-prerecorded)
- [ ] Do we have a video recording of an ASL interpreter translating our prerecorded media? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#sign-language-prerecorded)
- [ ] Have we provided an audio description of the prerecorded media that also includes implicit context that may not be understood through a language translation alone? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#extended-audio-description-prerecorded)
- [ ] Have we provided a transcript or equivalent version of live video content? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#media-alternative-prerecorded)


#### 1.3   Adaptable -  Create content that can be presented in different ways without losing the integrity and context of the content.
	

- [ ] Can we provide a simpler layout without losing information or structure? [Level A](https://www.w3.org/WAI/WCAG21/quickref/?showtechniques=111%2C128%2C133#adaptable)
- [ ] Have we included a text description of our content that conveys implicit tone and meaning, even if it is not explicitly stated within that content? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#info-and-relationships)
- [ ] Have we made the correct order of consuming our content obvious if the order of content is essential to understanding it? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#meaningful-sequence)
- [ ] Does the sequence of information as we reveal it make sense if we went through it in order? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#meaningful-sequence)
- [ ] Have we made sure to not use physical characteristics like color or location to explain how to accomplish a task? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#sensory-characteristics)
- [ ] Do we allow users to view our content in both landscape and portrait mode without distortion (unless one way or the other is essential)? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#orientation)
- [ ] Have we appropriately labeled our UI components so autofill can be used correctly? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#identify-input-purpose)
- [ ] Have we labeled input fields to communicate what information users can enter and why?  [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#identify-input-purpose)
- [ ] Does our markup match what the UI element is so that support devices can apply the user’s customized preferences? [Level AAA](https://www.w3.org/WAI/WCAG21/Understanding/identify-purpose.html)


#### 1.4   Distinguishable -  Make it easier for users to see and hear content including separating foreground from background. 


- [ ] Can users tell the difference between the foreground and background of content? [Level A](https://www.w3.org/WAI/WCAG21/quickref/?showtechniques=111%2C128%2C133#distinguishable)
- [ ] Have we made sure that color is not the only way that we convey information in our content? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#use-of-color)
- [ ] Can all normal text colors be differentiated from their background color at a **4.5:1** ratio ? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#audio-control)
- [ ] Can all large text colors be differentiated from their background color at a **3:1** ratio? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#contrast-minimum)
- [ ] Can all UI/graphic colors be differentiated from their background color at a **3:1** ratio (unless they are disabled or logos)? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#contrast-minimum)
- [ ] Do all page elements render legibly when zoomed in at **200%**? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#resize-text)
- [ ] Have we made sure not to rely on images alone to share information (unless it is essential)? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text)
- [ ] Can all normal text colors be differentiated from their background color at a **7:1** ratio? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#contrast-enhanced)
- [ ] Can all large text colors be differentiated from their background color at a **4.5:1** ratio? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#contrast-enhanced)
- [ ] Can all UI/graphic colors be differentiated from their background color at a **3:1** ratio (unless they are disabled or logos)? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#non-text-contrast)
- [ ] Can voices in audio be heard clearly and easily distinguished from background noise? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#low-or-no-background-audio)
- [ ] If we have included a block of text, have we given the user the ability to customize how they view it (color, alignment, line spacing, etc.)? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#visual-presentation)
- [ ] Have we only used images of text (without alt text) for decoration, not sharing content?  [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#images-of-text-no-exception)
- [ ] Have we made sure that a vertical scroll bar is not needed until we exceed **320px** and a horizontal scroll bar is not needed until we exceed **256px**? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#reflow)
- [ ] Can our content be viewed and understood without issues if the line height is **1.5** bigger than the font size? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#text-spacing)
- [ ] Can our content be viewed and understood without issues if the space between each line of text is at least double the font size? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#text-spacing)
- [ ] Can our content be viewed and understood without issues if the space between paragraphs is at least double the font size? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#text-spacing)
- [ ] Can our content be viewed and understood without issues if the space between letters is at least **0.12** times bigger than the font size? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#text-spacing)
- [ ] Can our content be viewed and understood without issues if the space between words is at least **0.16** times bigger than the font size? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#text-spacing)
- [ ] Are our UI components named as follows and are these states obvious to assistive devices? 

     - [ ] **Default** 
     - [ ] **Inactive** 
     - [ ] **Focus** 
     - [ ] **Disabled** 
     - [ ] **Loading** 
     - [ ] **Error** 


### 2. Operable 	


_User interface components and navigation must be operable._



#### 2.1   Keyboard Only -  Make all functionality available from a keyboard.

- [ ] Can users use a keyboard to access all content (as long as the path to get there is not important)? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#keyboard)
- [ ] Can users navigate away from focused content using only a keyboard without getting stuck? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#no-keyboard-trap)
- [ ] Can users use a keyboard to access all content no matter what? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#keyboard-no-exception)
- [ ] Do we give the user the ability to turn hotkey shortcuts on and off? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#character-key-shortcuts)
- [ ] Do keyboard hotkeys and standard shortcuts work properly within the interface? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#character-key-shortcuts)
	
#### 2.2   Enough Time -  Provide users enough time to read and use content.

- [ ] Can users adjust timing (re: slideshows, automated-scrolling, etc.) if needed? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#timing-adjustable)
- [ ] Are we giving users the ability to pause and restart automated content? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#pause-stop-hide)
- [ ] Do we give the user the ability to turn off motion animations if they start automatically? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#pause-stop-hide)
- [ ] Do we give users the ability to turn off motion animations if they last for more than **5** seconds? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#pause-stop-hide)
- [ ] Do we give users the ability to stop or pause updates that begin automatically? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#pause-stop-hide)
- [ ] Do we give users the ability to signal that they need more time before a timeout? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#timing-adjustable)
- [ ] Do we allow users to turn off timeouts unless they are necessary to security? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#timing-adjustable)
- [ ] Is timing completely irrelevant for the user to fully engage with our content? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#no-timing)
- [ ] Do we only interrupt users from what they were doing in an emergency? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#interruptions)
- [ ] Do we give the user the ability to start where they left off after reauthenticating? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#re-authenticating) 
- [ ] Do we preserve data as it was when the user is automatically logged out? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#re-authenticating)


#### 2.3   Seizures and Physical Reactions -  Do not design content in a way that is known to cause seizures or physical reactions.

- [ ] Have we made sure none of our content blinks or flashes more than **3** times per second? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#three-flashes-or-below-threshold) / [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#three-flashes)
- [ ] Have we given users the ability to turn off any animations that start as soon as they interact with them? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#animation-from-interactions)


#### 2.4   Navigable -  Provide ways to help users navigate, find content, and determine where they are.

- [ ] Can we give redundancy cues and/or structural markup that alerts users of duplicated content? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#bypass-blocks)
- [ ] Do all pages have descriptive titles that differentiate them from others within navigation? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#page-titled)
- [ ] Do all headings describe the purpose of the page? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#page-titled)
- [ ] Does the order of tabs and information presented to those using a keyboard make sense? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#focus-order)
- [ ] Do all links read as clear descriptions of where they will navigate the user? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-in-context)
- [ ] Are there multiple ways to navigate to a page within the system? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#multiple-ways)
- [ ] Do all labels clearly describe the topic or purpose of the content they are labeling? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
- [ ] Do our labels use the exact same words as the content they are describing? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#headings-and-labels)
- [ ] Is the focus indicator always available to those using a keyboard? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#focus-visible)
- [ ] Can the user verify their location within the interface (re: “sitemap” navigation)? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#location)
- [ ] Do all links reveal their purpose to the user? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-link-only)
- [ ] Do all links give additional descriptions about what the link’s content entails? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#link-purpose-link-only)
- [ ] Have we consistently used the correct order of header hierarchy throughout the interface? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#section-headings)


#### 2.5   Input Modalities -  Make it easier for users to operate functionality through various inputs beyond a keyboard.

- [ ] Have we allowed the user to move his or her mouse in whatever pattern allows him or her to accomplish a task? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#pointer-gestures)
- [ ] Have we provided an alternative to swiping and other pointer-based gestures? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#pointer-gestures)
- [ ] Have we prioritized the “release” click of the mouse for the user to take action? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#pointer-cancellation)
- [ ] Are all buttons and graphic labels named as what they are (re: “checkbox,” “notification,” etc.)? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#label-in-name)
- [ ] Have we given users the ability to adjust/turn off motion input sensing (re: shake to erase)? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#motion-actuation)
- [ ] Are our click targets at least **44px x 44px** in size? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#target-size)
- [ ] Have we enabled non-touch inputs even on devices where touch inputs are present? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#concurrent-input-mechanisms)


<br>


### 3. Understandable 


_Information and the operation of the user interface must be understandable._




#### 3.1   Readable -  Make text content readable and understandable. 


- [ ] Has a default human language been programmed into markup? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#language-of-page)
- [ ] Have we labeled what language is being used and when it changes to adjust vernacular? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#language-of-parts)
- [ ] Have we labeled jargon and idioms within our content? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#unusual-words)
- [ ] Do we offer a source that explains our abbreviations that's hosted internally or externally? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#abbreviations)
- [ ] Have we presented content at a middle school reading level? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#reading-level)
- [ ] If our content is very complex, have we provided additional supporting materials to help users understand it at a middle school reading level? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#reading-level) 
- [ ] Have we provided a mechanism to support correct pronunciation of terms not widely known? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#pronunciation)


#### 3.2   Predictable -  Make pages appear and operate in predictable ways. 
	
- [ ] Does content in a focus state remain exactly the same as when it’s in the default state? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#on-focus)
- [ ] Has the user been made aware that the interface will change when they input information prior to them doing so? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#on-input)
- [ ] Are UI page elements in a standard and consistent place within the page’s layout? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#consistent-navigation)
- [ ] Is the sequence of those UI elements repeated consistently throughout the interface? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#consistent-navigation)
- [ ] Is the page and site navigation always in the same location on each page? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#consistent-navigation)
- [ ] Are our icons used consistently in the same context across the interface? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#consistent-identification)
- [ ] Are the UI elements consistent with the behavior of standard UI elements? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#consistent-identification)
- [ ] Are we allowing the user to decide when to take action instead of automatically doing it for them? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#change-on-request)
- [ ] Do we give the user the ability to turn off all notifications until the end of the session?  [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#change-on-request)


#### 3.3   Input Assistance-  Help users avoid and correct mistakes.</h4>
	
- [ ] Do we alert users immediately with an error message as soon as an error is detected? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#error-identification)
- [ ] Have we provided more than one cue that an error has occurred? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#error-identification)
- [ ] Are all required form fields clearly indicated to the user? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#error-identification)
- [ ] Are input fields always paired with directions that help the user decide what to enter?  [Level A](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions)
- [ ] Do our alerts always include text even if colors and/or graphics are also used in the notification? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#labels-or-instructions)
- [ ] Are our error messages as short and specific as possible? (Recommendation)
- [ ] If an error is detected, have we offered a concise solution to fix the error? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#error-suggestion)
- [ ] Have we allowed users to review and correct their submissions before submitting them (especially with legal commitments and financial transactions)? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#error-prevention-legal-financial-data)
- [ ] Do we give the user the ability to immediately undo a mistake in any situation? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#error-prevention-legal-financial-data)
- [ ] Do we have a readily available system in place whenever a user needs help? [Level AAA](https://www.w3.org/WAI/WCAG21/quickref/#help)
- [ ] Have we created specific help text and options that allow the user to complete a task without losing track of where they are? (Recommendation)
- [ ] Do we allow users to change between devices when interacting with content on multiple devices during the same session? (Recommendation)


<br>


### 4. Robust 



_Content must be robust enough that it can be interpreted by a wide variety of user agents, including assistive technologies._




#### 4.1   Compatible -  Maximize compatibility with current and future user agents, including assistive technologies. 


- [ ] Does all content that uses a markup language have complete start and end tags? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#parsing)
- [ ] Does all of our markup include only one attribution (no duplicates)? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#parsing)
- [ ] Are all HTML elements correctly nested according to standard use? (Recommendation)
- [ ] Can the name and role of all UI elements be easily detected by supportive technology? [Level A](https://www.w3.org/WAI/WCAG21/quickref/#name-role-value)
- [ ] Can all of our status messages be automatically received and interpreted by supportive technology (even if they are not the user’s current focus)? [Level AA](https://www.w3.org/WAI/WCAG21/quickref/#status-messages)


