# GDI Course and Slides Template

*Work in Progress...*

**Girl Develop It** uses a customized HTML slide template for its open-source course content and slides.

Our slides are powered by [Reveal.js](https://revealjs.com/), the popular HTML presentation framework. For simplicity and ease of use, the Reveal.js files are served via CDN in the slides.

Creating a new course is easy! Simply create a duplicate or copy of the `gdi-course-template` folder. All the CSS and JavaScript needed are included; you only need to edit the `class.html` file to build content. This README contains additional instructions for building a course.

To contribute to or update current course content, please see the `Contributing Guidelines` page in this repo's Wiki. _(Coming soon)_

- [How to Use this Template](#how-to-use-this-template)
  + [Course Creation Tips](#course-creation-tips)
  + [Using RevealJS](#using-revealjs)
- [Template Content](#template-content)
- [Example Course Folder](#example-course-folder)

<hr>

## How to Use This Template

Create a copy of the `gdi-course-template` folder and add the copy to a designated topic directory.
  * For example, if creating a new Python course, the copied template folder would be added to the [`python` directory](https://github.com/girldevelopit/gdi-curriculum/tree/main/python).
  * Not sure of where to save a new course? Please ask GDI's Training Director, a member of GDI's Operations team, or your Subject Matter Expert.

Review the `demo-gdi-slides.html` file/slides for how to use Reveal.js and to copy/model code snippets as needed.

Create course content in `class.html`:
  * Update course name in the `<title>` tag.
  * Update course name in the `<footer>` tag.
  * If the course is a cohort or multi-class series, create and number additional `class.html` files:
    * For example: `class1.html`, `class2.html`, etc.

Additional Notes for Cohort or Multi-series classes:
  * For cohorts and multi-class series, it may be helpful to create an `index.html` file that serves as a cover page that links to all classes in the series.
    * For example: ...
  * After the first class in a cohort, subsequent classes don't really require or need all of the introductory GDI slides: (Mission Statement, Code of Conduct, Promos, Intros, etc). The GDI logo, current class title and agenda, a set of `review` slides (if appropriate) and the course content should suffice.

If incorporating images/media, add them to the `assets/imgs` folder.
  * Include credit /attribution to image(s) when possible.

Update the `README.md` file.

Update the `Marketing.md` file.

### Course Creation Tips

We recommend using unstacked slides (rather than nested slides) for better readability.

Limit the amount of content added to each slide. An image, a sentence, or a short code sample are much more understandable than a long list of bullet points.

Prefer visual explanations to text where possible.

Add "teachers' notes" such as FAQs, class management tips/best practices to the course `README.md` that can help future instructors.

### Using Reveal.js

See the [Using Reveal.js](https://github.com/girldevelopit/gdi-curriculum/wiki/Using-Reveal.js) page in this repo's Wiki.

## Template Content

* `assets` folder contains:
  * `css` folder with GDI theme customization for reveal.js
  * `fonts` folder for GDI theme fonts
  * `imgs` folder that holds:
    * GDI logos and stock images used in the template / starter slides.
    * Images for courses should be stored `imgs` folder.

* `demo-gdi-slides.html`
  * *(Work in progress)* This is meant to showcase ways to use reveal.js's features for GDI content, as well as to outline GDI style guidelines. Copy code/section snippets from this file as needed.

  * Note: The demo slides contain common use cases of reveal.js for GDI content. Interested in more ways to use the framework's robust features? Visit the [reveal.js website](https://revealjs.com/) for a full demo.

* `README` files
  * README.md: Should contain course information that guides instructors on how to teach the couse 'out of the box'.

  * Marketing.md: Should contain course detail/copy that the GDI Operations team uses to promote the course. 

* `class.html`
  * This is the primary file that a content/course creator will work in.
  * It contains sections for the course slides. Every `section` element or tag corresponds to a single slide.
  
```html
<div class="reveal">
  <div class="slides"> 
    <section>Slide 1</section>
    <section>Slide 2</section>
    <section>Slide 3</section>
  </div>
</div>
```
  * By default, `class.html` contains the starter slides or sections listed below. 
  * *Blank* slides are to be filled out for a new course or when a course is updated.
    * GDI Welcome and Logo
    * GDI Mission Statement
    * GDI Code of Conduct
    * GDI Marketing Promo
    * Course Title *(Blank)*
    * Instructor (and TA) Intro *(Blank)*
    * Student Intros / Ice Breaker *(Blank)*
    * Housekeeping
    * Course Outline *(Blank)*
    * Course Goals *(Blank)*
    * Course Content *(Blank)*
    * Course Conclusion
    * Feedback Survey *(Blank)*
    * Q & A
    * Resources *(Blank)*
    * GDI Upcoming Courses promo *(Blank)*
    * Instructor Contact *(Blank)*
    * Thank You


## Example Course Folder

For an example of how this template folder is used, please see the ....*To be added*
