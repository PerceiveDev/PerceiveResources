# Making a new project
To make a new project on our Jenkins (assuming you have moderator privileges or greater), first click new project:

![Step 1](https://github.com/PerceiveDev/PerceiveResources/raw/master/jenkins/new-project/step1.png)

Next, fill in the name and set the type to Freestyle project:

![Step 2](https://github.com/PerceiveDev/PerceiveResources/raw/master/jenkins/new-project/step2.png)

Fill in the description however you want. The convention of our team is to put the GitHub repo in the description:

![Step 3](https://github.com/PerceiveDev/PerceiveResources/raw/master/jenkins/new-project/step3.png)

Set the *Source Code Management* to Git and fill in the repository URL:

![Step 4](https://github.com/PerceiveDev/PerceiveResources/raw/master/jenkins/new-project/step1.png)

Set *Build Triggers* to *Poll SCM*, and set the schedule to `H/5 * * * *`:

![Step 5](https://github.com/PerceiveDev/PerceiveResources/raw/master/jenkins/new-project/step5.png)

Add a post-build action to save the JARs:

![Step 6](https://github.com/PerceiveDev/PerceiveResources/raw/master/jenkins/new-project/step6.png)

Finally, hit save:

![Step 7](https://github.com/PerceiveDev/PerceiveResources/raw/master/jenkins/new-project/step7.png)

Done!
