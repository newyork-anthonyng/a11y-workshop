### Curriculum/Syllabus (not part of sent proposal)
* Introduction
  * introduce ourselves
  * Class introduction. What are we talking about in class?
  * Leave that on the board, somehow
  * 5 minute breaks, every half hour
* What is web accessibility?
    * Web accessibility refers to the inclusive practice of removing barriers that prevent interaction with, or access to websites, by people with disabilities
* Talk about statistics for disabilities and whatnot
* What types of disabilities are there?
  * Temporary (broken arm), permanent (missing arm), situational (being on your phone in bright daylight)
    * temporary ??
    * permanent, no fine motor control, so you can't use a mouse, 
    * situational, having bad contrast
  * Visual, motor, hearing, cognitive
    * visual, blind, have to use screen reader
    * motor, can't use a mouse
    * hearing, deaf. closed captions or transcripts. Podcasts.
      * With transcript, https://www.youtube.com/watch?v=uyIZVNzo5KY
      * Without transcript, https://en.wikipedia.org/wiki/File:I%27ve_Been_To_The_Mountaintop.ogg
  * Show poster from here (https://accessibility.blog.gov.uk/2016/09/02/dos-and-donts-on-designing-for-accessibility/)
    * From the Accessibility Group at Home Office Digital
* Assistive technologies
  * Keyboard only, screen reader
  * Look at other AT. Like the straw thing, one button, 

# Break!

* Why should you care?
  * Lawsuits
    * https://dynomapper.com/blog/27-accessibility-testing/443-web-accessibility-lawsuits-set-to-increase-under-trump
    * https://www.adatitleiii.com/2018/01/2017-website-accessibility-lawsuit-recap-a-tough-year-for-businesses/
  * All customers benefit from more accessible websites
  * It's the right thing to do
    * Expedia wants to help people go places (https://www.youtube.com/watch?v=4PoE9tHg_P0)
* WCAG 2.0 Principles and Guidelines
  * Expedia pdf's. Look through that.
* Semantic HTML
  * Look at an inaccessible button together
  * Talk about how to make it accessible with JavaScript.
  * Look at HTMl attributes like tabindex and role
  * Talk about how using a semantic <button> tag would have saved all of this trouble
* Look at a poorly created website together
  * Show how to use ChromeVox plugin for screenreader
  * Go over automated tools, including Deque's AXE extension (https://chrome.google.com/webstore/detail/axe/lhdoppojpmngadmnindnejefpokejbdd?hl=en-US), and the Audits tab in Developer tools.
    * There are also CLI tools so you can fail your build. https://github.com/dequelabs/axe-cli
  * Go over manual testing as well
* Look at best practices
  * Mobile tap targets.
  * Skip navigation link
  * Keyboard shortcuts
  * Color contrast
  * Modal accessibility.
* Look through the WAI-ARIA best practices and create a tabs component together

What is a widget?
> an application, or a component of an interface, that enables a user to perform a function or access a service.
Websites used to be static websites. Now we have more dynamic websites; widgets are components of that.
Menu bars, sliders, etc. are examples of widgets. They resemble desktop interfaces that you are familiar with.
