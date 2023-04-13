---
layout: post
title: a post about the blender python api
date: 2023-04-13 11:59:00-0400
description: an example of a blog post with giscus comments
categories: sample-posts external-services
giscus_comments: true
related_posts: false
---

This post is just a reminder of basic bpy (blender python) functions
and how to use them.

```markdown
> > > bpy.data.scenes
> > > <bpy_collection[1], BlendDataScenes>
```

<div class="post_img_23-04-14">
    {% include figure.html path="assets/img/post_20230414_scene.PNG" class="img-fluid rounded z-depth-1" zoomable=true %}
</div>

# Access the scenes

# Access the objects in a Scene

> > > bpy.data.objects
> > > <bpy_collection[5], BlendDataObjects>

## Access objects by name (check image)

> > > bpy.data.objects['Barrel']
> > > bpy.data.objects['Barrel']

# https://federicoarenasl.github.io/Data-Generation-with-Blender/

# Access and modify information of objects

> > > bpy.data.objects['Camera.001'].rotation_euler[0] = 0
