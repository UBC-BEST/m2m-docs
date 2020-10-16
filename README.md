# Setup 

We'll be using [Kotlin Multiplatform](https://kotlinlang.org/docs/reference/multiplatform.html) and [Unity](https://unity.com/) for our app, and Python and Javascript for our backend server code.  
If you have used Java before, don't stress out - Kotlin is basically the same thing, just nicer looking. You can read some of the [docs](https://kotlinlang.org/docs/reference/basic-syntax.html) so you can make sure I am not lying.      

Before you start any actual coding, you need to be familiar with a few concepts like CLI, Git, Server/Client Architecture and REST APIs. Luckily, you don't need to know them in depth, but just enough to be able to use them! Here's a few videos that'll help: 

- [Linux/Mac Terminal](https://www.youtube.com/watch?v=aKRYQsKR46I), [Windows Powershell](https://www.youtube.com/watch?v=j9wtAezZ9x0)
- [Git Crash Course](https://www.youtube.com/watch?v=SWYqp7iY_Tc)
- [Client Server Architecture](https://www.youtube.com/watch?v=h-n_gyyNly8)
- [REST API](https://www.youtube.com/watch?v=Q-BpqyOT3a8)
- [Using Postman](https://www.youtube.com/watch?v=juldrxDrSH0&list=PLhW3qG5bs-L-oT0GenwPLcJAPD_SiFK3C) - You don't need all of them, as long as you know how to make API Requests using Postman, you should be good. 

Follow the steps below to get started with both codebases on your local machines:  

## MAC Users

Congratulations, you got the easiest onboarding experience. 
- Install brew by copy-pasting this command in your terminal:  
`$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" `
- Now you can install Android Studio, Postman, node, git and python using one magical command:
  `brew cask install android-studio postman adoptopenjdk14 && brew install node python git`
- Once Android Studio is installed, follow the [Kotlin Setup](https://kotlinlang.org/docs/mobile/setup.html) to finish setting up your IDE. 
- You can also install VSCode if you are coding Python or Javascript, but not much setup should be needed: `brew cask install visual-studio-code `
- Login to Git locally, and try to clone this repository. You should be able to clone it sucessfully. 

## Linux Users

The commands below are for Ubuntu. You should change the commands if you are using another package manager. You may need to add a `sudo` prefix to the commands if they throw a permissions error. 
- You can install node, git and python using one magical command:
  `apt-get install adoptopenjdk14 nodejs python3 git`
- Install Android Studio, Postman and optionally VSCode by going to their website and following the installation instructions. 
- Once Android Studio is installed, follow the [Kotlin Setup](https://kotlinlang.org/docs/mobile/setup.html) to finish setting up your IDE. 


