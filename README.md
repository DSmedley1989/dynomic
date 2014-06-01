dynomic
=======

Web application for collaborative creation and display of dynamic digital comic strips

##General Overview

Dynomic is intended to be an open-source framework for community-based collaborative planning, creation and viewing of dynamic interlinked web-based comic strips.

The key features are as follows:

###Character-focused Multi-threaded narrative

 - **Characters** exist as their own elements, with their own **story** comprising an ordered list of **panels** that contain them.
 - Comic panels are linked to the character elements they contain.
 - Character stories can come together (coverge) and split apart (diverge). When converged they share panels.
 - When two characters diverge the reader can select which character's story to follow.
 - Non-linear branching narrative allows for more exploration and development of a world. The reader can choose which path they take through the story.
 - Character focus means the reader can follow a character they like or switch to a new or different character.
 - Possibility of dynamic text? Displayed text could be different depending on who the **viewpoint** character is. (Advanced feature)

###Dynamic modular comic display format

 - **Panel Spaces** exist as square tiles on the dynamic page.
 - **Pages** are grids of panel spaces in various formats, 1x1, 1x2, 2x3, 3x3 etc.
 - **Panels** Are elements of artwork and/or text that can take up a certain number of panel spaces, 1, 1x2, 2x1 etc.
 - When a page is viewed, a number of panels for the focus character are loaded and arranged on the page.

###Collaborative planning and creation of panels

 - Plan for a two-layer structure:
    1: **Viewing Layer** - Where published panels can be seen and navigated by viewers.
    2: **Building Layer** - Existing under the viewing layer, members of a **project** can create and edit story board-style sketches, descriptions and example dialogue, upload a final panel image, define linkages and then publish.
 - Multiple users working together on projects, plan panels in advance, add notes, then upload final panel images and publish finished panels.
 - Add new panels as and when they are completed, or set up a batch. Possibly add ability to publish a panel at a set time.

###Cross-overs, team-ups and spin-offs

 - Plan to allow different creators to request and organise cross-overs between characters
 - Allow creators to set a point of divergeance, take an interesting minor character and create their own story in tandem with an existing narrative or in an entirely new direction.
