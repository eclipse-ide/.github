# Eclipse® – The leading open platform for professional developers
<p align="center">
  <img src="https://raw.githubusercontent.com/eclipse-platform/eclipse.platform/master/platform/org.eclipse.platform/splash.png" alt="Eclipse splash"/>
</p>

<h2 align="center">This page is intended as starting point for contributions to <br/> the <em>Eclipse IDE</em> or <em>Rich Client Platform</em> (RCP) </h2>

Eclipse® is famous for being an _Integrated Development Environment_ (IDE) for the _Java®_ programming language but is also well capable of other languages like C/C++, JavaScript or TypeScript, to just name a few.
At its core Eclipse is a highly extensible platform and a comprehensive set of frameworks and common services that collectively provide a powerful software development infrastructure used for numerous free and open as well as for commercial products and applications.

## Development and Contributing

Thank you for your interest: contributions are more than welcome!

The [CONTRIBUTING](../CONTRIBUTING.md) section provides the information to guide you through the contribution process, after you have identified the project you want to contribute to.

Users of the Eclipse IDE should visit [eclipseide.org](https://eclipseide.org)

## Structure of the Eclipse IDE and its eco-system

This section aims to familiarise you with the general structure of _Eclipse_ to help you identifying the repositories you want to report issues or contribute to.
To find the projects of your interested see the [Project Discovery Guide](../projects.md).

First of all there is not one single _Eclipse IDE_ or a single _Eclipse IDE_ project.
In general the _Eclipse IDE_ is organized into numerous independent _Eclipse projects_.
Each project can contribute multiple _components_ to an IDE.
The _components_ of Eclipse are called `Plug-ins` and are grouped into `Features`.

Most active projects release quarterly at the same time in a coordinated processes called the _Simultaneous Release_.

The [Eclipse Download page](https://www.eclipse.org/downloads/packages/) provides various predefined _Eclipse IDE Packages_, each of them bundling a different set of Features and Plug-ins from the corresponding SimRel.
Users can further customize their Eclipse IDE by installing more Features/Plug-ins from the [Simultaneous Release Repository](https://download.eclipse.org/releases/), the [Eclipse Marketplace](https://marketplace.eclipse.org/) or just any p2-repository available to them.
Undesired Features can also be uninstalled.

#### Fundamental components

:globe_with_meridians: Eclipse-**Platform** contains the core code that powers Eclipse as a Rich Client Platform (RCP), which is used to build powerful desktop applications, no matter the type of app.

:computer: **JDT** is all about the tools for developing Java within the IDE, making Java development smooth and efficient. 

:arrows_counterclockwise: **EGit** provides all the tools needed to work with Git version control, essential for collaboration in open source projects. 

:electric_plug: **PDE** focuses on developing plug-ins for Eclipse, allowing users to extend its functionality in new and exciting ways. 

:hammer: **M2E** integrates the _Maven_ build tool into Eclipse, enabling seamless configuration and execution of Maven builds.

## Community

The _Eclipse IDE_ is an _Eclipse Community project_ and as such obeys the governance rules described in the [Eclipse Foundation Development Process](https://www.eclipse.org/projects/dev_process/) to guarantee meritocracy, diversity, vendor-neutrality and business-friendliness.

Please bear in mind that the Eclipse IDE as a whole and the contributing projects are often developed by volunteers and the Eclipse IDE is not a product you have contracted for.
As a result, the committers may not be able to take care of some support requests.
However, as part of the Eclipse Foundation development process, committers are committed to review incoming code contributions.
If you do not provide the fix/implementation yourself (or pay someone to do it for you), a bug you reported might never get fixed.
If it is a serious bug, other people than you might care enough to provide a fix.
As a consequence of all this, the only way to ensure that a bug gets fixed, or a feature gets implemented, is to contribute it yourself, and convince a committer that the change you are submitting is in the best interest of the project.

As you contribute more and more, you will eventually be nominated as a committer for the project.

## Contact

If you need more help: [![Assistance](https://img.shields.io/badge/Ask_for_assistance-red?style=for-the-badge&logo=eclipseide)](../help.md)

## Technical and reference documentation

Comprehensive technical documentation of the different components can be found at
- https://help.eclipse.org/latest/index.jsp
