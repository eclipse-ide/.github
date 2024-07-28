# Eclipse™ – the leading open platform for professional developers

![splash](https://raw.githubusercontent.com/eclipse-platform/eclipse.platform/master/platform/org.eclipse.platform/splash.png)

### WARNING
This page is currently under construction and will become the starting-point for everyone interested in the development of the Eclipse IDE,
including an exhaustive guide for contributors and information to find the right repository to report an issue.

---

Eclipse is the leading open platform for professional developers.

Eclipse is famous for being an _Integrated Development Environment_ (IDE) for the _Java_™ programming language but is also well capable of other languages like C/C++, JavaScript or TypeScript, to just name a few.
At its core Eclipse is a highly extensible platform and a comprehensive set of frameworks and common services that collectively provide a powerful software development infrastructure used for numerous free and open as well as for commercial products and applications.

This page is intended to be the start for everyone interested in contributing to the Eclipse IDE.
<br>
Users of the Eclipse IDE should start at: https://eclipseide.org/

## Developing and Contributing

Thank you for your interest in contributing to Eclipse. Contributions are more than welcome!

The [CONTRIBUTING](../CONTRIBUTING.md) section provides the information to guide you through the contribution process, after you have identified the project you want to contribute to.

## Structure of the Eclipse IDE and its eco-system

This section is intended to make you familiar with the general structure of Eclipse to help identifying the projects where you wants to report issues or contribute to.
To find the projects of your interested see the [Project Discovery Guide](../projects.md).

First of all there is not one single _Eclipse IDE_ or a single _Eclipse IDE_ project.
In general the _Eclipse IDE_ is organized into numerous independent _Eclipse projects_.
Each project can contribute multiple _components_ to an IDE.
The _components_ of Eclipse are called `Plug-ins` and are grouped into `Features`.

Most active projects release quarterly about the same time in a coordinated processes called the _Simultaneous Release_.

The [Eclipse Download page](https://www.eclipse.org/downloads/packages/) provides various predefined _Eclipse IDE Packages_, each of them bundling a different set of Features and Plug-ins from the corresponding SimRel.
Users can further customize their Eclipse IDE by installing more Features/Plug-ins from the [Simultaneous Release Repository](https://download.eclipse.org/releases/), the [Eclipse Marketplace](https://marketplace.eclipse.org/) or just any p2-Repository available for them.
Undesired Features can also be uninstalled.

## Community

The _Eclipse IDE_ is an _Eclipse Community project_ and as such obeys the governance rules described in the [Eclipse Development Process](https://www.eclipse.org/projects/dev_process/) to guarantee meritocracry, diversity, vendor-neutrality and business-friendliness.

Please bear in mind that the Eclipse IDE as a whole and the contributing projects are often developed by volunteers and the Eclipse IDE is not a product you contracted for.
As a result, the contributors may not be able to look into some support requests.
As per Eclipse Development Process, the committers are committed to review incoming code contributions though.
If you do not provide the fix/implementation yourself (or pay someone to do it for you), a bug you reported might never get fixed.
If it is a serious bug, other people than you might care enough to provide a fix.
As a consequence of all that, the only sure way to ensure some issue gets fixed or some feature gets implemented is that you contribute it yourself and convince some contributor that the change you submit is in the best interest of the project.

As you contribute more and more, you will eventually get nominated as a committer on the project.

## Technical and reference documentation

Comprehensive technical documentation of the different components can be found at
- https://help.eclipse.org/latest/index.jsp
