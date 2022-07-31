![Website Front Cover](images/Screenshot%202022-07-29%20at%2015.12.57.png)

## Katie's

This website is for a self employed beauty therapist who offers luxury & spa treatments. Katie's is based in Carnoustie, Scotland. On this site you can see the services that Katie provides, and you can book an appointment using the form on the front page. If you need to find contact Katie you'll see her details at the bottom of the page, or you can use her social media links.

------

## Features

- Navigation Logo

  ![Navigation](images/Screenshot%202022-07-31%20at%2009.48.24.png)

  - This logo is on all pages. This logo will allow the user to navigate back to the home page instead of having to go back.

- Pages 

![[Pages](images/Screenshot%202022-07-31%20at%2009.45.10.png)

- You can access the three pages by clicking on their box. 

- Services 

![Services](images/Screenshot%202022-07-31%20at%2010.53.03.png)

- On this page is where you'll find information about the services provided by Katie. You can see the prices and how long each treatment takes. 
- This page will be updated if any changes are needed to keep the user up to date.


- About us

![About](images/Screenshot%202022-07-31%20at%2010.02.40.png)

- This page describes a little bit about Katie's.

- Gallery


- The Gallery page shows treatments that have been provided by Katie. The user can see the quality of treatments provided and can choose which one they would prefer.

- Treatment Form

![Form](images/Screenshot%202022-07-31%20at%2010.06.42.png)

- The user can use this form to sign up for a treatment. The user can choose which treatment they want and Katie will be alerted. The form doesn't send any information, but my future plans are to fix this.

- Location

![Map](images/Screenshot%202022-07-31%20at%2010.10.11.png)

- The user can see the location on a map. The user can use this if lost, or can type in the address to find the location of Katies.

- The Footer

![Footer](images/Screenshot%202022-07-31%20at%2010.12.21.png)

- This section includes contact details and social media links. When you click on the social media links this will take you to Katie's social media sites.

## Featues Left to Implement

- Make the website more centre.
- Fix the treatment form


------

## Testing

## Validator Testing

-  HTML
 - When passing through W3C Validator, I had 4 errors.

 ![HTML](images/Screenshot%202022-07-31%20at%2010.21.34.png)

 All errors are on the iframe element. I fixed these errors by following the advice provided on W3C Validator.

- CSS

- No errors were found.

- Lighthouse
  ![Lighthouse](images/Screenshot%202022-07-29%20at%2013.37.29.png)


## Bugs

1. I had to edit margins for smaller screens. 
2. When I deployed my site on GitHub the logo and map wasn't responsive. I had to change the file paths by removing ./ from the start. 
3. My form wouldn't stay to the left so I had to fix my margins.
4. The footer wouldn't stay at the bottom of my screen. I fixed this by adding bottom:0. 

------

## Deployment

This site was deployed to GitHub pages.

Live link - 

------

## Credits

- The code for the social media links was taken from Love Running Project.
- Idea for map was from Coders Coffeehouse
- Social Media icons from Font Awesome.
- Font used from Google Fonts.

## Media

- The logo is from Katie's Facebook page.
- Images for pages are from google.
- Gallery is from Katie's Facebook page.




 



**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
