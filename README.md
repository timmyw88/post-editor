# Post Editor

A small, private-ish editor for writing posts for my AI Notebook blog
(<https://timmyw88.github.io/ai-notebook/>).

Open it at **https://timmyw88.github.io/post-editor/**, or download `index.html` and double-click it.

1. Fill in the post details and write in Markdown (toolbar buttons insert prompt boxes, images, YouTube videos, tables…).
2. Click **Download .md** (or Ctrl+S).
3. Move the file into `content/posts/` in the blog repository, then commit and push.

- Everything runs in your browser. Nothing is sent anywhere, and the page can't change the blog.
- Your unfinished post is kept in this browser only (other visitors never see it).
- Image previews for `/images/...` paths load from the live blog, so new images show after you push them.
- Search engines are asked not to list this page (`noindex` + `robots.txt`).

A copy of this file also lives in the blog folder at `tools/post-editor.html` (git-ignored there).
