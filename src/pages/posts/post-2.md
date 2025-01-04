---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'astro mini guide for dummies'
pubDate: 2024-12-28
description: 'This is the second post of my new Astro blog.'
author: 'iggy'
image:
  url: 'https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Outdoors-man-meditation-relaxation-yoga-zen-calm-peace-479313.jpg/1280px-Outdoors-man-meditation-relaxation-yoga-zen-calm-peace-479313.jpg'
  alt: 'A person meditating'
tags: ["successes", "community"] 
---

## Reflecting on Success

December 29th, 2024 

### intro and new laptop

a few months ago, i was in singapore and my tech friend told me about astro. i was excited to try it! but, i didn't have a computer. luckily, i got a used laptop from a polish ngo who i volunteered for called "uwolnij złomka". it's a bit slow, but i'm so glad i can use it to learn.
[Uwolnij Złomka](https://uwolnijzlomka.org/)

### learning CS & website development

before singapore I started with some basic web development courses on W3Schools. I also watched MIT's free computer science lectures on YouTube to learn more about the theory behind coding.

W3Schools Online Web Tutorials
https://www.w3schools.com/
MIT OpenCourseWare | Free Online Course Materials 
https://ocw.mit.edu/

### own domain and github pages

i followed some online tutorials to build my website on Github Pages
https://www.w3schools.com/git/git_github_pages.asp
then i looked for domain which i decided to buy on porkbun.com 

then tried to connect with github pages, but it was still tricky for a beginner.

this guide helped a lot:
How to connect your domain to Github Pages - Porkbun Knowledge Base
https://kb.porkbun.com/article/64-how-to-connect-your-domain-to-github-pages

once it was connected i kept learning from youtube and asked lots of questions on different platforms: browser, chatgpt from OpenAI and gemini from google.

finally, i created a simple website! you can check it out here:  
https://web.archive.org/web/20241124224603/https://spol.ski/


### astro blog struggle

i really wanted to build a blog using astro, but my old laptop just couldn't handle it. every time i tried to run an astro project, it would completely crash and i'd have to restart the whole computer. it was so frustrating!
i tried using pre-made templates and watching tutorials, but my laptop kept dying on me. this video, for example, was really confusing, and i couldn't even get through it without my computer crashing: https://youtu.be/e-hTm5VmofI?si=VY_Lqx1myyN8tZP7


### change of browser

around christmas, a friend suggested i try a different browser. i switched to microsoft edge, and it's much faster than chrome or brave on my old laptop!
https://www.microsoft.com/en-us/edge/


### simple course
two days ago, i found a great astro tutorial: build your first astro blog
 https://docs.astro.build/en/tutorial/0-introduction/
it was a little confusing at first, but i got help from luis (a student from germany) on the astro discord.

### pushing on github

Meanwhile i le-learned git basics 
https://www.geeksforgeeks.org/what-is-git-push/
And it helped me to move the code to repo and track progress.

1. open the command prompt
2. go to project folder: 
cd "c:\users\visitor\onedrive\dokumenty\projektygithub\solar-spiral" 
(replace with your folder path)
3. add all changes: git add .
4. save changes with a message: git commit -m "my message"
5. send changes to github: git push origin main
6. if there's an error, i close the command prompt and try this first: 
   git fetch origin main
7. then try pushing again: git push origin main


### running my website locally

then when i tried to run my website on the local host command prompt command prompt was showing errors. With gemini help i discovered a way to run it on PowerShell. I’m posting it to past me or someone else if you have the same struggle to figure it out.

### search for powershell in windows.

1. right-click and "run as administrator".
2. enter your password if needed.
3. type: set-executionpolicy remotesigned -scope localmachine
 and press enter.
4. type: y 
and press enter.
5. go to your project folder: 
cd "c:\users\visitor\onedrive\dokumenty\projekty github\solar-spiral" (replace with your folder path)
6. type: npm run dev
7. wait a bit (especially if your laptop is slow).
8. copy the link from powershell (it should be:  "http://localhost:4321").
9. paste the link into your browser to see website

first version:
[iggy's website](https://web.archive.org/web/20241228121019/https://solarisproject.netlify.app/)
next, ⅔ of the course:
https://web.archive.org/web/20241228202825/https://solarisproject.netlify.app/

I saved it on netlify following the guide
https://docs.netlify.com/frameworks/astro/






