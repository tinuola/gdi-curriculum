# GDI Course Template

*Work in Progress...*

This template is for creating open-source slide content for **Girl Develop It** courses. 

- [How to Use this Template](#how-to-use-this-template)
- [Template Content](#template-content)
- [Example Course Folder](#example-course-folder)

<hr>

## How to Use This Template

Update the `gdi-course-template` folder to the new course name.

Create course content in `class.html`.
  * If the course is a multi-class series, create and number additional `class.html` files.
  * For example: `class1.html`, `class2.html`

If incorporating images/media, add them to the `assets/imgs` folder.

Update the `README.md` file.

Update the `Marketing.md` file.

## Template Content
* Reveal.js scaffolding:
  * `css, dist, examples, js, plugin, test, gulpfile`
  * These are default folders and files that power the template slides, and also contain GDI configurations.
  * Edits to the scaffold should be done at the template level via a pull request. Do not edit the scaffold as you create a course.

* `assets` folder
  * Contains GDI logos and stock images used in the template / starter slides.
  * Images for courses should be stored `imgs` folder.

* Demo files
  * *(work in progress)* `demo-gdi-slides` This is meant to show the various ways to use reveal's features for GDI content as well as outline GDI style guidelines. It's currently still in progress; so for now the `demo-revealjs-slides` file is a better example of what reveal.js can do.

* READMEs
  * README.md: Should contain course information that guides instructors on how to teach the couse 'out of the box'.

  * Marketing.md: Should contain course detail/copy that the GDI Operations team uses to promote the course. 

* class.html
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
  * By default, `class.html` contains the following starter slides or sections. *Blank* slides are to be filled out for a new course or when a course is updated.
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