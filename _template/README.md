# GDI Course and Slides Template

_Work in Progress..._

**Girl Develop It** uses a customized HTML slide template for its open-source course content and slides.

Our slides are powered by [Reveal.js](https://revealjs.com/), the popular HTML presentation framework. For simplicity and ease of use, the Reveal.js files are served via CDN in the slides.

Creating a new course is easy! Simply create a duplicate or copy of the `gdi-course-template` folder. All the CSS and JavaScript needed are included; you only need to edit the `index.html` file to build content. This README contains additional instructions for building a course.

To contribute to or update current course content, please see the `Contributing Guidelines` page in this repo's Wiki. _(Coming soon)_

- [How to Use this Template](#how-to-use-this-template)
  - [Course Creation Tips](#course-creation-tips)
  - [Using RevealJS](#using-revealjs)
- [Template Content](#template-content)
- [Example Course Folder](#example-course-folder)

<hr>

## How to Use This Template

1. Create a copy of the `gdi-course-template` folder. Add the copy to a designated topic directory.

   - For example, if creating a new Python course, the copied template folder would be added to the [`python` directory](https://github.com/girldevelopit/gdi-curriculum/tree/main/python).
   - Not sure of where to save a new course? Check in with GDI's Training Director, a member of GDI's Operations team, or a Lead Subject Matter Expert (SME).

2. Review the `demo-gdi-slides.html` file for how to use Reveal.js, and to copy/model slides or code snippets as needed.

3. For a single course, create course content in `index.html`:

   - Update course name in the `<title>` tag.
   - Update course name in the `<footer>` tag.
   - Create course slides.

4. For a cohort or multi-class series:

   - `index.html` should be a cover page that links to all classes in the series.
     - See the `demo-cohort-index.html` file as an example.
   - Rename `index.html` to `class1.html`. Create additional copies for each class in the series: `class2.html`, `class3.html`, etc.
     - Update course name in the `<title>` tag.
     - Update course name in the `<footer>` tag.
     - Create course slides.
   - NOTE: After the first class in a cohort, subsequent classes don't require or need a lot of the introductory GDI slides: (Mission Statement, Code of Conduct, Promos, Intros, etc). The GDI logo, current class title and agenda, a set of `review` slides (if appropriate) and the course content should suffice.
   - Rename `demo-cohort-index.html` to `index.html` and update the file contents.
     - Update with links to the `class#.html` files.
     - Update course name in the `<title>` tag.
     - Update course name in the `<footer>` tag.

5. If incorporating images/media, add them to the `assets/imgs` folder.

   - Include credit /attribution to image(s) when possible.
   - Optimize/compress all images to reduce file size. Try [tinypng.com](https://tinypng.com/).

6. Optional: Update the course's `README.md` file.

7. Optional: Update the courses' `MARKETING.md` file.

8. Update the `CHANGELOG.md` file in curriculum repo's root directory.

**Do not delete** the `demo-gdi-slides.html` file. It is meant to serve as a reference for using reveal.js and as a style guide.

<hr>

### Course Creation Tips

- We recommend using unstacked slides (rather than nested slides) for better readability.

- Limit the amount of content added to each slide. An image, a sentence, or a short code sample are much more understandable than a long list of bullet points.

- Prefer visual explanations to text where possible.

- Add "teachers' notes" such as FAQs, class management tips/best practices to the course `README.md` that can help future instructors.

<hr>

### Using Reveal.js

See the [Using Reveal.js](https://github.com/girldevelopit/gdi-curriculum/wiki/Using-Reveal.js) page in this repo's Wiki.

<hr>

## Template Content

- `assets` folder contains:

  - `css` folder with GDI theme customization for reveal.js
  - `fonts` folder for GDI theme fonts
  - `imgs` folder that holds:
    - GDI logos and stock images used in the template / starter slides.
    - Images for courses should be stored `imgs` folder.

- `demo-cohort-index.html`

  - Example file of an index or cover page listing/linking all classes in a cohort series. This file can be deleted if the course being created is not a cohort.

- `demo-gdi-slides.html`

  - _(Work in progress)_ This is meant to showcase ways to use reveal.js's features for GDI content, as well as to outline GDI style guidelines. Copy code/section snippets from this file as needed.

  - The demo slides contain common use cases of reveal.js for GDI content. Interested in more ways to use the framework's robust features? Visit the [reveal.js website](https://revealjs.com/) for a full demo.

  - **Do not delete this file.**

- `README` files

  - README.md: Should contain course information that guides instructors on how to teach the couse 'out of the box'.

  - MARKETING.md: Should contain course detail/copy that the GDI Operations team uses to promote the course.

- `index.html`
  - This is the primary file that a content/course creator will work in.
    - NOTE: For cohort classes, work will be done in `class#.html` files.
  - It contains sections for the course slides. Every `section` element or tag corresponds to a single slide.

```html
<div class="reveal">
	<div class="slides">
		<section>Slide 1</section>
		<section>Slide 2</section>
		<section>Slide 3</section>
	</div>
</div>
```

- By default, `index.html` contains the starter slides or sections listed below.
- _Blank_ slides are to be filled out for a new course or when a course is updated.
  - GDI Welcome and Logo
  - GDI Mission Statement
  - GDI Code of Conduct
  - GDI Marketing Promo
  - Course Title _(Blank)_
  - Instructor (and TA) Intro _(Blank)_
  - Student Intros / Ice Breaker _(Blank)_
  - Housekeeping
  - Course Outline _(Blank)_
  - Course Goals _(Blank)_
  - Course Content _(Blank)_
  - Course Conclusion
  - Feedback Survey _(Blank)_
  - Q & A
  - Resources _(Blank)_
  - GDI Upcoming Courses promo _(Blank)_
  - Instructor Contact _(Blank)_
  - Thank You

## Example Course Folder

For an example of how this template folder is used, please see the ...._To be added_
