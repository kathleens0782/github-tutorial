# GitHub Tutorial

_by Kathleen Dawn Saloma_

---
## Git vs. GitHub

Y'know why Git and Github are great? Because you could get a glass of  
milk, someone could break your computer with a hammer in hopes of ruining  
your hopes and dreams while your not looking, and then you can be like  
"Sike, I saved my code."

What I'm saying is, Git and Github are important for saving code. You'll  
get it once you read this entire tutorial/guide.

**Git:**
*  Takes "screenshots" of the code
    *   Does _not_ require GitHub

Git is a program that is used to take "screenshots" of a Git   
directory (or code in the staging area) permanently for the programer.  
In other words, you like photography? Good, that's what it's like.

**GitHub:**
*  Stores information in a "cloud" 
    * (_ex.: The website [c9.io](https://c9.io)_)
    * _Does_ indeed require Git
    * This is great for storing code, instead of typing large amounts  
      of code only to lose it by accidently deleting it.

Github is a program that actually does save the code in a "cloud" for the programer ([Cloud9](https://c9.io)
being one of many "clouds"). This is great for someone who has tons of code, yet they want to make sure that  
they never have to worry about losing said code. Horray for being effiencent!

---
## Initial Setup
For the initial setup, it's a very easy  
setup. First make a workspace:

`mkdir workspace`

(Tip: Make sure to use `git init` to initialize the  
code for version control.)

Then you want to make a new folder within the folder,  
type:


`mkdir yourfilenamehere`

This will make a new folder in your workspace area. You  
may make as many folders as you please. This is faster,  
yet more complex way of making files. After you are done  
making the folders you want type a file in your folder  
(**NOTE: "cd" INTO THE FOLDER YOU WANT BEFORE MAKING A NEW  
FILE!!!**):

`touch filename.md`

You may type into the the file as much stuff as possible. Then you  
want to use `git add .` to commit the file. After all is said and done,  
you may finally start putting the code into the repository...

---
## Repository Setup

The Repository Setup is used to actually save the code  
in a cloud to prevent typing an entire page of code  
again. Almost all coders use GitHub to save their  
progress on a project.

To do this, first the person needs to make a "new repository"  
in their GitHub account. This is where the code will be saved.  

Next, there will be a url in the green button that says "Clone or   
Download." Click on the button and copy the url in the code. There  
will be two things to type:  

`git add remote origin URL`

(Tip: Make sure to use `git add .`)

After that, you want to push in the code,    
which you will use:

`git push`

After that, the code will be saved on a cloud. The coder can keep editing the files in the  
code, and can keep using `git push` to keep saving the changes. Furthermore, this is helpful  
if the person's computer breaks, burn, etc. This is how GitHub can and continues to be  
helpful.

---
## Workflow & Commands
**`git status`:** shows the progress of  
your code
* **!!!VERY IMPORTANT!!!**

**`git init`:**
initializes git in directory for version control

**`git add . `:** Adds files to the current directory

**`rm -rf .git`:** removes initalized code

**`cd`:** moves you to a folder

**`cd ..`:** moves you up a folder

**`ls`:** shows content in a directory

**`mkdir` and `rmdir`:** makes and removes directories

**`touch filename.md`:** makes a file

**Git used to remembering these (laugh I'm hilarious).** 

---
## Common Errors

There are many errors you can make while  
coding, and that's perfectly fine as long  
as you, the coder, are learning from your  
mistakes. Many examples include:

**Git Log:** Probably one of the most common error a  
coder has to go through, the solution here is  
simple! All you have to to is exit by pressing `q`.  
Yeah!

**Forgetting to use `cd`:** In this situation, you  
could be making a file, but you wonder why the file is  
outside of the intented folder. You forgot to `cd`  
into the folder before they made a new `touch` file.

**Misspellings and Mistakes:** So your coding your file, and  
your ready to save, only to find that your not in your workspace  
anymore. What happened? Well, it could've been that you accidently  
typed `stauts` instead of `status`, or you forgot to put a quotation  
mark at the end of your commit message. Don't panic though, you can always  
simply `cd` back into the directory and carfully type that code again.

**COMMIT, COMMIT, COMMIT!:** Your save your code with `git push`, and  
you expect to see the fruits of your labor on GitHub. However, you  
end up seeing that nothing changed! Now now, don't freak out, the world  
isn't ending anytime soon. You just forgot to make a **commit** message to your  
save. That's normal. Even I forget sometimes.

**Add:** _Nooo...I'm not typing this because **I** forgot to do this..._  
_T-totally not!_ I'm just saying, if you ever plan to make a commit message  
to your code, make sure it's initalized with `git add .` first. Just a bit  
of advice...




