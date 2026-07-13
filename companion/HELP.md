## PresentationTools APS

Controls APS by [PresentationTools](https://presentationtools.com/).

### Requirements

- PC: APS v. 1.0.0.5 and above
- Mac: APS v.2 (0) and above
- Download latest version of APS from this website: [www.presentationtools.com/aps](https://presentationtools.com/aps)
- _Note: Still-images requires APS v.2 and above_

### Configuration

- IP address of the computer running APS for local use 127.0.0.1.
- Port, the default is 4777.

### Available actions:

#### Navigation & tabs:

- Open next presentation with fullscreen and slide number.
- Open the previous presentation with fullscreen and slide number.
- Open the next presentation without putting it in fullscreen. (deprecated)
- Put current presentation in fullscreen
- Close all except current.

#### Capture Image:

- Take screenshot of the main presenter-screen and store this in the image-banks.
- Choose between 10 destinations.

#### Display Image:

- Display image on the main presenter screen. Choose between image-bank 1-10 or test-image, blackout or freeze screen. (Note: In APS preferences you can choose if this command is a toggle-button or not)

#### Exit Images:

- Exit APS-image from the main presenter screen

#### Open/Start Presentation:

- Open presentation specified in file name with full screen and slide number

#### Generic - Go to slide:

- Go to the slide specified in the command

#### Commands to control specific presentation software:

- Powerpoint: Go to slide
- Powerpoint: Previous slide
- Powerpoint: Next slide

- Adobe Acrobat DC: Go to slide
- Adobe Acrobat DC: Previous slide
- Adobe Acrobat DC: Next slide

Mac only:

- Keynote: Go to slide
- Keynote: Previous slide
- Keynote: Next slide

#### Filenames on Companion buttons

- Display the filenames of the presentation file currently displayed, and the files that will be used with the previous and next commands.

#### Network Commands for 20 presentation from slot

- Open/Start presentation from slot

#### Variables

- Presentation_current: Currently opened presentation
- Presentation_previous: Prevously opened presentation
- Presentation_next: Next presentation to be opened
- Presentation_notes: Presenter notes for the current slide
- slide_number: Slide Number
- slides_count: Slides Count
- Slides_builds_count: Builds Count
- Powerpoint_sections_available: Whether section information is available for the active PowerPoint slideshow
- Powerpoint_sections_current_index: Current section number
- Powerpoint_sections_current_id: Current section ID
- Powerpoint_sections_current_name: Current section name
- Powerpoint_sections_current_slide_in_section: Current slide number within the section
- Powerpoint_sections_count: Total number of sections
- Powerpoint_section&lt;n&gt;_id: Section ID for section &lt;n&gt;
- Powerpoint_section&lt;n&gt;_name: Section name for section &lt;n&gt;
- Powerpoint_section&lt;n&gt;_first_slide_index: First presentation slide number for section &lt;n&gt;
- Powerpoint_section&lt;n&gt;_slides_count: Number of slides in section &lt;n&gt;

#### Feedbacks

- loaded: is enabled when a still image is loaded in the image-banks
- displayed: is enabled when a still image is displayed
- captured: is enabled when screen is captured for saving as a still image.
- slot_displayed: is enabled when the presentation in slot-bank is opened
- slot_exist: is enabled when a presentation exists for a slot.
- PowerPoint_section_exists: is enabled when the active PowerPoint presentation contains the selected section number.
- PowerPoint section is displayed: is enabled when the current slide is within the selected PowerPoint section.
