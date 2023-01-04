---
title: "Adventures in websiting"
date: 2022-12-30T03:50:53+01:00
draft: false
summary: "Some notes from my forays into very basic website design using Hugo"
---

Knowing that I was headed off on a bicycle ride, I wanted a way to keep friends and family apprised of my little victories and mishaps. So I set out to make a very basic website using [Hugo](https://gohugo.io/) for the framework and GitHub for hosting. 

* I first started with a simple write-up, the one shown [here](https://medium.com/@mahdix/build-your-own-website-hugo-github-pages-namecheap-4b3b0b781f29).
* I hadn't used git in quite some time and found many handy guides online, but this [one](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) worked best for me.
* Lastly, I set git up with some SSH keys and I hit the ground running!

I tried a few different readymade themes, tried modifying some, and then settled on a simple, straightforward one called [Archie](https://themes.gohugo.io/themes/archie/), which you're probably seeing here. I did change a few things around and I'm hoping that's ok under the MIT licensing scheme. More on fixing some of the customization issues [here](https://bwaycer.github.io/hugo_tutorial.hugo/themes/customizing/). Now, whenever I want to share something, I can write a post with the following commands. 

	$ hugo new posts/new-post-name.md
	$ hugo server
	
Then, I can work on that for a bit, get it all polished up and ready to go and then publish it using the following commands.

	$ git add .
	$ git commit -m "message here"
	$ git push

Maybe someone who uses git more regularly and together with others in a team is ready to point out some glaringly poor practice, but it seems to work for now. To keep my full-res photos off of github, I'll resize them using [IrfanView](https://www.irfanview.com/) while I look for a better way to host those. I think that about covers it. Thanks for reading this far, but this post was really just a test drive for myself ;)

P.S. I see there's also functionality for adding YouTube videos. My notes tell me this one was helpful.
{{< youtube psyz4UPnGAA >}}

I think most of the trouble I'm having is in the github hosting, which seems to 404 for a while after pushing my changes. [This](https://toughpixels.com/tips/loading-hugo-into-github-pages/) guide seems to address these two working together (or not) and I thought [this](https://rogerdudler.github.io/git-guide/) was a handy git cheatsheet. 