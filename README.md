![Charms](./Images/Icon.jpg)
# Charms

Charms is simple ModLoader for old versions of Minecraft

## **Features**

- Convenient and easy to install mods
- Convenient and easy to create mods
- Wide and flexible library


- Everything is clear

## **Releases**

*Charms is currently supported on
### **Java Edition**
| Version | Client | Server |
|:-:|:-:|:-:|
| `Beta 1.6.6` | [Releases](https://github.com/MrOnran/Charms/releases/tag/MC-Beta-1.6.6/) | - |

## **Installation**
### Client
- Install JRE or JDK version 9+
- Download the required release
##### RECOMMENDED: [Azul Zulu](https://github.com/MrOnran/Charms/releases/tag/MC-Beta-1.6.6/](https://www.azul.com/downloads/)

- Unzip it to some folder
- If there is a start.bat file in the folder, start the game by opening this file. If there is no such file, open the JAR of the game

### Server
- At the moment, Charms is not available for servers, that's all I can say

## **Mod Development**
### **Development**
#### **- Eclipse (Recommended)**
- Download eclipse from https://www.eclipse.org
- From the IDE selection menu, select **Eclipse IDE for java developers**
- Create a new workspace
- Create a new project using java version **JavaSE-1.8**
- Download the desired release and extract it to some folder


- Select your project, then in the top menu click **Project**, then **Properties**, then **Java Build Path**, then **Libraries,** then **Add External JARS**, and select the root JAR of the desired release. 
##### ***NOTE: The root JAR of a release, named after its type: mc-(version) charms-(version)***
- Create a new class inherited from com.charms.mod.Mod
- Add standard methods onEnable and onDisable
- Familiarize yourself with the API ( which is not... )
- Create

### **Building**
#### **- Eclipse (Recommended)**
- In the top menu, click the **File** button, then **Export**, then expand the **Java** folder and select **JAR file**


- Select a directory to export
### **Necessarily**
- Create a **description.txt** file and write a description for your mod there


- Create an **info.yml** file, and write the following lines there:
___
#### name: name of your mod
#### main: main class in your mod
#### version: version of your mod
___
- Copy some image and rename it to **icon.png**
- Add all the files above that you have worked with to the archive of your finished JAR


- Congratulations, you have successfully made your mod! You can test it
