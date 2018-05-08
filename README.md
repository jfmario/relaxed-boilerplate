
# RelaXed Boilerplate

UNDER CONSTRUCTION

This is a boilerplate for book PDF projects using
[RelaXedJS](https://github.com/RelaxedJS/ReLaXed) for PDF generation.

The purpose of this repository is to serve as a starting point and 
reference.

It includes a few sample lorem ipsum chapters as well as an image.

The `book.pug` file and the `book.scss` theme are variations on the official
book example provided by RelaXed.

## Getting Started

Use this a starting point for a book PDF project.

### Prerequisites

In order to use RelaXed, you need to have pupetteer installed.
When it is installed on Amazon Linux EC2, installing RelaXed is not 
enough to get pupetteer working. 

I found this article to be helpful:

https://mockingbot.com/posts/run-puppeteer-chrome-headless-on-ec2-amazon-linux

### Installation

* Clone this repository
* Install RelaXed: `npm i -g relaxedjs`

### Usage

Write chapters in markdown format in the `src/` directory. Follow the examples
in `book.pug` to add more chapters. The system I have here is the the markdown
files contain only the chapter text (not titles or title images).

Titles and title images should be included in the pug file.

When ready, run `relaxed book.pug` to watch your files and generate `book.pdf`.

I find relaxed to be a little clunky, especially without the ability to do 
a one-time generation of the PDF instead of watching the directory.

I often make my edits, then start relaXed, then re-save the .pug file to get 
the PDF.










