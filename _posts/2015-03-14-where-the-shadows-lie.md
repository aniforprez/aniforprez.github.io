---
published: true
title: Where the shadows lie
layout: post
---
My TV show app is going nowhere. Far too busy to devote much time into it. I've decided the routes, the functionality and the API calls I'll have to make. I've decided on a general flow for the project, both in terms of UI and code. The Mean.js method of splitting the project into numerous files for modularity and clarity is commendable and I will imitate that flow but to a smaller extent. I won't be using a templating engine for one thing. Not too hot on those. They seem unnecessary especially when I'm already using Angular as an MVC framework.

So instead of that project, I'll talk a bit about my trip into the heart of Mordor. At least it was what it felt like to get this blog started with Jekyll.

I'd seen Github pages and felt it was a great way to host a simple blog. Honestly thought it would be pretty easy to set up. Nothing doing. Here's how it actually went down.

1. Try to download Ruby. Find out there's no Windows download on the official site.
2. Go to (rubyinstaller.org) and download the thing and install.
3. Try to install Jekyll with `gem install jekyll` only to throw an error for every single dependency. 
4. Confused, I search online to find out what the issue could be. Apparently, I am also supposed to install "Bundler". Installed with `gem install bundler`.
5. Drink about a litre of water after losing about the same amount through sweat when reading [this](http://blog.florianwolters.de/educational/2014/04/18/Running_Jekyll_with_GitHub_Pages_using_Windows_8.1_x64_and_Ruby_2.0_x64/) wall of text.
6. Creat Gemfile as instructed in step 5. Get some error.
7. Pick up hair on floor and glue it back to my head. Extensive Googling reveals Step 5 is utter lies. The line `source 'https://rubygems.org'` needs to be `source 'http://rubygems.org'`. Note the missing 's'.
8. Folowed steps 6-12 as per blog. Elated as balls about the fact that my blog is now locally hosted.
9. Find Github Pages doc that says that Github pages are automatically built online hence there si very little need to run local build with Jekyll.
10. Stare blankly at screen imagining how I could have spent the last 2 hours on better things.

Honestly, there is no point to going out of your way to install ruby and jekyll if you're going to use Github Pages. All the files can be made on your own and simply commited to the repo. All your work is done for you. The only disadvantage is the fact that you will not have a preview of your work before pushing it onto your final blog or site.

Wish someone had told me this earlier. Consider this a PSA.