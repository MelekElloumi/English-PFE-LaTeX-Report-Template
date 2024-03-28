# English-PFE-Report-Template
This document contains the Latex template of my end-of-study internship report. It was based on the template of [achreffaidi](https://github.com/achreffaidi/PFE-Skeleton).

## How to use

- Download the files in this repo in a zip file

![download image](https://i.imgur.com/xcxxsUD.png)

- Create an account in [Overleaf](https://www.overleaf.com)
- Create a new project by uploading the zip file.
- You can now modify the template and compile it to see the result pdf.
- Chapter 1.tex contains examples of scripts you can use in your report
(figures, tables, equations, sections, references)

## Structure

- In the root folder there's a file called Report.tex. It's used to reference all the other documents on the \pages and \chapters directories.

- \images contains images used in the project.

- \chapters contains the latex code for each chapter.

- \pages contains the complementary sections of the report.

- references.bib and webography.bib contains the citations referenced in the report.

## FrontPage and AbstractPage

- You can modify FrontPage.docx and AbstractPage.docx then save them as .pdf files and include them in the overleaf project.

- You can easily swap between my template pages abd the ones provided by your university

- In Report.tex, line 114 (\includepdf[pages=-]{FrontPage.pdf}) includes the front page pdf at the start of the report
and line 167 for the abstract page at the end.

## How I built this template

I started from Achref Faidi's template. I didn't know how to use latex at first. So by observing the commands and
what they produce helped me grasp it little by little and I used google to help me understand.

I organized the report into chapter files instead of having them all in one main .tex file.

When I wrote my report, I needed some additional features like colouring the table and mofidying the spacing some parts...
With ChatGPT and google, I added the necessary packages to be able to use new commands.

Noramlly when you upload this report you will find only one warning that I couldn't remove but yeah we can't attain perfection.
This is clean and functional and I hope it can help others.

If your report must be in french, I challenge you to modify the necessary scripts (Hint: google "how to change the language of latex document")

At first you will be overwhelmed with this template. My advice is to put the skeleton of the chapters and section. Then visualize 
what you want to write in each subsection and if you need figures or tables. If you can see the end then you can slowly build up the steps to reach it.