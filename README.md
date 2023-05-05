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
| `Beta 1.9` | - | - |
| `Beta 1.8.1` | - | - |
| `Beta 1.7.3` | - | - |
| `Beta 1.6.6` | - | - |

## **Installation**
### Client
- Install JRE or JDK version 6+
#### ***RECOMMENDED: [Azul Zulu](https://www.azul.com/downloads/)***
- Download the required release

- Unzip it to some folder
- If there is a start.bat file in the folder, start the game by opening this file. If there is no such file, open the JAR of the game

### Server
- At the moment, Charms is not available for servers, that's all I can say

## **Mod / Plugin Development**
### **Development**
#### **- Eclipse (Recommended)**
- Download  [Eclipse](https://www.eclipse.org)
- From the IDE selection menu, select **Eclipse IDE for java developers**
- Create a new workspace
- Create a new project using java version **JavaSE-1.8 (or JavaSE-1.6 if you want to create a mod for an older Java version)**
- Download the desired release and extract it to some folder


- Select your project, then in the top menu click **Project**, then **Properties**, then **Java Build Path**, then **Libraries,** then **Add External JARs**, and select the root JAR of the desired release, and click button **Apply And Close**. 
##### ***NOTE: The root JAR of a release, named after its type: charmscraft***
- Create a new class inherited from **tk.charms.mod.Mod** (or **tk.charms.plugin.Plugin** if you like create a plugin)
- Implements abstract methods **init** and **shutdown**
- Familiarize yourself with the documentation
- Create

### **Building**
#### **- Eclipse (Recommended)**
- In the top menu, click the **File** button, then **Export**, then expand the **Java** folder and select **JAR file**


- Select a directory to export
### **Necessarily**
- Create an **mod.json** file, and write the following lines there:
___
#### {
####    "mod_entry_point" : "here.your.mod.class",
####    "mod_name" : "here mod name",
####    "mod_version" : "here mod version",
####    "mod_icon_path" : "here mod icon path",
####    "mod_description" : "here your mod description (to go to the second line write \n)",
####    "allow_client" : true/false,
####    "allow_server" : true/false
#### }
___
- Copy some mod icon to mod **.jar** and write his image to **mod.json** property **mod_icon_path**
- Add all the files above that you have worked with to the archive of your finished JAR


- Congratulations, you have successfully made your mod or plugin! You can test it.
