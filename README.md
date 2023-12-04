#This is an example of a read me file: 


Readme: key details at a glance – including a template

The file name readme contains a simple instruction and for good reason. The readme file is typically the first file a developer will look at before beginning a project. It’s also important that developers know how to write a good readme file that conveys all the relevant information in a concise manner.
Contents

    What are readme files and why do I need them?
    What should a readme file contain?
    Possible file formats for readme files
    Readme.md: an example in markdown format
    Readme example template

What are readme files and why do I need them?

A readme file – often created as readme.txt or readme.md – usually contains important information about the respective system, project or software. To ensure users can find the file straight away, it should ideally be placed in the top directory level.
Tip

README is often written in capital letters. Systems that differentiate between upper and lower case will then list the file before all other files that begin with lower-case letters.

The file also fulfills different purposes for different users:

    For end users, a readme file answers questions about installing, updating or using the software.
    For your own development work, a readme file provides two advantages. On the one hand, a readme file written prior to the start of development provides a guideline for implementing the project. On the other hand, it lets you resume work quickly if a project was previously set aside for a prolonged period of time.
    For other developers, a readme file clarifies the codex and provides key information for further development or use of a system, software or an open-source project. 

What should a readme file contain?

Depending on the purpose of a readme file, the following content in particular may be relevant:

    A general description of the system or project
    The project status is important if the project is still in development. Use the file to mention planned changes and the development direction or indicate the completion date of the project.
    The requirements on the development environment for integration
    A guide to installation and use
    A list of technology used and any links to further information related to this technology
    Open-source projects that the developers independently modify or expand should be contained in a section on “desired collaboration” in the readme.md file. How should problems be handled? How should developers advance the changes?
    Known bugs and any bug fixes
    FAQ section with all previously asked questions
    Copyright and licensing information

It’s important to write the readme file so that it is always aimed at the end user. This will resolve most of the questions that potentially arise.
Possible file formats for readme files

You can write and save a readme file in any text file format you wish. Formats may include readme.txt, readme.doc, and readme.1st. Depending on the platform the software should run on, the format of the readme file should be adjusted to the respective system and the associated text program. This ensures that the word processor is able to read the file.

Today, developers mostly use the readme.md format. But what is an .md file? The file ending indicates a readme file in markdown format. Markdown converts text into HTML using simple formatting characters. A well-formatted and structured readme file gives users a comprehensive overview of the project.
Readme.md: an example in markdown format

We show you piece by piece how a readme.md is structured and what formatting options exist with the markdown format. To enable global collaboration and prevent language barriers, you should always write the readme file in English.

Readme example in markdown format:

# Project name
***
Short description of the project.

Tip

Insert a horizontal divider with “***”.

The top of a readme file should contain a suitable project name and a short explanation about what the project is about. In markdown format, a hash sign “#” indicates the start of a headline. The number of hash signs determines the type of headline:

# Headline H1
## Headline H2
### Headline H3
#### Headline H4 
##### Headline H5
###### Headline H6

For extensive documentation, a clear table of contents provides a useful overview:

## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)

The table of contents can be structured with an ordered list in the readme.md. Simply insert the corresponding number at the start of the row and the list is created.

GitHub automatically adds IDs for the headlines in the readme file. The IDs are derived from the name of the headline and a hyphen “-” replaces the spaces. They are ideal for use as anchor navigation in the table of contents. If the readme.md is intended for a different platform that does not automatically assign IDs to headlines, anchor navigation can be created with HTML:

## Table of Contents
<a name="general-info"></a>
### General Info

The table of contents are followed by the individual blocks of content on the respective points:

## General Info
***
Write down general information about your project. It is a good idea to always put a project status in the readme file. This is where you can add it. 
### Screenshot
![Image text](/path/to/the/screenshot.png)

General information about the project is important to provide an impression of what it contains, in addition to a short explanation. A markdown also allows you to insert graphics, screenshots or other images into the documentation. Simply write a descriptive word in square brackets followed by the URL for the image in round brackets (without spaces in between). Enter an exclamation mark in front, so that markdown interprets it as an image file.

