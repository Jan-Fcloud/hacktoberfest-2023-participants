# Hacktoberfest-2023-Participants
⭐ Take part in Hacktoberfest 2023 by adding yourself to this website and by contributing your own web projects ⭐

# How to participate:
Hello and welcome to Hacktoberfest 2023, I hope you are enjoying yourself!
To take part in this repository, you can do multiple things:
- Improve the design and features on the website itself.
- Add yourself to the "Contributors" tab. Link your GitHub profile and tell us a few things about yourself, and add a project to ./contributor-projects that you would love to share with others.
- Improve this documentation.

**(Additionally, if you could promote this to others so they can introduce themselves as well by leaving a star, that would mean a lot!)**

## How to add yourself as a Contributor:
It's very simple. All you have to do is find the commented out HTML template in **contributors.html**, which contains everything already prepared for you. All you have to do is change the link to your profile picture (it can be external or you can add it to the repo), change the name, link to your GitHub, add your picture in the assets folder and give path of picture in the 'src' section of image part and of course change the description.
Also, feel free to make your own custom CSS for your presentation, the more different styles, the better!

HTML snippet:
```html
<div class="hacktoberfesr-contributor">
   <a href="GITHUB LINK HERE" target="_blank">
      <img class="mobile-img" src="ICON LINK HERE" height="150" width="150">
      <div class="card">
         <img class="desktop-img" src="ICON LINK HERE" height="400" width="400">
         <div class="card-info">
            <h1 class="orange-gradient">YOUR NAME</h1>
            <p class="flex-gap-small sub-info">Lorem Ipsum<span class="icon-circle"> o </span>Lorem Ipsum<span class="icon-circle"> o </span>Lorem Ipsum</p>
            <div class="using">
               <h2>Software I use:</h2>
               <div class="using-list">
                  <p>Lorem Ipsum</p>
                  <p>Lorem Ipsum</p>
                  <p>Lorem Ipsum</p>
               </div>
               <h2>Things I've developed with so far:</h2>
               <div class="using-list">
                  <p>Lorem Ipsum</p>
                  <p>Lorem Ipsum</p>
                  <p>Lorem Ipsum</p>
               </div>
            </div>
         </div>
      </div>
   </a>
</div>
```

# Disclaimer for pull requests
Although making a pull request by adding your profile is simple, the above mentioned snippet is what I prompt you to do after adding onto the website itself. Why do I say this? **Because of the following rule of Hacktoberfest:**
```
Bad repositories will be excluded.

PR/MRs should be useful to maintainers. Repos that encourage simplistic PR/MRs (like adding a name or profile to a list or arbitrarily curating content) will be excluded from Hacktoberfest. Remember: quantity is fun, quality is key.
```
So even if your pull request does get accepted here, there is a chance that it won't be added onto your valid record of completed Pull Requests. I will be adding Issues here for Hacktoberfest features, so there will be less confusion when it comes to accepted tasks.

All the Issues will of course be here:
- https://github.com/Jan-Fcloud/hacktoberfest-2023-participants/issues


## Rules:
There are not many rules. The only things you'd have to follow are:
- Do not delete or alter any other people's work or presentation,
- Always make sure to sync this repo with your fork, because it can happen that someone might have commited changes right before you,
- No auto redirects and keep all links target="_blank",
- Pull requests shouldn't be considered as "spammy",
- Be kind and show respect to everyone!

After everything mentioned is done, I will check pull requests, add it to this repo and add the **hacktoberfest-accepted** label.

# That's it!
That's gonna do it for this explaination! Have fun and best of luck on your Hacktoberfest journey!
