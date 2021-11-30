Make the iamge w=160 by h=150


# Complete Porfolio

This document showcases all projects that i have undertook. For the projects that was completed when a company there will only be a brief summary, on the otherhand other projects can be accessed in github. List of all the projects with tags to describe the project and/or my role in it is given below. 

| Project Title                                         | Descriptive Tags |
| -----------                                           | ----------- |
| [Trafic Light Fault Monitoring Board](#trafic-fault-detection)  | `Embedded`, `Software Design`, `Hardware Troubleshooting`, `PCB with Liligo Board`, `ESP8266 SoC` , `GSM` , `Wifi` , `Customer-driven` |
| [Motor Safty Control System](#Motor-safty)            |  `Embedded`, `Software Design`, `FRDM-KL25Z` , `Mbed Enabled Hardware`, `ARM Cortex M0+` , `Basic Assembly Language`|
| [Web and Native Application for Student Grouping Dashboard](#python-application)            |  `Python`, `Software Design`, `Native App:Qt`, `Web App:django`|
| [3 in a Row game in C++ using UnrealEnginge Script](#Unreal-Game)            |  `C++`, `Software Design`, `UnrealEngine`, `OOP`|
| [Snake game in C++ Using OpenGL](#c-snake-game)            |  `C++`, `Software Design`, `Game Dev`, `No game engine`, `OpenGL` , `GNU debug tool`|
| [Wireless Sensor Network Simulator](#wireless-sensor-network-simulator)            |  `Software Design`,`C`, `Parralle Programing`, `POSIX threads`, `MPI process`, `GDP debugging` , `GNU debug tool`|
| [Brushless DC motor control using Odrive](#bldc-control)            |  `ROS`,`Odrive`, `Designed a ROS node`, `Motor controlled was used in AV cart`|
| [External Keyboard PCB Design](#external-keyboard-pcb-design)            |  `Altium Designer`,`PCB layout`, `Atmega MCU`, `USB-powered`|
| [Developing API for ILI9320 Display to show QR codes](#developing-api-for-ilt9320-display-to-show-qr-codes)            |  `ILI9320 Display`,`Platform io`, `Arduino`|
| [Automatic Temperature Screening station using ESP32](#automatic-temperature-screening-station)            |  `ESP32`,`QR reader`, `platform io`, `GSM` , `working prototype designed`, `prototype was tested`|


## Trafic Fault Detection

## Motor Safty

## Python Application

## Unreal-Game

## C++ Snake Game

## Wireless Sensor Network Simulator

## BLDC Control

## External Keyboard PCB Design

This little guide demonstrates how to turn any [Github](http://github.com) repository with a bunch of [Markdown](https://en.wikipedia.org/wiki/Markdown) files into a simple website using [Github Pages](https://pages.github.com/) and [Jekyll](https://jekyllrb.com/).

* You don't need to use the command line or anything other than your browser.
* It doesn't require any knowledge in Jekyll.
* It's completely compatible with any bunch of markdown files you already have in any existing repository without any modification to those files. That includes the basic `README.md` almost all repositories contain.
* The markdown files will remain just as readable and usable in Github than in your website.

In fact this guide uses the same configuration and can be read both in Github and in Github Pages, at your preference:

* [Here is the link to the Github version](https://github.com/nicolas-van/easy-markdown-to-github-pages)
* [Here is the link to the Github Pages version](https://nicolas-van.github.io/easy-markdown-to-github-pages/)

## Step by step instructions

### Determine the repository where you want to activate Github Pages

You can of course create a new repository if you want.

### Create the `_config.yml` file

That file should be created on the root of your repository. Here is some content to copy-paste in it:

```yaml
plugins:
  - jekyll-relative-links
relative_links:
  enabled: true
  collections: true
include:
  - CONTRIBUTING.md
  - README.md
  - LICENSE.md
  - COPYING.md
  - CODE_OF_CONDUCT.md
  - CONTRIBUTING.md
  - ISSUE_TEMPLATE.md
  - PULL_REQUEST_TEMPLATE.md
```

It's basically just a few tuning of Github Pages' default configuration to have a better handling of Markdown files.

### Activate Github Pages in your repository configuration

On the Github page of your project go into `Settings > Options > Github Pages`:

![](./printscreen1.png)

In the `Source` option, select `master branch` then `Save`:

![](./printscreen2.png)

You must also choose a theme:

![](./printscreen3.png)

That's it! Now you can just use the link provided by Github to access your website:

![](./printscreen4.png)

## Usage guide

* Any markdown file in your repository will display in your Github Pages website. You just have to use the same path to access it and replace the `.md` extension by `.html`.
* To make links between your Markdown files just use a relative path to the other Markdown file. The configuration you copy pasted in your `_config.yml` provides a plugin to convert those URLs. So your Markdown files will have correct links both in Github and Github Pages.
* The index page of your website can be a `index.md` file or a `README.md` file. If both exists the `index.md` file has priority.
* You should be able to use any [Github Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

## Known differences between Github and Github Pages

* No automatic links with Github Pages. The Github Markdown renderer can automatically detect a simple copy-pasted link and make it a clickable link. Github Pages doesn't propose a feature to reproduce that behavior, so you'll have to braces your links with the `[]()` syntax.

## Recipes

Since the purpose of this guide is to demonstrate how to publish multiple Markdown files as a website but I don't have much more to say I will propose to you some delicious recipes instead:

* [Escalivada](./recipes/Escalivada.md)
* [Gazpacho](./recipes/Gazpacho.md)
* [Pasta all'amatriciana](./recipes/Pasta_all_amatriciana.md)

## Other Github Pages related projects

I'm a fan of Github Pages for the possibilities it offers to anyone to publish a website for free. I have multiple projects that could be of interest if that's your case too:

* [Bootstrap 4 Github Pages](https://nicolas-van.github.io/bootstrap-4-github-pages/)
* [Parcel Github Pages Boilerplate](https://github.com/nicolas-van/parcel-github-pages-boilerplate)

## Contributing

See the [Contribution Guide](./CONTRIBUTING.md).

## License

See the [License File](./LICENSE.md).
