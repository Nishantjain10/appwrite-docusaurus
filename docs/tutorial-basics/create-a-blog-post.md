---
sidebar_position: 3
---

# Create a Blog Post

Docusaurus creates a **page for each blog post**, but also a **blog index page**, a **tag system**, an **RSS** feed...

## Create your first Post

Create a file at `blog/2021-02-28-greetings.md`:

```md title="blog/2021-02-28-greetings.md"
---
slug: greetings
title: Greetings!
authors:
  - name: Matej Baco
    title: Software Engineer at Appwrite
    url: https://appwrite.io/blog/author/matej-baco
    image_url: https://appwrite.io/images/avatars/matej.png
    socials:
      github: meldiron
      x: _meldiron
      linkedin: matejbaco
  - name: Nishant Jain
    title: Integration Engineer at Appwrite
    url: https://www.appwrite.io/blog/author/nishant-jain
    image_url: https://www.appwrite.io/images/avatars/nishant.png
    socials:
      github: nishantjain10
      x: devnishant10
      linkedin: nishantj2002
tags: [greetings]
---

Congratulations, you have made your first post!

Feel free to play around and edit this post as much as you like.
```

A new blog post is now available at [http://localhost:3000/blog/greetings](http://localhost:3000/blog/greetings).