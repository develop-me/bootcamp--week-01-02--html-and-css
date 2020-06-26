# Develop Me HTML & CSS Syllabus

HTML &amp; CSS Syllabus for Developme: This covers both the first two weeks of the fellowship and the part time evening course.

### Overview

The first part is mainly based on theory lessons, learning HTML & CSS. Syntax, elements, style & layout, with supported exercises.

>If exercises are not held in directories, they are on codepen (this is a much easier set up for students in the early days). Codepen account is @devmeexamples. It's worth looking through this account as there are plenty of other useful examples!

The second part is writing the templates for a multipage site. Theory includes how to approach a project, design handover, CSS methodology to structure your HTML & CSS well; we support the theory of component design and reuseable CSS

There are three categories taught in this course: HTML, CSS & Web Theory. The latter is for notes & lessons on accessibility, performance, testing, project planning & design theory.

### Folder structure

- exercises
	Each lesson contains exercises, here you will either find the code or the instructions for the students. After the first day the exercises build on from each other.
- notes
	These are the students notes - see []() to run LaTeX to generate the pdfs for the students
- quiz
	There is one for each week/part, but they are held in google docs, under the instructor account. Archive any previous quiz answers and then remove them from the form before distributing to new students
- slides
	These are also the tutors notes. We encourage live coding over slides, however all these notes use [PITCHME](https://github.com/gitpitch/in-60-seconds) markdown files, so you can view as plain markdown, or run on github as a presentation (good for new tutors).

### Notes for new tutors

Go through the repo - the slides folder especially. We teach in increments so you may feel valuable info is being omitted only to find it's being taught at a later stage. Don't overwhelm your students - remember you will have to lie until you can tell the truth.

If you are adding content: Choose your unit, create/modify slides, notes & exercises content as per. Things you may find useful:
- There is an example presentation in the [root directory here](PITCHME.md) I strongly recommend using that to create new presentations

## Suggested Course Structure

Feel free to mix and match the syllabus order as you see fit. This is proposed so you can keep track of where you have been and where you go next.

Order in the repo is as per category, not as per order in which you teach.

>I recommend printing off the table and making notes as you go as to what you have taught & amends

#### Part One

| PT | FT | Title | Lesson | Slides | Exercise | Notes |
|---|---|---|---|---|---|---|
|  |  | Intro & Class Rules | [Lesson](https://gitpitch.com/develop-me/bootcamp--week--01-02--html-and-css/master/slides/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides#/) |   |   |
|  |  | Web Theory: General Overview | [Lesson](slides/web-theory/01_overview/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/01_overview/#/) |  | web-theory.pdf 1.1 |
|  |  | HTML: Intro & Syntax | [Lesson](slides/HTML/01_intro-syntax/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/HTML/01_intro-syntax#/) | [Exercise](exercises/HTML/01_intro-syntax) | html.pdf 1.1 |
|  |  | HTML: Content Elements | [Lesson](slides/HTML/02_content-els/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/HTML/02_content-els#/) | [Exercises](exercises/HTML/02_content-els) | html.pdf 2.1 |
|  |  | Web Theory: Assistive Technologies |  | [Lesson](slides/web-theory/02_assistive/PITCHME.md) |  |  |
|  |  | HTML: Sectioning Elements | [Lesson](slides/HTML/03_sectioning-els/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/HTML/03_sectioning-els#/) | [Exercises](exercises/HTML/03_sectioning-els) | html.pdf 2.2 |
|  |  | Web Theory: Devtools | [Lesson](slides/web-theory/03_devtools/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/03_devtools#/) | [Exercises](exercises/web-theory/03_devtools/README.md) | web-theory.pdf |
|  |  | HTML: Media Elements | [Lesson](slides/HTML/04_media-els/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/HTML/04_media-els#/) | [Exercises](exercises/HTML/04_media-els) |  |
|  |  | CSS: Intro & Syntax | [Lesson](slides/CSS/01_intro-syntax/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/01_intro-syntax#/) | [Exercise](exercises/CSS/01_intro-syntax) | css.pdf 1.1 |
|  |  | CSS: Basic Styles | [Lesson](slides/CSS/02_basic-styles/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/02_basic-styles#/) | [Exercises](exercises/CSS/02_basic-styles) | css.pdf 2.1 |
|  |  | HTML: Metadata | [Lesson](slides/HTML/05_metadata/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/HTML/05_metadata#/) | [Exercises](exercises/HTML/05_metadata) | html.pdf 1.2 |
| * | * |<td colspan="5">Go over everything we have done, organise your files and notes, remember to shut down your text editor when you do. Sit somewhere different tomorrow</td>
|  |  | HTML: Text Elements | [Lesson](slides/HTML/06_text-els/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/HTML/06_text-els#/) | [Exercises](exercises/HTML/06_text-els) | html.pdf 2.4 |
|  |  | CSS: Web Fonts | [Lessons](slides/CSS/03_web-fonts/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/03_web-fonts#/) | [Exercises](exercises/CSS/03_web-fonts) | css.pdf 2.3 |
|  |  | CSS: Box Model | [Lesson](slides/CSS/04_box-model/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/04_box-model#/) | [Exercises](exercises/CSS/04_box-model) | css.pdf |
|  |  | Web Theory: Devtools | [Lesson](slides/web-theory/03_devtools/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/03_devtools#/) | [Exercises](exercises/HTML/05_devtools) | web-theory.pdf |
|  |  | CSS Colours | [Lesson](slides/CSS/05_colours/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/05_colours#/9) | [Exercises](exercises/CSS/05_colours) | css.pdf 2.2 |
| * |  |<td colspan="5">The button exercise</td>
|  |  | CSS Floats | [Lesson](slides/CSS/06_floats/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/06_floats#/) | [Exercises](exercises/CSS/06_floats) | css.pdf |
|  |  | CSS Units | [Lesson](slides/CSS/07_units/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/07_units#/) | [Exercises](exercises/CSS/07_units) |  |
|  | * |<td colspan="5">Flexbox Froggy</td>
|  |  | HTML Forms | [Lesson](slides/HTML/07_forms/PITCHME.md) | [Notes](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/HTML/07_forms#/) | [Exercises](exercises/HTML/07_forms) | html.pdf |
| * |  |<td colspan="5">Flexbox Froggy & Form Exercise
|  |  | CSS Flexbox | [Lesson](slides/CSS/08_flexbox/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/08_flexbox#/) | [Exercises](exercises/CSS/08_flexbox) | css.pdf |
|  |  | Responsive Design | [Lesson](slides/CSS/09_media-queries/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/09_media-queries#/) | [Exercises](exercises/CSS/09_media-queries) | css.pdf |
| * |  <td colspan="5">Finish flexbox & media query exercises. |
|  | * <td colspan="5">Play Grid Garden |
|  |  | CSS Grid Part 1 | [Lesson](slides/CSS/10-grid-1/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/10-grid-1#/) | [Exercises](exercises/CSS/10-grid-1) | css.pdf |
|  |  | CSS Grid Part 2 | [Lesson](slides/CSS/10-grid-2/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/10-grid-2#/) | [Exercises](exercises/CSS/10-grid-2) | css.pdf |
|  | * |<td colspan="5">Revise for quiz tomorrow</td>
|  |  | Requirements Gathering | [Lesson](slides/web-theory/04_requirements/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/04_requirements#/) | [Exercises](exercises/web-theory/04_requirements) | web-theory.pdf 4.1 |
|  |  | Sitemaps | [Lesson](slides/web-theory/05_sitemap/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/05_sitemap#/) | [Exercises](exercises/web-theory/05_sitemap) | web-theory.pdf 4.2 |
|  |  | Scamps | [Lesson](slides/web-theory/06_scamping/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/06_scamping#/) | [Exercises](exercises/web-theory/06_scamping) | web-theory 4.3 |
|  | * |<td colspan="5">Quiz & 1-1s</td>
|  |  | Wireframes | [Lesson](slides/web-theory/07_wireframing/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/07_wireframing#/) | [Exercises](exercises/web-theory/07_wireframing) | web-theory 4.4 |
| x |  | CSS Framworks | [Lesson](slides/CSS/11_frameworks/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/11_frameworks#/) | [Exercise](exercises/CSS/11_frameworks) | css.pdf 4.4 |
|  | * |<td colspan="5">Homework: Prototype with Bootstrap</td>


#### Part Two

Figma Student Master for Part Two - https://www.figma.com/file/6TdVNL837VjTI7yvmiyKXf/Photography-Site-Student-Master?node-id=0%3A1

| PT | FT | Title | Lesson | Slides | Exercise | Notes |
|---|---|---|---|---|---|---|
|  |  | Design Systems | [Lesson](slides/CSS/12_design-systems/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/12_design-systems#/) | [Exercise](exercises/CSS/12_design-systems) | css.pdf 5.1 |
|  |  | Atomic Design | [Lesson](slides/CSS/13_atomic-design/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/13_atomic-design#/) |  | [Exercise](exercises/CSS/13_atomic-design) |
|  |  | Design Handover | [Lesson](slides/web-theory/08_design-handover/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/08_design-handover#/) | [Exercises](exercises/web-theory/08_design-handover) | web-theory.pdf 3.5 |
|  |  | Design Breakdown | [Lesson](slides/web-theory/09_design-breakdown/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/09_design-breakdown#/) | [Exercises](exercises/web-theory/09_design-breakdown) | web-theory.pdf 3.6 |
|  |  | Positioning & Transforms | [Lesson](slides/CSS/14_positioning/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/14_positioning#/) | [Exercises](exercises/CSS/14_positioning) | css.pdf |
|  |  | Imports | [Lesson](slides/CSS/15_imports/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/15_imports#/2) | [Exercises](exercises/CSS/15_imports) | css.pdf 4.1 |
|  |  | Variables | [Lesson](slides/CSS/16_variables/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/16_variables#/4) | [Exercises](exercises/CSS/16_variables) | css.pdf 4.2 |
|  |  | Accessibility | [Lesson](slides/web-theory/10_accessibility/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/10_accessibility#/) | [No exercise yet](exercises/web-theory/10_accessibility) | web-theory.pdf 3.2 |
|  |  | OOCSS | [Lesson](slides/CSS/17_OOCSS/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/17_OOCSS) | [Exercises](exercises/CSS/17_OOCSS) | css.pdf 4.3 |
|  |  | CSS Effects | [Lesson](slides/CSS/18_effects/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/18_effects#/6) | [Exercises](exercises/CSS/18_effects) | css.pdf 1.5 |
|  |  | BEM | [Lesson](slides/CSS/19_BEM/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/19_BEM#/) | [Exercises](exercises/CSS/19_BEM) | css.pdf 4.4 |
|  |  | Complex Selectors | [Lesson](slides/CSS/20_complex-selectors/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/20_complex-selectors#/) | [Exercises](exercises/CSS/20_complex-selectors) | css.pdf |
|  |  | Specificity | [Lesson](slides/CSS/21_specificity/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/CSS/21_specificity#/) | [Exercises](exercises/CSS/21_specificity) | css.pdf |
|  |  | Upload to server | [Lesson](slides/web-theory/11_upload/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/11_upload#/) | [Exercises](exercises/web-theory/11_upload) |  |
|  |  | Testing | [Lesson](slides/web-theory/12_testing/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/12_testing#/) | [Exercises](exercises/web-theory/12_testing) |  |
|  |  | Web Theory: Devtools | [Lesson](slides/web-theory/03_devtools/PITCHME.md) | [Slides](https://gitpitch.com/develop-me/bootcamp--week-01-02--html-and-css/master?p=slides/web-theory/03_devtools#/) | [Exercises](exercises/web-theory/03_devtools/README.md) | web-theory.pdf |
|  |  | CSS Animation |  |  |  |  |
|  |  | Extra CSS |  |  |  |  |

#### Key

- `x` Can be ommitted
- `*` This course only

- CSS: CSS Animation
	- [Slides](slides/CSS/22_animation/PITCHME.md)
	- [Exercises](exercises/CSS/22_animation)
- CSS: Extra CSS
	- [Slides](slides/CSS/23_extra/PITCHME.md)
	- [Exercises](exercises/CSS/23_extra)