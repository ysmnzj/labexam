---
layout: post
title: Lab Exam
featured-img: sleek
mathjax: true
---

# Getting started

[GitHub Pages](https://pages.github.com) can automatically generate and serve the website for you.
Let's say you have a username/organisation `my-org` and project `my-proj`; if you locate Jekyll source under `blog` folder of master branch in your repo `github.com/my-org/my-proj`, the website will be served on `my-org.github.io/my-proj`.

1. Just download or fork and clone the source from [github.com/janczizikow/sleek](https://github.com/janczizikow/sleek/).
2. Make sure your local machine has ruby and node
3. Edit site settings in  `_config.yml` file according to your project.
4. Replace `favicons` and `_includes/logo.svg` with your own logo.

**Note** that you might have to adjust some CSS depending on the width and height of your logo. You can find Header / Navigation related SCSS in `_sass/layout/nav.scss`.

## Writing content

### Posts

Create a new Markdown file such as `2017-01-13-my-post.md` in `_post` folder. Configure YAML Front Matter (stuff between `---`):

```yaml

---
layout: post # needs to be post
title: Lab Exam # title of your post
featured-img: sleek #optional - if you want you can include hero image
---

```

#### Lab exam
ما یادگرفتیم که با دیجنگو پروژه بسازیم، من برای تایپ هم خیلی تلاش کردم ولی موفق نشدم...
