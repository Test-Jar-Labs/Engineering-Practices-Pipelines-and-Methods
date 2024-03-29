
# Engineering-Practices-Pipelines-and-Methods
Some helpful links and guides for Test Jar Labs good engineering practices pipelines and methods

## General Engineering
### [Semantic Github Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
- https://www.conventionalcommits.org/en/v1.0.0/
```
feat: (new feature for the user, not a new feature for build script)
```
```
fix: (bug fix for the user, not a fix to a build script)
```
```
docs: (changes to the documentation)
```
```
style: (formatting, missing semi colons, etc; no production code change)
```
```
refactor: (refactoring production code, eg. renaming a variable)
```
```
test: (adding missing tests, refactoring tests; no production code change)
```
```
chore: (updating grunt tasks etc; no production code change)
```

### [Riot: Legends or Runeterra CI/CD Pipeline](https://technology.riotgames.com/news/legends-runeterra-cicd-pipeline)
- Using Git Lfs mono repo that contains 
- Game client code
- Game server code
- Game assets
- Build scripts
- Other tools
- Separate mono repo for micro services 
- Unity Game Engine
- CI/CD with Jenkins
- Infrastructure with AWS
- Issue tracking with Jira
- Internal Comms with Slack
- Hierarchical branch based workflow

### [MoveAI](https://www.move.ai/)
AI motion capture tool that allows you to create amazing mocap animations with just your phone. Can use just 1 camera and up to 6 of them for ultra accurate results. 

### [Playfab](https://playfab.com/)
Scalable gaming backend as a service. Has practically everything you need to publish and run a live game.

## Unity Specific
### [WEEB'S GUIDE TO PROGRAMMING IN UNITY](https://docs.google.com/document/d/1eTRYnxrII3b_vce9EytjGA7PU8HCLVjG8qCyW19kqcA/edit#heading=h.mh5w7xa88qmb)
Unity Engineering for Dummies Living Doc. Super good resource on good Unity engineering practices. 

### [Unity Cloud Build](https://unity.com/features/cloud-build)
- Automated Workflows
- Concurrent Builds
- Distribute everywhere
- iOS: Need access to mac at least once for certificates
- $9 dollars for teams up to 3 could be

### [Jenkins Pipeline for Unity iOS](https://cemayan.medium.com/jenkins-pipeline-for-unity-ios-7cf66b3608f)
- CI/CD Pipeline for Unity using Jenkins
- iOS

### [Unity + Git + LFS](https://thoughtbot.com/blog/how-to-git-with-unity)
- Add Unity-specific .gitignore settings
- Configure Unity for version control
- Use Git Large File Storage
- Unity Multiplayer
- https://docs-multiplayer.unity3d.com/

### Upgrading Unity Version
1. Make a commit with whatever source control software you're using.
2. Close the project
3. Open the project in a new version
4. Deal with any issues. There is probably none!

### [Unity Remote Config](https://docs.unity3d.com/Packages/com.unity.remote-config@1.4/manual/index.html)
Remote Config is a cloud service that lets you tune and customize your app over the air without requiring an update to your game.


### [Unity Assembly Definitions](https://www.youtube.com/watch?v=eovjb5xn8y0)
Speed up unity compile times.


### [Unity Domain Reloads](https://johnaustin.io/articles/2020/domain-reloads-in-unity#:~:text=Whenever%20you%20make%20a%20change%20in%20a%20Unity,are%20the%20bane%20of%20all%20large%20Unity%20projects)
5 second iteration times

### [Testing Unity Multiplayer Locally](https://docs-multiplayer.unity3d.com/docs/develop/tutorials/testing/testing_locally/index.html)
Guide covering the available workflows for testing multiplayer games locally. ParrelSync is the best one within editor. You can also build.

### [ParrelSync](https://github.com/VeriorPies/ParrelSync)
(Unity3D) Test multiplayer without building. Install the package

### [DoozyUI](https://doozyui.com/)
Fantastic UI Tooling to manage states, animations, and screens for complex UI. Includes a visual scripting state manager called Nody that allows our designers to create complex UI flows without having to code as much if any at all. 

### [Unity iOS Project Builder](https://www.pmbaty.com/iosbuildenv/documentation/unity.html)
Build iOS apps straight from your PC. No need to use your MacBook except the first time you set it up.

## Unreal Specific



















