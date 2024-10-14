
Contributing to open source can seem intimidating at first, but don’t worry! Getting involved in the Eclipse projects is actually straightforward, and you’ll be working with an awesome community.

💻 **JDT** is all about the tools for developing Java within the IDE, making Java development smooth and efficient. 

🔄 **EGit** provides all the tools needed to work with Git version control, essential for collaboration in open source projects. 

🔌 **PDE** focuses on developing plugins for Eclipse, allowing users to extend its functionality in new and exciting ways. 

🌐 **Platform** contains the core code that powers Eclipse as a Rich Client Platform (RCP), which is used to build powerful desktop applications, no matter the type of app.

Each project is generally split into two parts: core (handling the internal logic) and ui (managing the user interface). Sometimes these are in separate repositories, and other times they are organized in different folders within the same repository. This makes it easier to understand the internal workings and how they are presented to users.

🎯 If you need to fix something in the user interface—whether it’s a dialog, view, perspective, or preferences page—you can easily find the Java class implementing the UI element. Just use the shortcut **Alt+Shift+F1** to instantly see the plugin containing the class, so you know exactly which project to work on.

📥 To start contributing, select the relevant setup file. This will fetch the code directly from GitHub, allowing you to create pull requests (PRs) or submit changes through GerritHub for EGit. You can consult the associated contribution guide listed in the table below. The whole process of getting the project ready happens through the setup file, so you’ve already done that in Step 1. After that, each project has its own contribution rules, but overall, they are similar and typically involve submitting your work via a Pull Request or a change on GerritHub.

🚀 You’ve got this! With the right tools and support, contributing to Eclipse is easier than you might think. Dive in and start making a difference!


| Project | Repository and Setup | Description | Contribution Page | 
|---------|------------|-------------|-------------------|
| **[Eclipse Platform](https://github.com/eclipse-platform)** |  | The global Eclipse Platform project [See more](https://projects.eclipse.org/projects/eclipse.platform) | [CONTRIBUTING.md](https://github.com/eclipse-platform/.github/blob/main/CONTRIBUTING.md) |
| | [eclipse.platform](https://github.com/eclipse-platform/eclipse.platform) | The repository with all the code that is not UI concerned | [Good First Issues](https://github.com/eclipse-platform/eclipse.platform/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) | 
| |  [eclipse.platform.ui](https://github.com/eclipse-platform/eclipse.platform.ui) ![Static Badge](https://img.shields.io/badge/setup-orange?style=plastic&link=https://raw.githubusercontent.com/eclipse-platform/eclipse.platform.ui/master/releng/org.eclipse.ui.releng/platformUIConfiguration.setup) | The UI of Eclipse  | [Good First Issues](https://github.com/eclipse-platform/eclipse.platform.ui/labels/good%20first%20issue) | 
| |  [eclipse.swt](https://github.com/eclipse-platform/eclipse.platform.swt) | The SWT library | [Good First Issues](https://github.com/eclipse-platform/eclipse.platform.swt/labels/good%20first%20issue)  |  
|  |  |  |  
| **[EGit](https://github.com/eclipse-egit/)** | |  The EGit project [See more](https://projects.eclipse.org/projects/technology.egit) | [EGit Contributor Guide](https://github.com/eclipse-egit/egit/wiki/Contributor-Guide) |  
| |  [egit](https://github.com/eclipse-egit/egit) | The eclipse git implementation  | [Good First Issues](https://github.com/eclipse-egit/egit/labels/good%20first%20issue)   |  
| |  [jgit](https://github.com/eclipse/jgit) | The java GIT API and implementation | [Good First Issues](https://github.com/eclipse-jgit/jgit/labels/good%20first%20issue) | 
|  |  |  | 
| **[JDT](https://github.com/eclipse-jdt/)** | The Java Development Tools project [See more](https://projects.eclipse.org/projects/eclipse.jdt) | [CONTRIBUTING.md](https://github.com/eclipse-jdt/.github/blob/main/CONTRIBUTING.md) | 
|  | [eclipse.jdt.core](https://github.com/eclipse-jdt/eclipse.jdt.core) | Non UI support to manage java code  | [Good First Issues](https://github.com/eclipse-jdt/eclipse.jdt.core/labels/good%20first%20issue) |  
|  | [eclipse.jdt.ui](https://github.com/eclipse-jdt/eclipse.jdt.ui) | UI Support for the JDT  | [Good First Issues](https://github.com/eclipse-jdt/eclipse.jdt.ui/labels/good%20first%20issue)  | 
|  | [eclipse.jdt.debug](https://github.com/eclipse-jdt/eclipse.jdt.debug) | Java debug support |  [Good First Issues](https://github.com/eclipse-jdt/eclipse.jdt.debug/labels/good%20first%20issue) | 
|  |  |  | 
| **[PDE](https://github.com/eclipse-pde)** |  | The Plug-in Development Environment Project [See more](https://projects.eclipse.org/projects/eclipse.pde) | [CONTRIBUTING.md](https://github.com/eclipse-pde/.github/blob/main/CONTRIBUTING.md) |   
|  | [eclipse.pde](https://github.com/eclipse-pde/eclipse.pde) | Models, builders, editors, views, and so on to facilitate plug-in development [See more](https://projects.eclipse.org/projects/eclipse.pde) | [All Good First Issues](https://github.com/issues?q=is%3Aopen+is%3Aissue+user%3Aeclipse-pde+archived%3Afalse++label%3A%22good+first+issue%22+) |  



