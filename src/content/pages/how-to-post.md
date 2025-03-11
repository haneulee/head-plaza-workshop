---
title: How to Create a Post
description: A page that explains how to create a post on this website.
pubDate: 2025-03-03
---

Use posts to document experiments, work in progress, insights, or anything worth sharing with others or for future reference.

Create a post by adding a markdown file in your project folder, for example, `src/content/projects/YOUR-PROJECT/YOUR-POST.md`.

In addition to your regular text, you must add [frontmatter](https://jekyllrb.com/docs/front-matter/) at the beginning of the post for metadata.

```md
---
title: How to Create a Post
description: A page that explains how to create a post on this website.
pubDate: 2025-03-03
---
```

Use [Imgur](https://imgur.com/) to host images or video loops. Long-form videos should be hosted on dedicated platforms like [Vimeo](https://vimeo.com/).

<video src="https://i.imgur.com/LtRhnq9.mp4" muted inline autoplay loop></video>

Use regular HTML elements where markdown is not supported, for instance, to embed a 3D viewer from Sketchfab.

<div class="sketchfab-embed-wrapper w-full aspect-video bg-gray-50"> <iframe title="bh4" class="w-full h-full" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/4dda80925ba4455996c95886b708d910/embed"> </iframe> <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;"> <a href="https://sketchfab.com/3d-models/bh4-4dda80925ba4455996c95886b708d910?utm_medium=embed&utm_campaign=share-popup&utm_content=4dda80925ba4455996c95886b708d910" target="_blank" rel="nofollow" style="font-weight: bold; color: #1CAAD9;"> bh4 </a> by <a href="https://sketchfab.com/TiborUdvari?utm_medium=embed&utm_campaign=share-popup&utm_content=4dda80925ba4455996c95886b708d910" target="_blank" rel="nofollow" style="font-weight: bold; color: #1CAAD9;"> TiborUdvari </a> on <a href="https://sketchfab.com?utm_medium=embed&utm_campaign=share-popup&utm_content=4dda80925ba4455996c95886b708d910" target="_blank" rel="nofollow" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a></p></div>

Here is the Markdown that generates this example post:

~~~md
---
title: How to Create a Post
description: A page that explains how to create a post on this website.
pubDate: 2025-03-03
---

Use posts to document experiments, work in progress, insights, or anything worth sharing with others or for future reference.

Create a post by adding a markdown file in your project folder, for example, `src/content/projects/YOUR-PROJECT/YOUR-POST.md`.

In addition to your regular text, you must add [frontmatter](https://jekyllrb.com/docs/front-matter/) at the beginning of the post for metadata.

```md
---
title: How to Create a Post
description: A page that explains how to create a post on this website.
pubDate: 2025-03-03
---
```

Use [Imgur](https://imgur.com/) to host images or video loops. Long-form videos should be hosted on dedicated platforms like [Vimeo](https://vimeo.com/).

<video src="https://i.imgur.com/LtRhnq9.mp4" muted inline autoplay loop></video>

Use regular HTML elements where markdown is not supported, for instance, to embed a 3D viewer from Sketchfab.

<div class="sketchfab-embed-wrapper w-full aspect-video bg-gray-50"> <iframe title="bh4" class="w-full h-full" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share src="https://sketchfab.com/models/4dda80925ba4455996c95886b708d910/embed"> </iframe> <p style="font-size: 13px; font-weight: normal; margin: 5px; color: #4A4A4A;"> <a href="https://sketchfab.com/3d-models/bh4-4dda80925ba4455996c95886b708d910?utm_medium=embed&utm_campaign=share-popup&utm_content=4dda80925ba4455996c95886b708d910" target="_blank" rel="nofollow" style="font-weight: bold; color: #1CAAD9;"> bh4 </a> by <a href="https://sketchfab.com/TiborUdvari?utm_medium=embed&utm_campaign=share-popup&utm_content=4dda80925ba4455996c95886b708d910" target="_blank" rel="nofollow" style="font-weight: bold; color: #1CAAD9;"> TiborUdvari </a> on <a href="https://sketchfab.com?utm_medium=embed&utm_campaign=share-popup&utm_content=4dda80925ba4455996c95886b708d910" target="_blank" rel="nofollow" style="font-weight: bold; color: #1CAAD9;">Sketchfab</a></p></div>
~~~
