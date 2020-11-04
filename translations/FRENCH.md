# [Contribuez sur ce projet](https://syknapse.github.io/Contribute-To-This-Project/)

[![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Contribute%20To%20This%20Project.%20An%20easy%20project%20for%20first-time%20contributors,%20with%20a%20full%20tutorial.%20By%20@Syknapse&url=https://github.com/Syknapse/Contribute-To-This-Project&hashtags=100DaysofCode 'Tweet this project')

> **Annonce:** Souhaitez-vous devenir un collaborateur de ce projet et contribuer à sa maintenance? Si vous êtes intéressé, envoyez-moi un DM sur [Twitter](https://twitter.com/Syknapse) et lisez le [guide du collaborateur](collaborator_guide.md).

## Introduction

Ceci est un tutoriel pour aider les nouveaux contributeurs à participer à un projet simple et facile.

### Objectifs

-   Contribuez à un projet open source.
-   Etre plus à l'aise dans l'utilisation de GitHub.

### À qui est-ce destiné ?

-   Ceci est pour les débutants absolus. Si vous savez comment écrire et modifier une balise **a** `<a href="" target=""></a>` alors vous devriez pouvoir le faire.
-   C'est pour ceux qui ont un peu plus d'expérience mais qui souhaitent apporter leur première contribution open source, ou obtenir plus de contributions pour plus d'expérience et de confiance.

### Pourquoi ai-je besoin de faire cela ?

Tout développeur Web, en herbe ou expérimenté, doit utiliser le contrôle de version de Git, et GitHub est le service d'hébergement Git le plus populaire utilisé par tout le monde. C'est aussi le cœur de la communauté Open Source. Se familiariser avec GitHub est une compétence essentielle. Contribuer à un projet renforce votre confiance et vous donne quelque chose à afficher sur votre profil GitHub.<br>
Si vous êtes un nouveau développeur et que vous vous demandez si vous avez besoin d'apprendre Git et GitHub, voici la réponse: [Vous auriez dû apprendre Git hier](https://codeburst.io/number-one-piece-of-advice-for-new-developers-ddd08abc8bfa 'Nouveau développeur ? Vous devriez avoir appris Git hier. par Brandon Morelli, créateur de CodeBurst.io').

## Que vais-je contribuer ?

![Contributor Card](/readme-only/card.PNG 'Contributor Card')

Vous allez contribuer une carte comme celle-ci sur ce [projet site web](https://syknapse.github.io/Contribute-To-This-Project/ 'https://syknapse.github.io/Contribute-To-This-Project'). Il comprendra votre nom, votre pseudo Twitter, une courte description et 3 liens vers des ressources utiles pour les développeurs Web que vous recommandez.

Vous allez faire une copie du modèle de carte dans le fichier HTML et le personnaliser avec vos propres informations.

## Index d'accès rapide

| <ul><li>[Introduction](#introduction)</li><li>[Que vais-je contribuer ?](#que-vais-je-contribuer-?)</li><li>[Setup](#setup)</li><li>[Contribuer &rightarrow;](#contribuer)</li><li>[Prochaines étapes](#prochaines-étapes)</li><li>[Remerciements](#remerciements)</li></ul> | Contribuer: <ul><li>[Step 1: Fork this repository](#step-1-fork-this-repository)</li><li>[Step 2: Clone the repository](#step-2-clone-the-repository)</li><li>[Step 3: Create a new branch](#step-3-create-a-new-branch)</li><li>[Step 4: Open the index.html file](#step-4-open-the-indexhtml-file)</li><li>[Step 5: Copy the card template](#step-5-copy-the-card-template)</li><li>[Step 6: Apply your changes](#step-6-apply-your-changes)</li><li>[Step 7: Commit your changes](#step-7-commit-your-changes)</li><li>[Step 8: Push your changes to GitHub](#step-8-push-your-changes-to-github)</li><li>[Step 9: Submit a PR](#step-9-submit-a-pr)</li><li>[Step 10: Celebrate!](#step-10-celebrate)</li></ul> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |


## Setup

First let's get setup to do the work

1. Login to your GitHub account. If you don't yet have an account then [join GitHub](https://github.com/join). I recommend that you do the [GitHub Hello World tutorial](https://guides.github.com/activities/hello-world/) before you continue.
1. Download [GitHub Desktop app](https://desktop.github.com/).
    - Alternatively if you are comfortable using Git on the command line you can do so (here's [first-contributions](https://github.com/Syknapse/first-contributions), a similar project that can serve as a guide for the commands needed). OR
    - If you use [VS Code](https://code.visualstudio.com/ 'Visual Studio Code website') it comes with integrated Git and allows you to do what we need straight from the editor.
    - However the simplest and easiest way to follow this tutorial is using GitHub Desktop.

Now that you are all setup let's get on with the business of contributing to the project.

---

---

## Contribuer

Become an open source contributor in 10 easy steps.

_Estimated time: Less than 30 minutes_.

### Step 1: Fork this repository

-   The objective here is to make a copy of this project and place it in your account.
-   A repository (repo) is how a project is called on GitHub and a fork is a copy of it.
-   Make sure you are on the [main page](https://github.com/Syknapse/Contribute-To-This-Project 'https://github.com/Syknapse/Contribute-To-This-Project') of this repo.

| <ul><li>Click on the _Fork_ button</li></ul> | ![Fork](readme-only/fork.PNG "click on 'Fork'") |
| :------------------------------------------- | ----------------------------------------------: |


-   You now have a complete copy of the project in your own account

---

### Step 2: Clone the repository

-   Now we want to make a local copy of the project. That is a copy saved on your own machine.
-   Open the GitHub desktop app. In the app:

| <ul><li>Click on _File_ then _Clone repository_</li></ul> | ![Clone](readme-only/clone.PNG 'click clone repository') |
| :-------------------------------------------------------- | -------------------------------------------------------: |


| <ul><li>You will see a list of your projects and forks on GitHub.</li><li>Select `<your-github-username>/Contribute-To-This-Project`.</li><li>Click _Clone_</li></ul> | ![Clone project](readme-only/clone-project.PNG 'click on <your-github-username>/Contribute-To-This-Project') |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------: |
| <ul><li>A forked project will have the fork symbol on the left.</li><li>Your fork will have your own GitHub user name.</li></ul>                                      |    ![your fork](readme-only/clone-your-fork.PNG 'your fork will look like this, with your own user name')    |

-   This will take a moment as the project is copied to your hard disk. I recommend that you keep the default path which is usually `..\Documents\GitHub`.
-   Now you have a local copy of the project.

---

### Step 3: Create a new branch

-   Once the repo has been cloned and you have it open in GitHub desktop it is time to create a new branch.
-   A branch is a way to keep your changes separate from the main part of the project called `Master`. For example if things go wrong and you are not happy with your changes you can simply delete the branch and the main project won't be affected.

| <ul><li>Click on _Current branch_</li><li>Then click on _New_</li></ul> | ![Create branch](readme-only/branch-new.PNG "Click on 'Branch', then 'New'") |
| :---------------------------------------------------------------------- | ---------------------------------------------------------------------------: |


| <ul><li>Give your branch a name</li><li>Click `Create branch`</li></ul> | ![Name branch](readme-only/branch-name.PNG 'Name your branch') |
| :---------------------------------------------------------------------- | -------------------------------------------------------------: |


-   You can name it whatever you want, but since this is a branch to add a card with your name to the project, calling it `your-name-card` is good practice because it keeps the intention of this branch clear.

| <ul><li>Publish your new branch to Github</li></ul> | ![Name branch](readme-only/branch-publish.PNG 'Click publish to send the new branch to your remote repo on GitHub') |
| :-------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------: |


-   Now you have created a new branch separate from the master.
-   For the next steps make sure you are working in this branch. You will see the name of the branch you are on at the top center of the GitHub desktop app where it says _Current branch_.

**Do NOT work on the `master` branch**

---

### Step 4: Open the index.html file

-   Now we need to open the file we are going to edit with your favourite code editor.
-   Find the project folder on your computer. If you have kept the default this should be something like `your-computer > Documents > GitHub > Contribute-To-This-Project`
-   The `index.html` file is directly in the `Contribute-To-This-Project` folder.

| <ul><li>Open your code editor (Sublime, VS Code, Atom..etc) and use the `Open file` command and locate the index.html file in the main directory of the project</li><li>Alternatively you can locate the file on your hard drive, right click, and open with your editor</li></ul> | ![Open index file](readme-only/index-open.PNG 'Open index.html in your text editor') |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------------------: |


-   Now you have the file you are going to edit open in your editor and you are ready to start making changes to it.

---

### Step 5: Copy the card template

-   We will make a copy of the card template to start working on it

| <ul><li>Scroll down towards the end of the file where you will find the section labelled `== TEMPLATE ==`</li><li>Copy everything within the red square in the image, from the `Contributor card START` comment to the `Contributor card END` comment</li></ul> |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Copy card template](readme-only/card-copy.PNG 'Copy the card template')                                                                                                                                                                                       |

| <ul><li>Paste the whole thing directly above the comment indicating it</li><li>Make sure there is a single line of space between your card start and the last card end. It's good practice to keep our code as clear as possible</li><li>Make sure your indentation is correct and matches the template</li></ul> |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Paste card template](readme-only/card-paste.PNG 'Paste above the indicated line')                                                                                                                                                                                                                               |

-   This now is **your** card for you to customise and edit.

---

### Step 6: Apply your changes

-   We will now start editing the html, changing the customizable fields in our card.

| <ul><li>Replace 'Name' with your name</li><li>Note: Don't change `class="name"`</li></ul> | ![Change name](readme-only/change-name.PNG 'Type your name') |
| :---------------------------------------------------------------------------------------- | -----------------------------------------------------------: |


| <ul><li>Insert the URL of your Twitter account `href="Insert URL here"`</li><li>Type your handle in the text field</li></ul> |
| :--------------------------------------------------------------------------------------------------------------------------- |
| ![Change contact](readme-only/change-contact.PNG 'Insert a link to your Twitter account and type your handle')               |

-   If you prefer to use a contact other than Twitter you will need to replace the twitter icon `<i class="fa fa-twitter"></i>` by going to [Font Awesome Icons](http://fontawesome.io/icons/) searching for the right icon and replacing only the `fa-twitter` part with the new icon like `fa-facebook` for example. Then Follow the same steps above.

| <ul><li>Tell us something about you</li><li>Keep it short and sweet. Think about it more like a tweet than a blog post</li></ul> | ![Change about](readme-only/change-about.PNG 'Write a sentence about you') |
| :------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------: |


| <ul><li>Share with the community 3 links to resources that are useful for web development</li><li>This can be anything, a video, a talk, a podcast, an article, a reference, or a tool</li><li>If you are a beginner don't be intimidated by this, share whatever you know even if you think it's basic. You'll be surprised how many people will benefit</li></ul> |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ![Change resources](readme-only/change-resources.PNG 'Insert link, write a short description, and type the name of the resource')                                                                                                                                                                                                                                   |
| <ul><li>Link: Insert the link `href="here"` replacing the `#`</li><li>Title: Write a brief description `title="here"`</li><li>Name: Write the resource's name in the text field `>here</a>`</li></ul>                                                                                                                                                               |

-   Make sure you have **saved all your changes**.
-   **Test your changes**. THIS IS IMPORTANT! Open the html file in your browser (by double clicking on it for example) and see what your card will look like on the site. See that the entire page still looks the same and nothing is broken. Click your links and make sure they are working. Open the console (Ctrl + Shift + J (Windows / Linux) or Cmd + Opt + J (Mac)) and check that there are no error messages.
-   Great, you have finished editing your code! The next steps will send your changes to GitHub and then submit them to be merged with the main project.

---

### Step 7: Commit your changes

-   Go back to the GitHub desktop app.
-   Your changes will have been added automatically to the staging area.
-   This means that Git has recorded all the **saved** changes.
-   You can see this reflected in the app. Everything you have added to the file will be in green, and deletions will show as red.

| <ul><li>The next step is called _Commit_</li><li>This roughly means "confirm the changes"</li></ul> | ![Commit changes](readme-only/commit.PNG "The changes you've added should appear in green on the right side of GitHub desktop app. The commit button is on the bottom left") |
| :-------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |


| <ul><li>This is what your GitHub desktop header should look like</li><li>Notice the fork symbol next to the project name in `Current repository`</li><li>Your `Current branch` will have the name you gave it in step 3</li></ul> |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Commit changes](readme-only/commit-header.PNG "The changes you've added should appear in green on the right side of GitHub desktop app. The commit button is on the bottom left")                                               |

| <ul><li>To _Commit_ you must fill in the _Summary_ field</li><li>This is the commit message explaining what you have changed</li><li>In this case "Added my card information" would be a reasonable message</li><li>Optionally you can add a more detailed _Description_</li><li>Click the _Commit_ button. Your button will say something like `Commit to "your-branch-name"`</li></ul> | ![Write commit message and commit](readme-only/commit-message.PNG "Write a brief commit message in the 'summary' input, and click 'commit'") |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------: |


---

### Step 8: Push your changes to GitHub

-   Your changes are now saved or committed. But they are saved only locally, that is on your computer.
-   Synchronizing local changes with your repository on Github is called a _Push_. You are "pushing" the changes from your local repository to the remote repository on Github.

| <ul><li>Click the _Push_ button</li></ul> | ![Push to GitHub](readme-only/push.PNG "Push your changes to GitHub, click on the 'Push' button") |
| :---------------------------------------- | ------------------------------------------------------------------------------------------------: |


-   After a few seconds the operation is complete and now you have exactly the same copy of this branch on your machine as well as on GitHub.

---

### Step 9: Submit a PR

-   This is the moment you have been waiting for; submitting a _Pull Request_ (PR).
-   So far all the work you have done has been on the fork of the project, which as you remember resides on your own account of GitHub.
-   Now it's time to send your changes to the main project to be merged with it.
-   This is called a [_Pull Request_](https://help.github.com/articles/about-pull-requests/ 'About Pull Requests - GitHub Help') because you are asking the original project maintainer to "pull" your changes into their project.
-   Go to the main page of **your fork** on GitHub (it will have the fork icon and your own user name at the top).
-   Towards the top of the repo you will see a highlighted pull request message with a green button.

| <ul><li>Click on the `Compare and pull request`</li></ul> | ![Submit a Pull Request](readme-only/pull-request.PNG 'This is usually towards the top of the page, under the description and above the project files and folders') |
| :-------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------: |


| <ul><li>This is what the `Open a pull request` page looks like.</li><li>REMEMBER _you are trying to merge your branch with the original project not with the `Master` branch on your fork_.</li><li>The image below gives you an idea of how the header of your pull request should look like.</li><li>On the left is the original project, followed by the master branch. On the right is your fork and the branch you created.</li></ul> |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![Open a Pull Request](readme-only/pull-request-branches.PNG 'You are requesting to merge your branch from your fork into the master branch of the original project')                                                                                                                                                                                                                                                                      |

| <ul><li>Create a pull request:</li><li>Write a title</li><li>Add optional information in the description</li><li>Click `Create pull request`</li></ul> | ![Submit a Pull Request](readme-only/pull-request-open.PNG "Click the green button. Don't be scared!") |
| :----------------------------------------------------------------------------------------------------------------------------------------------------- | -----------------------------------------------------------------------------------------------------: |


-   Don't be fazed by all the options. You only need to do these three steps for now.
-   Leave the option `Allow edits from maintainers` ticked.
-   Now, a _Pull Request_ will be sent to the project maintainer. As soon as it is reviewed and accepted your changes will appear on the [project web page](https://syknapse.github.io/Contribute-To-This-Project 'Contribute To This Project web page').

---

### Step 10: Celebrate!

That's it. You have done it! You have now contributed to open source on GitHub.

You have added code to a live web page: [https://syknapse.github.io/Contribute-To-This-Project](https://syknapse.github.io/Contribute-To-This-Project)

Your changes **won't be visible immediately**; first they have to be reviewed, accepted, and merged by the project maintainer. Once they are merged your card should be visible and live on the page.

It is very normal for a reviewer to ask for changes on a PR. Think of it as good practice if it happens to you. Keep an eye for comments and requested changes. Once you make the requested changes (back in your branch) all you have to do is to commit and push your changes. The PR will automatically update with the new changes.

I promise I will try to review and merge as soon as possible but I do this in my spare time, so a few days delay is inevitable.

---

---

## Prochaines étapes

-   Revenez dans un moment pour vérifier votre demande de Pull Request a été fusionnée.
-   Vous devriez recevoir un e-mail de GitHub lorsque vos modifications ont été approuvées ou si des modifications supplémentaires sont demandées. Et quand le PR est finalement fusionné avec la branche master et que votre carte a été ajoutée.
-   Si vous avez trouvé ce projet **utile** merci de lui donner un ⭐⭐⭐ en haut de la page et **Tweet** à ce sujet pour aider à faire passer le mot [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Contribute%20To%20This%20Project.%20An%20easy%20project%20for%20first-time%20contributors,%20with%20a%20full%20tutorial.%20By%20@Syknapse&url=https://github.com/Syknapse/Contribute-To-This-Project&hashtags=100DaysofCode 'Tweet this project')
-   Vous pouvez **me suivre** et me contacter [Twitter](https://twitter.com/Syknapse '@Syknapse') ou [en utilisant l'une de ces autres options](https://syknapse.github.io/Syk-Houdeib/#contact 'My contact section | Portfolio')
-   Il s'agit d'un projet open source, donc en plus de contribuer à votre carte, vous êtes invités à aider à corriger les bugs, les améliorations ou les nouvelles fonctionnalités. Ouvrez un [issue](https://help.github.com/articles/creating-an-issue/ 'Mastering Issues | GitHub Guides') ou envoyer un nouveau [pull request](https://help.github.com/articles/creating-a-pull-request-from-a-fork/ 'Creating a pull request from a fork | GitHub Help')
-   **Merci d'avoir contribué à ce projet**. Maintenant, vous pouvez aller de l'avant et essayer de contribuer à d'autres projets; Cherchez l'étiquette ![Good First Issue](https://user-images.githubusercontent.com/29199184/33852733-e23b7070-debb-11e7-907b-4e7a03aad436.png) pour les options de contribution adaptées aux débutants.
-   Je recherche également des collaborateurs pour me donner un coup de main dans la révision et la fusion des PR. Si vous souhaitez obtenir une pratique Git plus avancée, veuillez m'envoyer un DM sur Twitter et lire le [guide du collaborateur](collaborator_guide.md).

## Remerciements

Ce projet est fortement influencé par celui de [Roshan Jossey's](https://github.com/Roshanjossey), [first-contributions](https://github.com/Roshanjossey/first-contributions) un excellent tutoriel.

Il est également particulièrement inspiré par la grande communauté autour [#GoogleUdacityScholars](https://twitter.com/hashtag/GoogleUdacityScholars?src=hash) The Google Challenge Scholarship: Front-End Web Dev, promotion 2017 Europe.

## License

[MIT License](https://github.com/Syknapse/Contribute-To-This-Project/blob/master/LICENSE)

[Retour en haut &uparrow;](#introduction)
