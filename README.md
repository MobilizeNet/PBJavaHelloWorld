# PBJava

PBJava is a tool that understands your PowerBuilder application and converts it to a Java web application that uses frameworks such as Maven, Spring, Angular, CSS, and Typescript.

This tool has the ability to process the source code to generate Java, Angular, HTML, and CSS files. This Java web application can then be deployed in a Tomcat server with common standards of security, navigation, database interactions, and support when extending.

Instead of manually rewriting an entire application, we help you by automating this process using PBJava. This reduces costs, risks and time, while keeping the existing business logic intact.

For more details you can go to our [website](https://www.mobilize.net/powerbuilder) or check our documentation at https://docs.mobilize.net/



# PowerBuilder to Java (Java) Hello World Sample App

This repo contains the source code and binaries for the PBJavaHelloWorld app.

This app is just shows a Powerbuilder Window with a datawindow that implements a simple todo list.

The sample was migrated with our [tools](https://mobilize.net/powerbuilder) to a Spring Java application with an Angular FrontEnd.

You can see an screenshot of this repo on Safari on MAC OS

![PBMAPHelloWorld](./ScreenShot.png)


# How to Build

If you want to build this app:

- BackEnd: you can use the `./build.ps1` or `./build.sh` scripts
- FrontEnd: you can use the `./buildFrontEnd.ps1` or `./buildFrontEnd.sh`

# Code Structure

When you migrate your app from Powerbuilder to Java you will have 3 main folders:

- WebApp
- Target
- ReferenceApplication

For an overview of the migrated code see [Migrated Code Overview](https://docs.mobilize.net/PBJava/articles/migration/postmigrationprocess.html#migrated-code-overview)



## WebApp
Angular FrontEnd is inside this folder.

This folder is structured as:
- WebApp\sampleSite\sampleSite-angular
    - src
        - app
            - components\sample
                - d_sample_list
                - w_sample
    - wwwroot *(this is generated after Angular Compilation)*


## Target
The migrated powerbuilder code to java is inside this folder.

## ReferenceAppl
The project to generate the WAR is here.

# Running the app directly from your browser

If you do not want to install anything but still wnat to take a look at migrated application your can open the application using the links below:

[![Open in VS Code](https://img.shields.io/badge/Open%20in-VS%20Code-blue?logo=visualstudiocode)](https://vscode.dev/github/MobilizeNet/PBMAPJavaHelloWorld)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/MobilizeNet/PBMAPJavaHelloWorld)
[![Open in CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/embed/react-markdown-preview-co1mj?fontsize=14&hidenavigation=1&theme=dark)
[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/MobilizeNet/PBMAPJavaHelloWorld)
[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/MobilizeNet/PBMAPJavaHelloWorld?template=node&title=ngx-vcard%20Example)
[![Open in Repl.it](https://replit.com/badge/github/withastro/astro)](https://replit.com/github/MobilizeNet/PBMAPJavaHelloWorld)
[![Open in Glitch](https://img.shields.io/badge/Open%20in-Glitch-blue?logo=glitch)](https://glitch.com/edit/#!/import/github/MobilizeNet/PBMAPJavaHelloWorld)
[![Open in Codeanywhere](https://codeanywhere.com/img/open-in-codeanywhere-btn.svg)](https://app.codeanywhere.com/#https://github.com/MobilizeNet/PBMAPJavaHelloWorld)
