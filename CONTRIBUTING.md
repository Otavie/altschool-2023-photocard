# GUIDE TO ADD CONTRIBUTION

This a beginner level project for developers. It is also a good place to start if you want to go into Open Source Project.

#### _If you don't have git on your local machine, [install it](https://docs.github.com/en/get-started/quickstart/set-up-git)._

## 1) Fork this Repository

Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.

## 2) Clone the Repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone <copied-url>
```

where <copied-url> (without the lesser than and greater than signs <>) is the url to this repository (your fork of this project). See the previous steps to obtain the url.


## 3) Create a Branch

#### _Note: Make sure you have created a branch before you start working on the project._ <br />

Change to the forked repository directory on your computer by using:

```
cd altschool-2023-photocard
```

Now create a branch using the `git branch` command:

```
git branch <branch-name>
```

Then switch to the created branch using the `git branch` command:

```
git checkout <branch-name>
```

## 4) Make Necessary Changes and Commit those Changes
### Check out STEPS TO ADDING YOUR PHOTOCARD DETAILS below

Add those changes to the branch you just created using the `git add` command:

```
git add <file-name>
```
Now commit those changes using the `git commit` command:

```
git commit -m "Commit Message"
```

replacing `Commit Message` with your proper commit message.

## 5) Push Changes to GitHub

Push your changes using the command `git push`:

```
git push -u origin <branch-name>
```

replacing _<branch-name>_ with the name of the branch you created earlier.

## 6) Submit Your Changes for Review by Initiating a Pull Request (PR)

To initiate a pull request on GitHub, navigate to your repository and locate the `Compare & pull` request button. Simply click on this button to proceed with the pull request process.

Now submit the pull request.

## 7) Wait, for Response from the Reviewer
An email will be send to let you know if your request was accepted or rejected.


## How to Make the Necessary Changes (STEPS TO ADDING YOUR PHOTOCARD DETAILS)

After you have cloned the repository, to add your photocard details, take the following steps:

1. **Open index.html File:** Open the `index.html` file and locate the `<div class="photo-container">` section. Inside the `photo-container` div, locate the commented `photocard` div with sample information as shown below

```html
<div class="photocard">
    <div class="image-card">
        <img src="/img/<image-file-name>" alt="Your Name">
    </div>
    <div class="text-card">
        <div class="intro">
            <h3 class="student-name">First-Name Last Name</h3>
            <h4 class="student-stack">Your track e.g. Frontend Developer</h4>
        </div>
        <ul class="socials">
            <a href="link-to-your-github"><li class="social-item"><i class="fa-brands fa-github"></i> => smith-patrick</li></a>
            <a href="link-to-your-linkedin"><li class="social-item"><i class="fa-brands fa-linkedin"></i> => smith-patrick</li></a>
            <a href="link-to-your-twitter-account"><li class="social-item"><i class="fa-brands fa-twitter"></i> => smith-patrick</li></a>
            <a href="link-to-your-website. Put N/A if you don't have"><li class="social-item"><i class="fa-solid fa-globe"></i> => smith-patrick.com</li></a>
        </ul>
    </div>
</div>
```

2. **Copy and Paste:** Copy (without the comments) the Commented photocard div  from the opening `<div class="photocard">` to the closing `div` and paste it just above the commented div

3. **Replace Details:** Replace the sample data with your own image, name, specialization, and social media links.

#### Note: Your photo should be square shape preferably 500px by 500px
#### Note: Your photo should be be added to the img folder in the clone repository

4. **Add Social Media Links:** Customize the social media links in the `<ul class="socials">` section. Update the anchor (`<a>`) tags with your social media profiles or any other relevant links.

5. **Preview:** Open the `index.html` file in your web browser to preview your personalized photocard. Ensure that all details are accurate and the social media links are functioning correctly.

6. **Deploy:** Once you are satisfied with your photocard, you can deploy it to a web server or hosting service to share it with others.

7. **Add Your Name:** Add your name to the list of contributors by opening the [Contributors.md](https://github.com/Otavie/altshoolers-2023-photocard/blob/master/Contributors.md) file and adding your name with your GitHub username.

8. **STAR THE OPEN SOURCE REPO:**


### THANK YOU
Thank you for your contributions.

## Further Improvement

We welcome contributions from all AltSchoolers, Class of 2023! If you have ideas for improvements or additional features, feel free to raise an issue.

