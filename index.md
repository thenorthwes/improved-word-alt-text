# Improved Word Alt Text

This project's goal is to develop a Word plug-in which modifies the default behavior in Microsoft word when an image is inserted such that the user is prompted with a dialog box that guides them to create alt text. The goal is to raise alt text awareness so it is not forgotten in a hidden menu; and suggest best practices so that alt text is high quality and contextually relevant to the image’s intended use.

### Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/De4jPjoHatA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Introduction– 1-3 paragraphs: Present the promise/ obstacle/ solution for your project— What is the problem you are solving and why is it important to solve it?
Missing and/or bad alternative text for images in Office documents pose a significant challenge to users with visual impairments. Adding alt text to images is usually an afterthought for most content creators and with better and more proactive tooling, content creators will be reminded and encouraged to write better alt text more frequently thereby increasing the amount of well-described images in Office documents. Initially we were focused on creating an add-in for MS PowerPoint but the PowerPoint JS API isn't as robust and so we pivoted to making an add-in which will work for MS Word.

The current approach to alt text in Office has 2 main problems we aim to solve with our plugin. Primarily the alt text UI is not proactive and it requires the user to manually search for it or manually use the accessibility checker. This is likely in favor of auto-opening the Design Ideas feature (in PPT) and to avoid annoying users, as accessibility does not have the importance and awareness for most users that it should. Another issue we aim to solve is that the alt text UI either lets the user do all the writing with minimal guidance, or generates a totally automated caption, regardless of context of document. Either the latest research around how to write good alt text just hasn’t made its way into the user interface yet, or they wanted to keep the guidance as simple as possible. We aim to improve the prompt about writing good alt text by reccomending best practices from reputable best practices we identify.

Our solution to overcome these obstacles is to build an Office add-in that users can add to their installation of Office in the web and their installed product. The add-in would work as a replacement for the existing Alt text UI.When a user adds an image to their document, the add-in would automatically open the task pane and prompt them to add alt text for the image. The add-in would guide the user to writing good alt text based on the contents and context of the image, using category-based guidance (people, chart/figure, landscape, etc.). The user can expand their chosen category and read detailed guidance in the pane. This will improve upon the current experience, which provides static guidance for every image.


### Related Work– 1-3 paragraphs: Talk about relevant work that closely connects with your project.

### Solution– about 3 paragraphs: What did you do in your project- what did you design or implement? 

### Validation - about 2 paragraphs: What did you validate/what was your validation approach? What were the results of your validation?

We approached our project with two intentions of validation. First we were trying to validate if this JS plug was this technically feasible and does it smoothly function within word. **EXPAND ON OUR WORK HERE**. 

The second validation we worked on was validation of our premise. Does more information about alt text best practices improve a content creator's image descriptions. Although inuitively true we wanted to be see what would change for ourselves. We developed two Google forms with 3 images. The first form just asked for image descriptions (alt text). The second form included the object-action-context mantra and shared the 'intent' of the image in the hypothetical content. We sent this out to our class, asking those with even / odd birthday dates to go to form A/B. We did talk about how our population wasn't refelctive of a real world population since it was made up of students who have recently studied accessibility technology and best practices. 

### Learnings and future work – 1-2 paragraphs: Describe what you learned and how this can be extended/ built on in the future.


### References And Links
[Code is available on GitHub](https://github.com/jennifergalley/uw-alt-text)
[University of Washington Course Page](https://courses.cs.washington.edu/courses/csep590a/21sp/)

# SCRAP THIS CONTENT LATER BELOW

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/thenorthwes/improved-word-alt-text/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
