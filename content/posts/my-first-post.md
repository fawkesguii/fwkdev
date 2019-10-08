---
title: "My First Post"
date: 2019-04-23T09:39:23+02:00
description: This is an introduction post to showcase Hugo.
slug: hello-world-my-first-post
categories:
- hugo
- blog
tags:
- helloworld
- hugo
- blog
draft: false
---

![](https://i.ytimg.com/vi/fPOSAfxhZLg/maxresdefault.jpg)

Hello world and welcome to my first post

## New Beginning
This is a new beginning on my blog on hugo and this seems pretty cool so im adding random text here because I dont know **what** to add here. So im adding a lot more random text here.
This is another test.

## Code
This is python code:
```python
from random import randint
from faker import Fake
randint(1, 2)
destFile = "largedataset-" + timestart + ".txt"
file_object = open(destFile,"a")
file_object.write("uuid" + "," + "username" + "," + "name" + "," + "country" + "\n")

def  create_names(fake):
	for x in  range(numberRuns):
		genUname = fake.slug()
		genName = fake.first_name()
		genCountry = fake.country()
	file_object.write(genUname + "," + genName + "," + genCountry +"\n")
```
This is bash code:
```bash

#!/usr/bin/env bash
var="ruan"
echo "Hello, ${var}"
```

## Tweets
This is one of my tweets, see [configuration](https://gohugo.io/content-management/shortcodes/#highlight) for more shortcodes:

## Tables
This is a table:
|**id** |**name**|**surname**|**age**| **city** |
|----------|--------|-----------|-------|--------------|
|20-1232091|ruan |bekker |32 |cape town |
|20-2531020|stefan |bester |32 |kroonstad |
|20-4835056|michael |le roux |35 |port elizabeth|

## Lists
This is a list:
* one
* two
*  [three](https://example.com)

This is another list:
1. one
2. two
3.  [three](https://example.com)

## Images
This is an embedded photo:
![](https://images.pexels.com/photos/248797/pexels-photo-248797.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500)

Run the Server

You can set the flags in your main config as well. Go ahead and run the server:
```bash
$ hugo server \
--baseURL "http://localhost/" \
--themesDir=themes --theme=pickles \
--bind=0.0.0.0 --port=8080 --appendPort=true \
--buildDrafts --watch --environment production
```

Screenshots

When you access your blog on port 8080 you should see your post. Some screenshots below:
image
image
image
image

References:
https://gohugo.io/getting-started/installing/
https://gohugo.io/content-management/syntax-highlighting/
https://willschenk.com/articles/2018/building-a-hugo-site/

Posted by Ruan Apr 23rd, 2019 11:41 am blog, golang, hugo

« Setup a Drone CICD Environment on Docker with LetsencryptUsing Drone CI to Build a Jekyll Site and Deploy to Docker Swarm »

Comments

Subscribe

Email Address:

Recent Posts

Running vs Code in Your Browser With Docker

Expire Objects in AWS S3 Automatically After 30 Days

Reindex Elasticsearch Indices With Logstash

Deploy a Monitoring Stack on Docker Swarm With Grafana and Prometheus

Deploy Traefik Using Bekker Stacks