## Technologies
***
A list of technologies used within the project:
* [Technology name](https://example.com): Version 12.3 
* [Technology name](https://example.com): Version 2.34
* [Library name](https://example.com): Version 1234

You can create bullet points in an unordered list in markdown format using an asterisk “*” at the beginning of the line.

Links can be inserted anywhere in the readme.md. The structure is very similar to an image file, but without the exclamation mark at the beginning of the line. Write the word to be linked in square brackets, followed by the path to the website in round brackets (likewise without any spaces between).
Note

The file should always be in the same repository. You can also use other publicly available files. However, there is a risk that the owner may delete these files at some point, thereby removing them from your readme.md.

## Installation
***
A little intro about the installation. 
```
$ git clone https://example.com
$ cd ../path/to/the/file
$ npm install
$ npm start
```
Note: To use the application in a special environment use ```lorem ipsum``` to start.

Since a readme file is often used in the context of software development, it can be a good idea to include examples of source text in the document. Markdown provides a formatting option for this, too. The code can be formatted with “```” at the beginning and end. You can also use code sections directly in the text.

## Collaboration
***
Provide instructions on how to collaborate with your project.
> Maybe you want to write a quote in this part. 
> Should it encompass several lines?
> This is how you do it.

A “>” at the start of the line will change the text into a quote.

## FAQs
***
A list of frequently asked questions
1. **This is a question in bold**
Answer to the first question with _italic words_. 
2. __Second question in bold__ 
To answer this question, we use an unordered list:
* First point
* Second Point
* Third point
3. **Third question in bold**
Answer to the third question with *italic words*.
4. **Fourth question in bold**
| Headline 1 in the tablehead | Headline 2 in the tablehead | Headline 3 in the tablehead |
|:--------------|:-------------:|--------------:|
| text-align left | text-align center | text-align right |

Ordered and unordered lists can also be used in combination in the readme.md. Simply continue the numbered list with the corresponding number.

We have integrated italic and bold words and passages for illustrative purposes. You can create italic text by placing the respective word or passage between a simple asterisk “*” or underscore “_”. For bold formatting, enter doubled asterisks or underscores.

Tables can also be inserted into the readme.md using the markdown format. You can create tables using pipes “|” and hyphens “-”. The colons indicate whether the text should be left, right or center-aligned.
Readme example template

Below you will find a summary of examples from the article as a readme template:

## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
5. [FAQs](#faqs)
### General Info
***
Write down general information about your project. It is a good idea to always put a project status in the readme file. This is where you can add it. 
### Screenshot
![Image text](https://www.united-internet.de/fileadmin/user_upload/Brands/Downloads/Logo_IONOS_by.jpg)
## Technologies
***
A list of technologies used within the project:
* [Technology name](https://example.com): Version 12.3 
* [Technology name](https://example.com): Version 2.34
* [Library name](https://example.com): Version 1234
## Installation
***
A little intro about the installation. 
```
$ git clone https://example.com
$ cd ../path/to/the/file
$ npm install
$ npm start
```
Side information: To use the application in a special environment use ```lorem ipsum``` to start
## Collaboration
***
Give instructions on how to collaborate with your project.
> Maybe you want to write a quote in this part. 
> Should it encompass several lines?
> This is how you do it.
## FAQs
***
A list of frequently asked questions
1. **This is a question in bold**
Answer to the first question with _italic words_. 
2. __Second question in bold__ 
To answer this question, we use an unordered list:
* First point
* Second Point
* Third point
3. **Third question in bold**
Answer to the third question with *italic words*.
4. **Fourth question in bold**
| Headline 1 in the tablehead | Headline 2 in the tablehead | Headline 3 in the tablehead |
|:--------------|:-------------:|--------------:|
| text-align left | text-align center | text-align right |

Tip

Use the WYSIWYG editor from Dillinger to create a readme.md online quickly and easily.

    10/08/2020
    Web development 

Related articles
Markdown Editors
Markdown Editors

How can you easily format texts for use online and offline? This becomes a piece of cake when you use the markup language Markdown and an editor. With these editors for Linux, Windows and Mac as well as the online editors, you can create Markdown documents and convert them into HTML pages. But what are the best Markdown editors?
Markdown Editors
Related Products
IONOS MyWebsite
MyWebsite
Deals at IONOS

Save on our most popular products, including cloud storage, hosting, websites, servers and more.
Popular Articles
Personal e-mail domains: How to get your own e-mail domain

Create your personal email address with your own email domain to demonstrate professionalism and credibility.
How do you buy a domain name? A guide

How do you register and secure a domain name? And how do you buy a domain that’s already been taken?
What are the different types of domains?

What are the different types of domain endings? And what’s the difference between top-level domains and second-level domains?…
What is prompt engineering and how does it work?

What is prompt engineering and how can it be used to improve the results of ChatGPT and other chatbots? Find out everything…
Different Website Types compared

Choosing the right type of website is critical to the success of any online endeavor. Corporate website, blog, microsite –…
