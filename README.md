# Start-Up Guide
This repository serves as the basis for all MamaProducties projects. 

## First steps
1. Create a GitHub account.
2. Request access to the GitHub organization.
3. Install Sourcetree, GitHub Desktop, or Git Bash.
- [Sourcetree](https://www.sourcetreeapp.com/) (Recommended for developers)
- [GitHub Desktop](https://desktop.GitHub.com/) (Recommended for artists)
- [Git Bash](https://gitforwindows.org/) (Not Recommended, only for experienced Git Users)
- Other options are also good as long as they are free to use commercially.
4. (Optional) Set up SSH from the instructions listed [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh). Then add your SSH key to your GitHub account.
5. Create an Atlassian account.
6. Request access to the Jira boards for planning.
7. Create a Discord account.
8. Request access to the Discord server.

### Unity set-up
1. Install Visual Studio 2022       
Go to the [Visual Studio](https://visualstudio.microsoft.com/vs/) website, then download the Visual Studio 2022 Community edition. During installation, also select the Game development with Unity workload.

2. Install the format on save extension
Start up Visual Studio 2022, select Extensions/Manage Extensions in the toolbar. Fill in [Format on Save for VS2022](https://marketplace.visualstudio.com/items?itemName=WinstonFeng.VSFormatOnSave2022) in the search bar. Select the extension and install it.

3. Install Unity Hub    
Go to the [Unity](https://unity.com/download) website and download the version for your operating system.

4. Install a Unity version  
After installing the Unity Hub, we can now install a Unity version. To do so, open the Unity Hub and select Installs. Then select the latest Unity Version.
- Lumin Os Build Support (Required for Magic Leap Projects).
- Android Build Support (Required for Neuro Projects).

### Nest JS set-up 
1. Go to the [Visual Studio Code](https://code.visualstudio.com/) website and download and install the latest version of Visual Studio Code.
2. Go to the [Node.js](https://nodejs.org/en/) website and download and install the LTS version of Node.js.
3. Install [Typescript](https://www.typescriptlang.org/download) following the npm instructions from their website.  
4. Create an account for [npm](https://www.npmjs.com/).
5. Request access to the packages for the Nest projects.

# Developer instructions
## Git Strategy MaMa Productions?
### Commit strategy
Each commit should contain only a single new element. For example, when a
commit message requires an "and" it is generally advisable to rethink. Commit
messages are written in the Imperative Mood. For example, describe your change set as if you are giving instructions to the versioning system.

### Branching strategy
The branching strategy comprises a main branch and separate topic branches for individual feature development. Each topic branch is named with a prefix to indicate the type of topic. A "feature/" prefix indicates that the topic branch is for a new feature, while a "bugfix/" prefix indicates that the topic branch fixes an issue in the current main branch.

![Branching Strategy GIT](./Images/BranchingStrategy.png?raw=true "Branching Strategy GIT")

### Merging strategy
When a topic branch is functional and ready for development, create a pull
request on GitHub to merge it. Never merge or commit directly to the main
branch. After receiving at least one approval, you can merge your pull request
into the main branch.

## How to set up a project?
### Unity
0. Make sure you first finish the [start-up guide](##Start-up-Guide).
1. Create your GitHub Repository.
2. Clone the project.
3. Create a project using the Unity Hub.
4. Paste the contents of the Unity folder of the start-up repository into your project.
5. Follow the installation guide of Unity glTFast [here](https://discussions.unity.com/t/changing-the-pivot-point-of-meshes/144/6) to allow artists to send glb files. 

#### Neuro Feedback
1. Set up a Git submodule from the instructions [here](https://confluence.atlassian.com/sourcetreekb/adding-a-submodule-subtree-with-sourcetree-785332086.html) with the Neuro-Feedback-Essentials as the submodule.
2. Follow the Using the code in Unity in the README to get started.

### Nest
0. Ensure you first finish reading the [start-up guide](##Start-up-Guide).
1. Create your GitHub Repository.
2. Clone the project.
3. (Optional) The Nest.js base project can be cloned and copied to the project.
4. Paste the contents of the Nest folder of the start-up repository into your project.

### Magic Leap 
1. Follow the instructions for the [Unity start-up](###Unity-Start-Up), but when choosing the Unity version, select <strong>Unity 2020</strong>..
2. Create a Magic Leap Account on the [Magic Leap](https://ml1-developer.magicleap.com/en-us/home) website.
2. Follow the [Magic Leap Setup Guide](https://ml1-developer.magicleap.com/en-us/learn/guides/set-up-development-environment).
3. To set up the developer certificate, follow the [guide](https://ml1-developer.magicleap.com/en-us/learn/guides/developer-certificates). <strong>Important</strong> Your private key (.privkey) and certificate (.cert) files must always be in the same directory. Ensure that the file extension is .privkey for Windows. For MacOS, change the file extension to .privkey.key or key. 

4. Tip: When developing with the Magic Leap, always ensure that when not actively using the device, it is charging.
 
 ### Neuro Feedback
1. Follow the instructions for the [Unity start-up](###Unity-Start-Up), but when choosing the Unity version, select <strong>Unity 2017</strong>.
2. Ensure that the SSH connection is successful.


# Artist guidelines
## Export guide Blender
1. Select the objects you want to export (after applying rotation and scale)
2. Export > glTF 2.0 (.glb/.gltf)
3. Include > Selected objects
4. Transform > +Y Up
5. Geometry > Apply modifiers, UVs, Normals, Vertex colors, Materials > Export, Images > Automatic
6. Animation (in case of animations) > enable Animation (default settings)


## Blender cheat sheet
![Branching Strategy GIT](./Images/cheatsheet-blender.png?raw=true "Branching Strategy GIT")