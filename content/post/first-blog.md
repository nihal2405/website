---
title: "First Blog"
date: 2022-10-07T21:05:05-05:00
tags: [blog]
---

### First Blog

* Create new branch for your blog

```
git checkout -b first-blog
```

* Move your branch to latest code from git

```
git fetch --all
git reset --hard origin/master
```

* Copy sample mark file

```
cp content/post/test-post.md content/post/first-blog.md
```

* Update title/tags/date
* Write some content

* Commit your changes

```
git add .
git commit -m "my first blog"
```

* Push your branch

```
git push origin first-blog
```

* Create PR
* Wait for approval