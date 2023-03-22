# CSS, advanced - Amateur - By: Guillaume Salva, CTO at Holberton School -

Weight: 1 ### Concepts _For this project, we expect you to look at these
concepts:_ - [Some pointers about CSS](https://intranet.hbtn.io/concepts/840) -
[CSS fundamentals](https://intranet.hbtn.io/concepts/841) - [CSS
advanced](https://intranet.hbtn.io/concepts/847)
![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/1f4cd63ecc3a8c03b0f4309b74aca179e225aabf.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230322%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230322T070609Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=4ab1d75afdbeac442ea9fcf063760534fc5c9524378cdc0bab9fe2c98f3c85df)

## Resources **Read or watch**: - [Learn to Code HTML &

CSS](https://intranet.hbtn.io/rltoken/F2pX4OykI21fHe88c2epKQ "Learn to Code HTML
& CSS") (_until “Creating Lists” included_) - [Inline Styles in
HTML](https://intranet.hbtn.io/rltoken/1SJ8hD4imW6bcw5tzzeT3Q "Inline Styles in
HTML") - [Specifics on CSS
Specificity](https://intranet.hbtn.io/rltoken/Fx7Rohte4tNqh1eboMY2_Q "Specifics
on CSS Specificity") - [CSS
SpeciFishity](https://intranet.hbtn.io/rltoken/2JCM5ZBeHSKbU6XK69phgA "CSS
SpeciFishity") - [CSS](https://intranet.hbtn.io/rltoken/2s3Y6s-SLb-OtEhrtiQx3g "CSS") - [MDN](https://intranet.hbtn.io/rltoken/cUKKIIhFEfXqUbIsx0LRWQ "MDN") ##
Learning Objectives At the end of this project, you are expected to be able to
[explain to anyone](https://intranet.hbtn.io/rltoken/3O8RRdO_zmZQ0_7vJP-x1g "explain to anyone"), **without the help of Google**: ### General - What is CSS

- How to add style to an element - What is a class - What is a selector - How to
  compute CSS Specificity Value - What are Box properties in CSS - How does the
  browser load a webpage ## Requirements ### General - All your files should end
  with a new line - A `README.md` file, at the root of the folder of the project
  is mandatory - You are **not allowed** to install, import or use external
  libraries. This website must be build with only HTML/CSS/JavaScript. No NodeJS,
  React, VueJS, Bootstrap, etc. - Your code should be W3C compliant and validate
  with [W3C-Validator](https://intranet.hbtn.io/rltoken/tdfM5nIHc07ziIf2TmplKQ "W3C-Validator") ## Tasks ### 0. README and objectives! mandatory This project
  is following the `0x02. HTML, advanced` project - please make sure all tasks of
  this previous one are fully done. For this project, you will focus on the CSS
  and the style of the page. This designer file will be available on
  [Figma](https://intranet.hbtn.io/rltoken/xpBbmWCQ6UbA5zJOC4VbEQ "Figma") - feel
  free to create an account to access the final result here: - [Page in
  Figma](https://intranet.hbtn.io/rltoken/WcoJ5j4uynlWPJYDc1T2Iw "Page in Figma")
- [fig file](https://intranet.hbtn.io/rltoken/WfyjkKwVzm-sm45PQc28Cw "fig file")
  And “Duplicate to your Drafts” to have access to all design details. (if not
  already done)
  ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230322%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230322T070609Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f5d37d7ba4d0e5a831485da9ede074cd942ee41bd5e9fd1954883655e66d165d)
  Important notes with Figma: - if your computer doesn’t have missing fonts, you
  can find them here:
  [source-sans-pro](https://intranet.hbtn.io/rltoken/UdQuzPSdBNnOkWc-KkBdqw "source-sans-pro") and
  [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/NZS_cTcrHwbfSEyH53LGag "Spin-Cycle-OT") - some values are in float - feel free to round them For this
  task, please write an amazing `README.md` and copy the `index.html` file from
  `0x02. HTML, advanced` **Repo:** - GitHub repository:
  `holbertonschool-web-development` - Directory: `css_advanced` - File:
  `README.md, index.html` Please review your task manually with the following
  checklist [](https://intranet.hbtn.io/projects/2063#task-18769-carousel)
  `README.md` is present
  [](https://intranet.hbtn.io/projects/2063#task-18769-carousel) Help **0/3** pts

### 1. Import the style mandatory Before starting the implementation of the

Style: - Create the file `styles.css` - Import `styles.css` in the `head` of
your `index.html` **Repo:** - GitHub repository:
`holbertonschool-web-development` - Directory: `css_advanced` - File:
`index.html, styles.css` Please review your task manually with the following
checklist [](https://intranet.hbtn.io/projects/2063#task-18770-carousel)
`styles.css` is present
[](https://intranet.hbtn.io/projects/2063#task-18770-carousel) Help **0/1** pt

### 2. Header and Banner mandatory Based on the

[Figma](https://intranet.hbtn.io/rltoken/WcoJ5j4uynlWPJYDc1T2Iw "Figma") file,
add the correct styling to the `header` and first `section` of the page
![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/d334bcd363741f2c5e5f32cd6114f4bd85910290.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230322%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230322T070609Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=88f0b8c18ad895dd14302983133392e05c50b47a0dada4901bbcef168ed9e29d)
**Reminders:** - All colors values, width, height and images are part of the
Figma - Keep your CSS simple and clean - use as simple as you can CSS selectors

- Be accurate - the final result should be the same as the page at the end!
  **Repo:** - GitHub repository: `holbertonschool-web-development` - Directory:
  `css_advanced` - File: `styles.css` Please review your task manually with the
  following checklist
  [](https://intranet.hbtn.io/projects/2063#task-18771-carousel) `styles.css` is
  present [](https://intranet.hbtn.io/projects/2063#task-18771-carousel) Help
  **0/10** pts ### 3. Quotes mandatory Based on the
  [Figma](https://intranet.hbtn.io/rltoken/WcoJ5j4uynlWPJYDc1T2Iw "Figma") file,
  add the correct styling to the quote `section`
  ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/ee0996ad34d3fae07261689c6f0b2cb5613880a9.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230322%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230322T070609Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fe9c9f69adec47cfe5891a4cbd21e53edd12b3dce1f674276a0f6186d0ce7bf9)
  **Tips:** - You can start to see similar or common style, time to start to
  centralize your style and CSS selectors **Repo:** - GitHub repository:
  `holbertonschool-web-development` - Directory: `css_advanced` - File:
  `styles.css` Please review your task manually with the following checklist
  [](https://intranet.hbtn.io/projects/2063#task-18772-carousel) `styles.css` is
  present [](https://intranet.hbtn.io/projects/2063#task-18772-carousel) Help
  **0/5** pts ### 4. Videos list mandatory Based on the
  [Figma](https://intranet.hbtn.io/rltoken/WcoJ5j4uynlWPJYDc1T2Iw "Figma") file,
  add the correct styling to the videos list `section`
  ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/d47a729b9d6702221c8efc85b1230e99141c6d10.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230322%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230322T070609Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fa790789c6f9d8c5c791c8c04ff263943a0b15913df3e0780cdac040480196fa)
  **Repo:** - GitHub repository: `holbertonschool-web-development` - Directory:
  `css_advanced` - File: `styles.css` Please review your task manually with the
  following checklist
  [](https://intranet.hbtn.io/projects/2063#task-18773-carousel) `styles.css` is
  present [](https://intranet.hbtn.io/projects/2063#task-18773-carousel) Help
  **0/9** pts ### 5. Membership mandatory Based on the
  [Figma](https://intranet.hbtn.io/rltoken/WcoJ5j4uynlWPJYDc1T2Iw "Figma") file,
  add the correct styling to the membership `section`
  ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/aaf4bb53ac9d8944b1ced13aa4c7090e5eb3be2f.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230322%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230322T070609Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0e591d5af5c82ce260a3faa0a0b238a3990cf3c1ac2df9a0c02b56bf500a046b)
  **Repo:** - GitHub repository: `holbertonschool-web-development` - Directory:
  `css_advanced` - File: `styles.css` Please review your task manually with the
  following checklist
  [](https://intranet.hbtn.io/projects/2063#task-18774-carousel) `styles.css` is
  present [](https://intranet.hbtn.io/projects/2063#task-18774-carousel) Help
  **0/6** pts ### 6. FAQ mandatory Based on the
  [Figma](https://intranet.hbtn.io/rltoken/WcoJ5j4uynlWPJYDc1T2Iw "Figma") file,
  add the correct styling to the FAQ `section`
  ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/925cc37eab76934f55ba496627a1b39657dc141f.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230322%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230322T070609Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d5ce69aa2cc6f7323d503078da47e373c7ec834965d6fc9a691911674a458b89)
  **Repo:** - GitHub repository: `holbertonschool-web-development` - Directory:
  `css_advanced` - File: `styles.css` Please review your task manually with the
  following checklist
  [](https://intranet.hbtn.io/projects/2063#task-18775-carousel) `styles.css` is
  present [](https://intranet.hbtn.io/projects/2063#task-18775-carousel) Help
  **0/5** pts ### 7. Footer mandatory Based on the
  [Figma](https://intranet.hbtn.io/rltoken/WcoJ5j4uynlWPJYDc1T2Iw "Figma") file,
  add the correct styling to the `footer`
  ![](https://s3.eu-west-3.amazonaws.com/hbtn.intranet/uploads/medias/2021/4/90bf4d0180791e49a8656cdc617d1280c4ffe9bf.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIA4MYA5JM5DUTZGMZG%2F20230322%2Feu-west-3%2Fs3%2Faws4_request&X-Amz-Date=20230322T070609Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1f8a37452766c8022a8bef81106c6a0c87a25e889c7a4f02c69370aa3e77d88b)
  **Repo:** - GitHub repository: `holbertonschool-web-development` - Directory:
  `css_advanced` - File: `styles.css` Please review your task manually with the
  following checklist
  [](https://intranet.hbtn.io/projects/2063#task-18776-carousel) `styles.css` is
  present [](https://intranet.hbtn.io/projects/2063#task-18776-carousel) Help
  **0/6** pts ### 8. Make it live! mandatory Yes, you made it! You just finish to
  implement your first web page from a designer file, Congrats! It’s time to
  deploy it in Github, by using [Github
  Pages](https://intranet.hbtn.io/rltoken/bw-x7ITHhFxnm03gVIjiKw "Github Pages")
