---
title: My image post
description: "In this page, we will explain what featured images are and show you some examples how to add a featured \
image for a page."
date: 2023-01-11
featured:
  url: thumbnail.jpg
  alt: A woman in front of her laptop with a dog
  caption: Working remotely
  credit: Unknown author
  previewOnly: false
---

Some content here.

Content pages in Hugo can have their images or any other files stored under the same directory of the page itself.
In Hugo's terms, it's called **page bundle** and allows us to keep all assets together with a page content file.

This theme uses [page bundles](https://gohugo.io/content-management/organization/#page-bundles) for featured images.
There are two main different ways to add a featured image.

### Option 1. Put `featured.*` or `thumbnail.*` image in the page bundle

This theme considers `featured` or `thumbnail` image in any popular graphic format in the root of the page bundle as
a featured image.

![Zoom meeting working from home](working-remotely-meeting.png)

Directory structure of this page:
