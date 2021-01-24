---
title: "Sample Post"
date: 2020-08-29
author: Anonymous
categories:
tags: 
description: "Quick blurb"
draft: TRUE
type: "post"
---

Hello! This is a sample post to help you when publishing submissions.  </p>

## Instructions: </p>

1. In the "read" folder, click "Add file," then "Create new file."
2. Name your file using the following convention: "blog_title_yyyymmdd.md". Make sure you include ".md" at the end or it won't publish!!! Check out the name of this file for an example. 
3. Copy and paste the inputs above (everything in between the 3 hyphens) at the top of your new file, and edit accordingly. See "Inputs Tips" below for help on filling these in.
4. Copy and paste the content from the submission below the last 3 hyphens. See the rest of this file for formatting help. 
5. Once you're done, hit "Commit Changes" at the bottom of the page (no need to change any settings!) and you're all set :) 

Please message Robin if you need further help! 

## Inputs Tips: <br>
* title: If the submitter doesn't provide a title, just name it "Untitled". Make sure to put it in quotations.
* date: Use the date that you first commit the post, not the date you received it. Use the format yyyy-mm-dd.
* author: "Anonymous" for anybody who doesn't want their information shared.
* image : Use a photo from the submission. Default to "images/slider-bg2" if no image is shared. See "Formatting Tips" for how to add image content. Aim for a 2:1 aspect ratio and crop the original photo if necessary. 
* bg_image: Use a photo from the submission. Default to "images/slider-bg2.jpg" if no image is shared. See "Formatting Tips" for how to add image content.
* categories: List all formats included in the submission. Try to keep these categories consistent across posts-- check existing categories and use those before creating new ones. 
* tags: List all topics identified in the submission. Try to keep these tags consistent as well-- e.g. if the submitter tags their work as "Cuisine" but the "Food" tag already exists, then use "Food" instead. You can see all existing categories and submissions in the sidebar of the "Read" page. 
* description: Leave "" if not provided.
* draft: False allows everybody to see the post.
* type: Leave as "post".



## Formatting Tips <br>

### Images: </p>

1. Upload all your images to exampleSite/static/images/blog using the same name as your post. If you have multiple images associated with a post, add an underscore and a number to distinguish them (e.g. "sample_post_20200829_1", "sample_post_20200829_2", etc.) 
2. You can reference an image in the inputs by entering its path, e.g. "images/blog/sample_post_20200829.jpg".
3. You can embed images by using the below code. Update "width" to change the size of the image. 

<img src="/images/blog/sample_post_20200829.jpg" alt="Alt text" width="200"/>

### Videos: </p>

1. Upload the video to Youtube using the wirfeditors@gmail.com account.
2. From the link to the video, copy the text after "v=".
3. Paste the text into the below code where the current string (the R6SNtgQjyrU) is. 
4. Once you've committed changes to your post, update the description in the Youtube video to say "Read the full story from "Where I'm Really From" here:" and include the link to the new post. 

{{< youtube R6SNtgQjyrU >}}

### Audio:

Please note that only mp3 files are supported! If you received a different file, make sure to convert it first before following the below steps. </p>

1. Upload your audio to exampleSite/static/audio using the same name as your post. If you have multiple audio files associated with a post, add an underscore and a number to distinguish them (e.g. "sample_post_20200829_1", "sample_post_20200829_2", etc.)
2. You can embed audio by using the following code.

{{< audio mp3="/audio/sample_post_20200829.mp3" >}}
