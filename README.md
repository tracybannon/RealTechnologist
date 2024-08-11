# RealTechnologist
This is the source code for my personal website: tracybannon.tech

This repo uses a Hugo theme called "CleanWhite" from zhaohuabing.  It's clean, and elegant, but fully functional blog.

## Regular Setup

### 1. Setting up Hugo (this is for Windows 11)
 
 - Setting up HUGO:  https://www.jeremymorgan.com/tutorials/golang/how-to-hugo-windows-11/
 - Go installed and validated
   - ![image](https://github.com/tracybannon/RealTechnologist/assets/79816433/0767a815-bbc8-46ca-b268-f50cf6dfcfc3)
 - Instructions verified on August 20,2023 using "Installing the Binary (The Easy Way)"
   - https://gohugo.io/installation/windows/
   - hugo_extended_0.117.0_windows-amd64.zip
   - Hugo.exe placed in C:\Program Files\Go 


I need to figure out how to work this on a Mac
https://gohugo.io/getting-started/quick-start/
 
 ### 2. Cloning + Running Locally

  - Clone this repo via the command line `git clone https://github.com/tracybannon/RealTechnologist`

 - Start the Hugo sever & check it out:

   - `hugo server -D`
   - go to [http://localhost:1313/](http://localhost:1313/)

### 3. Commit and deploy

- This repo converts using gohugo.io  (https://gohugo.io/getting-started/quick-start/)
- When committed to GitHub, it will kick off pipeline established with netlify
- when commited change to GihHub, integration with Netlify 
- https://app.netlify.com/teams/

