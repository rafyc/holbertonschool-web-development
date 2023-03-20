### Concepts

_For this project, we expect you to look at these concepts:_

- [Some pointers about HTML](https://intranet.hbtn.io/concepts/834)
- [HTML - elements of a web page](https://intranet.hbtn.io/concepts/835)
- [HTML Foundations](https://intranet.hbtn.io/concepts/836)
- [HTML - Semantic sectioning elements](https://intranet.hbtn.io/concepts/837)
- [HTML Semantic Elements](https://intranet.hbtn.io/concepts/838)
- [HTML Validation](https://intranet.hbtn.io/concepts/839)

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1f4cd63ecc3a8c03b0f4309b74aca179e225aabf.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8e18d46fac25691d98fe2dbf68032a33da7b80bbcee1e1fbe3271fc457d5dc8a)

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/97c8976d2ff5ff1871d7a0815b72773379df6acb.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=73c7a0dd0525d5ecd68654b2bef1484c1b1aa23bd49165e8c876c50c503bc97a)

## Resources

**Read or watch**:

- [Learn to Code HTML & CSS](https://intranet.hbtn.io/rltoken/D6o845Dj6bWanYggYGQK4A "Learn to Code HTML & CSS") (_until “Creating Lists” included_)
- [Introduction to HTML](https://intranet.hbtn.io/rltoken/odwyiWUlo7nyK3UR6FUEdg "Introduction to HTML")
- [MDN](https://intranet.hbtn.io/rltoken/STnL1M-mwzCvnzHtG21XGQ "MDN")

## Learning Objectives

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.hbtn.io/rltoken/tk1bYe9n6YmcEsF-gwOgMA "explain to anyone"), **without the help of Google**:

### General

- What is HTML
- How to create an HTML page from a wireframe
- What is a markup language
- What is the DOM
- What is an element / tag
- What is an attribute
- What the purpose of each HTML tag

## Requirements

### General

- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project is mandatory
- You are **not allowed** to install, import or use external libraries. This website must be build with only HTML/CSS/JavaScript. No NodeJS, React, VueJS, Bootstrap, etc.
- Your code should be W3C compliant and validate with [W3C-Validator](https://intranet.hbtn.io/rltoken/czWaAX6ZYwSLoR3bh2Qiqg "W3C-Validator")

## Tasks

### 0. README and objectives!

mandatory

In this and coming projects, you will implement from scratch a webpage from a designer file.

For this first project, you will focus on the HTML structure only - **no CSS, no style - just pure HTML semantic.**

This designer file will be available on [Figma](https://intranet.hbtn.io/rltoken/ChJbK90Un6oS2A6ozdyTQA "Figma") - feel free to create an account to access the final result here:

- [Page in Figma](https://intranet.hbtn.io/rltoken/lhaBvvfXnyGKs9bRxokWtQ "Page in Figma")
- [fig file](https://intranet.hbtn.io/rltoken/BOC4LSHhGgn-RudlXjuUKg "fig file")

And “Duplicate to your Drafts” to have access to all design details.

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=5e3eabe2c2bb2ca7a2945c93eb09369c01c962aae81d6cb3e28ce03b57201237)

Important notes with Figma:

- if your computer doesn’t have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/76O2REi_XN8esxhm9fZg9w "source-sans-pro") and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/tIZuYvssJ291nB0BWUl-Tw "Spin-Cycle-OT")
- some values are in float - feel free to round them

For this task, please write an amazing `README.md`

**Repo:**

- GitHub repository: `holbertonschool-web-development`
- Directory: `html_advanced`
- File: `README.md`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2062#task-18761-carousel)

`README.md` is present

[](https://intranet.hbtn.io/projects/2062#task-18761-carousel)

Help

**0/2** pts

### 1. Header

mandatory

Let’s start by the top: **the header**

Here the wireframe of it:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/415b0226fd338ff76a330b371fc83c9224254c47.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a3667d63eb19359b12402b42f0cb90aa215ade85090455422232be595f1ff804)

- Create the HTML skeleton (`html`, `head`, `body`, etc.)

- In the body, add an `header` tag
- Inside this `header`:
  - Add a link element with an image inside
  - Add a block of 3 link elements

**Repo:**

- GitHub repository: `holbertonschool-web-development`
- Directory: `html_advanced`
- File: `index.html`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2062#task-18762-carousel)

`index.html` is present

[](https://intranet.hbtn.io/projects/2062#task-18762-carousel)

Help

**0/5** pts

### 2. Banner

mandatory

Now, the banner under the `header`:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/ee07503a513036f49d73b31df339ee798f9f277f.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=ac42b181316cf0f975291a588301ae14f603967ca46fecf973076311a3376232)

Under the `header`, add a `main` element with inside a `section` element.

In this `section` element, add:

- A block with inside:
  - An heading tag (don’t forget to use the correct heading value)
  - A text element
  - A button tag
- Another block with inside:
  - Another heading tag (same, be careful about which one you are using)
  - A block containing 4 blocks - each block with inside:
    - An image
    - An heading tag
    - A text

**Repo:**

- GitHub repository: `holbertonschool-web-development`
- Directory: `html_advanced`
- File: `index.html`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2062#task-18763-carousel)

`index.html` is present

[](https://intranet.hbtn.io/projects/2062#task-18763-carousel)

Help

**0/11** pts

### 3. Quote

mandatory

Under the banner, we will add the quote block:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/25b4264f9266962bffb39791b265317cc5ff8147.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=cf292291b180159454ad183dd158b07d027fdf13a233dec5fe245072b78bda76)

The quote section is inside the `main`:

- Create a new `section` for the quote
- Inside, add a block containing:
  - An image
  - Another block with inside:
    - A quote tag
    - An author quote
    - A text

**Repo:**

- GitHub repository: `holbertonschool-web-development`
- Directory: `html_advanced`
- File: `index.html`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2062#task-18764-carousel)

`index.html` is present

[](https://intranet.hbtn.io/projects/2062#task-18764-carousel)

Help

**0/7** pts

### 4. Videos

mandatory

Let’s now add the videos list:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/a5712ac70330c6812c6aee2bf21efe7ac53d1397.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3a7d64446219805ed186ed715e7d6339940a5cca6c0e80ffde631db7f91e4953)

New `section` with inside:

- An heading tag
- A block containing the 4 video block - each of them are composed with:
  - An image
  - An heading
  - A text
  - A block for the author:
    - A image
    - An heading
  - A block for the rating:
    - A block of images (one star = one image)
    - A text

**Repo:**

- GitHub repository: `holbertonschool-web-development`
- Directory: `html_advanced`
- File: `index.html`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2062#task-18765-carousel)

`index.html` is present

[](https://intranet.hbtn.io/projects/2062#task-18765-carousel)

Help

**0/12** pts

### 5. Membership

mandatory

Membership section is similar as the videos list:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1ddf18bc6d89725de2fde4881e8990fae6d89628.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0a74696084e6ea1e431abbc871e7673cc972bf6789dd84fce98fc5e42a0eaa06)

After the videos list section, add a new `section` containing:

- An heading
- A block with inside 4 block item - each block defined with:
  - An image
  - An heading
  - A text
- A button

**Repo:**

- GitHub repository: `holbertonschool-web-development`
- Directory: `html_advanced`
- File: `index.html`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2062#task-18766-carousel)

`index.html` is present

[](https://intranet.hbtn.io/projects/2062#task-18766-carousel)

Help

**0/5** pts

### 6. FAQ

mandatory

The FAQ section is ending the page before the footer:

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/e4b2806abe9edc126fa0d4155aaf5d7e7da479e4.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3aea1c8c8cc4cd97eeae7a74d2d6cab52ccfaaa08c8b5b8f02b66ed4f279d56e)

Add a `section` for the FAQ with inside:

- A block that contains 2 “row block”
- Each “row block” contains 2 “item block”
- Each “item block” is composed of:
  - An heading
  - A text

**Repo:**

- GitHub repository: `holbertonschool-web-development`
- Directory: `html_advanced`
- File: `index.html`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2062#task-18767-carousel)

`index.html` is present

[](https://intranet.hbtn.io/projects/2062#task-18767-carousel)

Help

**0/5** pts

### 7. Footer

mandatory

And… the footer!

![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/7224527ac842981b3b387cd9d713b4a1b912a487.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230320%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230320T093324Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=46adad3847957d26d0e467e85f0741105871fccd29219aabfac377de6932d2fb)

After the last `section`, outside of the `main`, add a `footer`:

- A global block (used later for centering the footer content), inside this block:
  - A “row block” with:
    - An image
    - A block with inside:
      - Images with link
  - A text

And… that’s it for the moment - the result should not be shiny, don’t worry, CSS is coming…

**Repo:**

- GitHub repository: `holbertonschool-web-development`
- Directory: `html_advanced`
- File: `index.html`

Please review your task manually with the following checklist

[](https://intranet.hbtn.io/projects/2062#task-18768-carousel)

`index.html` is present
