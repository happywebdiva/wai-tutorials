---
title: Images Concepts
tutorial_title: Images
status: draft
order: 1
topic_order: 1
type: intro
---

Every image needs to have a *text alternative* that provides an equivalent alternative by describing the information or function represented in the image. The reason for this is [explained below](#why-is-this-important). The following tutorial pages show you how to provide appropriate text alternatives based on the purpose of the image:

-   **[Informative images](informative.html)** used to graphically illustrate concepts and information, typically pictures and illustrations: The text alternative needs to be at least a short description conveying the essential information presented by the image.

-   **[Decorative images](decorative.html)** used to add visual interest to the page, rather than to convey information that is important to understanding the text: The text alternative should be null (`alt=""`).

-   **[Functional images](functional.html)** used alone as a link or button to activate a function - for example, icons for printing and submitting forms: The text alternative needs to describe the function rather than the visual image.

-   **[Images of text](textual.html)** that provide readable text (sometimes used when special fonts are wanted): This is discouraged except for logos; however, if used, the text alternative needs to contain the same words as in the image.

-   **[Complex images](complex.html) such as graphs and diagramst** that convey data or detailed information: The alternative needs to be a full text equivalent of the data and information provided in the image.

-   **[Groups of images](groups.html)** used to convey a single piece of information: The text alternative for one item should convey the information conveyed by the entire group.

-   **[Image maps](imagemap.html)** that contain multiple clickable areas: The text alternative for the image as a whole should provide an overall context for the links, and text alternatives for the clickable areas need to describe the purpose or destination of the links.

## Why is this important?

Images are used extensively on websites and can create major barriers
when they are not made accessible. Accessible images are beneficial in
many situations such as for:

-   **People using screen readers:** The text alternative can be read aloud or rendered as Braille,
-   **People using speech input software:** Users can put the focus onto a button or linked image with a single voice command,
-   **People browsing speech-enabled websites:** The text alternative can be read aloud,
-   **Mobile web users:** Images can be turned off, especially for data-roaming,
-   **Search engine optimization:** Images become indexable by search engines.


{::nomarkdown}
<%= notes_start %>
{:/nomarkdown}

**Note:** Images are often important for communicating information and interacting with web pages. For example, for people with some types of learning disabilities, illustrations make it much easier to understand information; some people who enlarge web pages use images as cues for orientation. Removing images from websites (so called "text-only versions") makes websites less accessible for these users.

{::nomarkdown}
<%= notes_end %>
{:/nomarkdown}
