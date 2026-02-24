How to update:

Open GitHub Desktop
Open Cursor
Edit HTML or CSS files

To add blog posts:


📝 Blog Maintenance Guide
This blog runs on Jekyll. You don't need to code new HTML pages for every entry; you just write in Markdown, and the site builds itself.

🚀 How to Add a New Post
Go to the _posts/ folder.

Create a new file. The filename must follow this exact format:

YYYY-MM-DD-title-of-your-post.md

(Example: 2026-02-24-my-first-trip.md)

Add the "Front Matter" at the very top of the file:

Markdown
---
layout: default
title: "Your Post Title Here"
---
Write your content below the second --- using Markdown.

🖼️ Adding Images
Upload your image file to the assets/images/ folder.

Embed it in your post using this line:
![Describe the photo]({{ site.baseurl }}/assets/images/your-image.jpg)

✍️ Markdown Cheat Sheet
Instead of HTML tags, use these simple shortcuts:

# Heading 1 (Main Title)

## Heading 2 (Sub-section)

**Bold Text**

* Bulleted List Item

[Clickable Link Text](https://google.com)

🔄 How the Site Updates
Save & Push: Once you commit and push your changes to GitHub, the "Actions" tab will automatically start building your site.

Automatic Listing: The new post will automatically appear on your homepage list. You never have to update the homepage manually.

Global Changes: To change the header, footer, or menu, edit _layouts/default.html. It will update every single blog post at once.
