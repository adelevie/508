# 1 INTERACTIVE INTERFACE ELEMENTS

## 1.1 Keyboard Access

A. An interactive element or function cannot be accessed or activated by keyboard [21(a), B1]
B. A keyboard trap is found [21(a), B1]
C. Non-standard or alternative keyboard commands are required for access but are not documented [21(a), B1]
D. Information revealed by mouse over (TITLE) is not available to keyboard-only users (i.e., there is no equivalent screen text or visual context) [21(a), B1]
E. At any time, there is no visual indication of the current focus (loss of focus) [21(c), B2]
F. The visual focus appears on the wrong element [21(c), B2]
G. The visual focus does not remain within a modal dialog box until closed [21(c), B4]
H. The visual focus does not move to revealed content and no description of the content change is provided [31(a), 31(b), B4]
I. The tab order is not logical [31(a), 31(b), B3]

### 1.2.1 SW: All interactive elements

A. A user control does not have a descriptive and unique Name property [21(d), B16]
B. A user control has an incorrect Role and/or State [21(d), B16]
C. An interactive interface element that has multiple statuses does not indicate its current status [21(d), B6]
D. An input form (text field, checkbox, radio button, etc.) Name does not match its visual label or does not include complete instructions and cues [21(d), 21(l), B11]
E. An input form Role does not accurately reflect its function [21(d), 21(l), B11]
F. An input form State does not accurately reflect that it is selected or has focus [21(d), 21(l), B11]
G. An input text field has an incorrect Value. [21(f), 21(l), B11]

### 1.2.2 Web: Forms

A. A Web form field has no markup to associate it to its complete instructions and cues [22(n), B11]
B. If 'Label for' and 'ID' are used but are not valid HTML [22(n), B11]
C. Form instructions are revealed only by mouse over (TITLE) and are not available onscreen  [22(n), B11]
D. An ARIA form's Name property does not contain complete instructions  [22(n), B11]
E. An ARIA form's Role or State or Value property is not correct [22(n), B11]
F. A form control does not identify its purpose [22(n), B11]

### 1.2.3 Web: Links and User Controls

A. A link does not have a unique and meaningful description [31(a), 31(b), B16]
B. A scripted element does not have a unique and meaningful description  [22(l), 31(a), 31(b), B16]

# 2 NON-TEXT INTERFACE ELEMENTS

## 2.1 SW: Images

A. An image does not have an equivalent text description (Name), correct Role, or correct State [21(d), B7]
B. Any interface element that has multiple statuses does not indicate its current status [21(d), B6]
C. A data table's headers are not identified [21(d), B13]
D. A complex data table cell is not associated to its header(s) [21(d), B14]
E. An image has inconsistent meaning [21(e), B7]
## 2.2 Web: Images
A. A Web image does not have an ALT or TITLE or ARIA attribute [22(a), B7]
B. A meaningful image does not have an equivalent text description (purpose and function) [22(a), B7]
C. A decorative image does not have ALT=[22(a), B7]
D. An image that contains text does not have the same text in the ALT [22(a), B7]
E. A CAPTCHA image ALT does not describe its purpose [22(a), B7]
F. A multi-state component does not provide complete status information [31(a), 31(b), B6]
G. An image has inconsistent meaning [21(e), B7]

## 2.3 Video-only and Animation 

A. In SW, an animation does not have an equivalent text or audio description [21(h), B19]
B. In Web, a video-only file does not have an equivalent text or audio description [22(a), 24(d), B19]

## 2.4 Web: Audio-only 

A. An audio file does not have an equivalent text description/transcript [22(a), B18]

## 2.5 Web: Image Maps 

A. A server side image map is found [22(e), 22(f), B26]

# 3 COLOR AND CONTRAST

## 3.1 Color Dependence

A. In software, information is provided only by color [21(i), B8]
B. In Web, information is provided only by color [22(c), B8]

## 3.2 Color Contrast 

A. The contrast ratio is less than 4.5:1 for content background and foreground colors [31(b), B9]

# 4 FLASHING

A. The frequency of a flickering element cannot be determined programmatically [21(k), 22(j), B10]
B. B. The frequency of a flickering element is programmatically set at or above 3 Hz [21(k), 22(j), B10]

# 5 PAGE TITLES

A. There is no meaningful page title in plain language [31(a), 31(b), B12]

# 6 MULTIMEDIA

A. Synchronized captions are not provided for multimedia [22(b1), 24(c), B20]
B. The provided captions for multimedia are not equivalent [22(b1), 24(c), B20]
C. Synchronized audio descriptions are not provided for multimedia [22(b2), 24(d), B21]
D. The provided audio descriptions are not equivalent [22(b2), 24(d), B21]

# 7 TIME OUTS 

A. The application timed out without notification [22(p), B25]
B. The application's time out notification is displayed for less than 20 seconds [22(p), B25]
C. The application timed out without an option to request more time [22(p), B25]

# 8 SW: BUILT-IN ACCESSIBILITY FEATURES 

A. The application disrupted any of the OS Accessibility options (High Contrast, Sticky Keys, Sound Sentry and/or system text size (stand-alone software only)) [21(b), B28]
B. The application does not adopt the OS high contrast display settings [21(g), B28]
C. Text of application did not enlarge or became illegible when enlarged [21(g), B28]
D. The application did not adopt the OS high contrast colors, 21(g), and the application does not offer at least 4 color options [DHS-Specific: 21(j), no baseline]
E. Sticky Keys functionality was disrupted in the application [31(f), B28]
F. Sound Sentry functionality was disrupted by the application [31(c), B28]

# 9 WEB: TEXT PROPERTIES

## 9.1 Web: Language 

A. The correct default language for the page is not programmatically set [31(a), 31(b), B17]
B. A passage (content, image descriptions, form labels etc.) that differs from the default language of the page is not programmatically identified correctly [31(a), 31(b), B17]

## 9.2 Web: Section Headings

A. Visually apparent headings are not programmatically identified [31(a), 31(b), B15]
B. Programmatically identified heading levels do not match the visual outline level [31(a), 31(b), B15]

# 10 WEB: DATA TABLES

A. Any data table's row or column headers are not identified programmatically [22(g), B13]
B. An image of a data table is found [22(g), B13]
C. A complex data table's data cells are not associated with its headers programmatically [22(h), B14]
D. An image of a complex data table is found [22(h), B14]

# 11 WEB: STYLE SHEET DEPENDENCE 

A. The order of the content changed and is not logical [22(d), B22]
B. Relevant content or information from a meaningful image is not available [22(d), B22]
C. Any content overlaps or becomes illegible [22(d), B22]
D. Programming code or other confusing elements are revealed on the page [22(d), B22]

# 12 WEB: FRAMES 

A. A frame's Title or Name is non-descriptive [22(i), B23]
B. An iframe's Title or Name is non-descriptive [22(i), B23]

# 13 WEB: REPETITIVE CONTENT AND LINKS 

A. There is no method to skip repetitive content [22(o), B5]
B. The skip function's target is not located after the repetitive content [22(o), B5]
C. The skip function does not work properly [22(o), B5]
D. The relative order of repeated components is different from other pages [31(a), 31(b), B3]

# 14 WEB: REQUIRED PLUG-INS

A. In a public site, the link to download a required plug-in is not provided [22(m), B27]
B. The plug-in required to view content is not compliant [21(a)-(l) as applicable, No baseline]

# 15 WEB: ALTERNATIVE (ACCESSIBLE) VERSION 

A. An alternative page does not contain equivalent information as the primary page [22(k), B24]
B. The primary site can be made compliant [22(k), No baseline]
