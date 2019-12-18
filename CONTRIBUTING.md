# Contributor's Guide Template

If you want to contribute to a project documentation and make it better, your help is very welcome.
This guide puts together the guidelines to help you figure out how you can offer your feedback and contribute to the documentation.

## Contribute in Multiple ways

There are multiple ways to help improve our documentation:

* [Log an issue](https://github.com/opencv/dldt/issues): Enter an issue in the documentation repository for minor issues such as typos.
* [Make a suggestion](): Send your documentation suggestion to the mailing list.
* [Contribute via GitHub](#contribute-via-github): Submit pull requests in the GitHub* documentation repository.

## Contribute via GitHub

Our documentation is hosted in GitHub and we follow the standard GitHub flow. Here are the basic steps for contributing:

1. Clone the documentation repository.
2. Create your own fork of the repository.
3. Create a branch for your contribution.
4. Add your commits.
5. Open a pull request.
6. Discuss, review, and update your contributions.
7. Once the maintainer approves, your contribution is merged.

Here is the list of repositories where the project documentation is located:

* https://github.com/opencv/open_model_zoo - Pre-trained Deep Learning models and samples (high quality and extremely fast)
* https://github.com/opencv/dldt - OpenVINO™ Toolkit Deep Learning Deployment Toolkit repository


The documentation for our project is written using Markdown. Use our guidelines and best practices to write consistent, readable documentation:

* [Authoring Guidelines](#authoring-guidelines)
* [Structure and Formatting Guidelines](#structure-and-formatting-guidelines)
* [Graphics Guidelines](#graphics-guidelines)

## Authoring Guidelines

We want our documentation to be easy to read and understand. This section describes guidelines for writing documentation that is clear, concise, confident, and courteous. 

For details on organizing content and how we use Markdown, refer to [Structure and Formatting](structure-and-formatting-guidelines). 

###	Use simple English

* **Be brief.** Use short sentences and paragraphs. Stick to the principle of one main idea per sentence, plus one additional point if needed. Each paragraph should address one main idea. Remember the basic structure of a paragraph: Introduction, body, and conclusion.

* **Use simple words.** Use simple words to increase reader comprehension and reduce ambiguity. Follow our tips for making good word choices:

   * **Avoid jargon:** Write for your audience, using everyday language where possible, and technical terms where appropriate. Avoid clichés, idioms, and metaphors.

   * **Be consistent:** Use one term for each concept or action and use it consistently.

   * **Avoid “fancy” words and phrases:** If there is a simpler word or phrase, use it.

###	Make content scannable

Organize your content to make it scannable for the reader, which helps them find what they need quickly, and to understand the information more efficiently.

* **Put the most important content first.** Make sure your introduction clearly communicates what the reader can find on the page. Present the point of the document first, and organize supporting information towards the end of the page.
* **Write scannable headings.** Expect readers of documentation to skim and scan the content, and to leave if they don’t find what they need quickly. Good headings add organization to your content and help the reader to find and understand content more effectively. Follow our guidelines for writing effective Headings.
* **Write great link text.** Great link text tells the reader what they can expect when they click on a link. It also helps make the page more scannable. Follow our guidelines for writing Link text.

#### Headings
Use these guidelines to write effective headings:

* **Be concise and descriptive.** Use only the words necessary to describe the section.
* **Use sentence case.** Capitalize only the first word and proper nouns in a heading.
* **Avoid punctuation.** Unless your heading is a question, don’t use sentence punctuation in headings.
* **Use parallel structure.** Headings at the same level should use the same grammatical pattern. This provides structure to the document and helps users find information more easily. See Parallelism.
* **Use strong verbs.** Strong, active verbs get to the point. Avoid -ing verbs, such as Running, Testing, etc.

#### Link text
All links in content should follow these guidelines:

* **Write descriptive link text:** Link text should describe where the link goes, without having to read the surrounding text.
* **Keep link text concise:** Use only the words needed to accurately describe the destination.
* **Use unique link text:** Each link on a page should be unique. If users see the same link text twice on a page, they’ll assume it goes to the same place.
* **Start link text with keywords:** Frontload the link text with the most important words to help users scan the text.
* **Avoid generic text:** Don’t use generic, uninformative link text such as “click here” or “read more”.

###	Use strong verbs

Passive verbs make writing stuffy and formal. Use strong verbs to get to the point and avoid unnecessary words and phrases.

Commands, also called imperatives, are the fastest and most direct way of giving someone instructions.

Use simple present tense instead of future tense for most text. Search for the words “will” or “shall” to find future tense instances. Future tense is acceptable for conditional statements, such as in a caution or a warning.

###	Parallelism

Parallelism refers to the practice of using similar patterns of grammar, and sometimes length, to coordinate words, phrases, and clauses.

Use parallel construction in lists. The table below shows some unparallel structures and how they can be made parallel with a little rewording.

## Structure and Formatting Guidelines

### Documentation format: doc source format (.md, .rst etc.)
### Documentation organization: doc types, page structure, headings
### Inline text formatting 
### Line length (settings for VS Code, Notepad++)
### Code blocks and examples
### Lists and instructions
### Notices
### Links

## Graphics Guidelines

Use images or figures to convey information that may be difficult to explain using words alone. Well-planned graphics reduce the amount of text required to explain a topic or example.

Follow these guidelines when using graphics in support of your documentation:

* Keep it simple. Use images that serve a specific purpose in your document, and contain only the information the reader needs.

* Avoid graphics that will need frequent updating. Don’t include information in a graphic that might change with each release, such as product versions.

* Use either PNG or JPEG bitmap files for screenshots and SVG files for vector graphics.

* Place the image immediately after the text it helps clarify, or as close as possible.

* Use the Markdown directives to insert images and figures into the document. Include both alt text, and the title.

* Include at least one direct reference to an image from the main text, using the figure number.

Images should follow these naming and location conventions:

* Save the image files in a figures folder at the same level as the file that will reference the image.
* Name image files according to the following rules:
   * Use only lower case letters.
   * Separate multiple words in filenames using dashes.
   * Name images using the filename of the file they appear on and add a number to indicate their place in the file. For example, the third figure added to the `welcome.md` file must be named `welcome-3.png`.
