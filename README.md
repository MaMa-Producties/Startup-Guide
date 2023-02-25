# Start-Up Guide
This repository is the basis for any project for MamaProducties. 

## How to set up a project?
### Unity
0. Make sure you first finish the [start-up guide](##Start-up-Guide).
1. Create your GitHub Repository.
2. Clone the project.
3. Create a project using the Unity Hub.
4. Paste the contents of the Unity folder of the start-up repository into your project.

#### Neuro Feedback
1. Set up a Git submodule from the instructions [here](https://confluence.atlassian.com/sourcetreekb/adding-a-submodule-subtree-with-sourcetree-785332086.html) with the Neuro-Feedback-Essentials as the submodule.
2. Follow the Using the code in Unity in the README to get started.

## Nest
0. Make sure you first finish the [start-up guide](##Start-up-Guide).
1. Create your GitHub Repository.
2. Clone the project.
3. (Optional) The Nest Js base project can be cloned and copied to the project.
4. Paste the contents of the Nest folder of the start-up repository into your project.

## Start-up Guide
1. Create a GitHub account.
2. Request access to the GitHub organization.
3. Install Sourcetree, GitHub Desktop, or Git bash.
- [Sourcetree](https://www.sourcetreeapp.com/) (Recommended for developers)
- [GitHub Desktop](https://desktop.GitHub .com/) (Recommended for artists)
- [Git Bash](https://gitforwindows.org/) (Not Recommended only for experienced Git Users)
- Other options are also good as long as they are free to use commercially.
4. (Optional) Set up SSH from the instructions listed [here](https://support.atlassian.com/bitbucket-cloud/docs/set-up-personal-ssh-keys-on-windows/). Then add your SSH key to your GitHub account.
5. Create an Atlassian account.
6. Request access to the Jira boards for planning.
7. Create a Discord account.
8. Request access to the Discord server.

### Unity start-up
1. Install Visual Studio 2022       
Go to the [Visual Studio](https://visualstudio.microsoft.com/vs/) website, then download the Visual Studio 2022 Community edition. During installation, also select the Game development with Unity workload.

2. Install the format on save extension
Start-up Visual Studio 2022, select Extensions/Manage Extensions in the toolbar. Fill in Format on Save for VS2022 in the search bar. Select the extension and install it.

3. Install Unity Hub    
Go to the [Unity](https://unity.com/download) website and download the version for your operating system.

4. Install a Unity version  
After installing the Unity Hub, we can now install a Unity version. To do so, open the Unity Hub and select Installs. Then select the latest Unity Version.
- Lumin Os Build Support (Required for Magic Leap Projects).
- Android Build Support (Required for Neuro Projects).

### Nest JS start-up 
1. Go to the [Visual Studio Code](https://code.visualstudio.com/) website and download and install the latest version of Visual Studio Code.
2. Go to the [Node Js](https://nodejs.org/en/) website and download and install the LTS version of Node Js.
3. Install [Typescript](https://www.typescriptlang.org/download) following the npm instructions from their website.  
4. Create an account for [npm](https://www.npmjs.com/).
5. Request access to the packages for the Nest projects.

### Magic Leap 
1. Follow the instructions for the [Unity start-up](###Unity-Start-Up).
2. Create a Magic Leap Account on the [Magic Leap](https://ml1-developer.magicleap.com/en-us/home) website.
2. Follow the [Magic Leap Setup Guide](https://ml1-developer.magicleap.com/en-us/learn/guides/set-up-development-environment).
3. To set up the developer certificate, follow the [guide](https://ml1-developer.magicleap.com/en-us/learn/guides/developer-certificates). <strong>Important</strong> Your private key (.privkey) and certificate (.cert) files must always be in the same directory. For MacOS may change the file extension to .privkey.key or key. Ensure that the file extension is .privkey.

4. Tip, when developing with the Magic Leap, always make sure that when not actively using the device,it is charging.
 
 ### Neuro Feedback
1. Follow the instructions for the [Unity start-up](###Unity-Start-Up), but when choosing the Unity version, select <strong>Unity 2017</strong>.
2. Make sure that the SSH connection is successful.
