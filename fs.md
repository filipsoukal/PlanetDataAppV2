# Functional Specification - Planet Data App
### Version:
0.1
### Date created:
10.10. 2022
### Author:
Filip Soukal 4.C SSPŠ
### Contact:
soukal.filip.03@gmail.com
## 1.0 Introduction
### 1.1 Document Purpose
This document describes Planet Data App behaviour from the users perspective and a detailed overview of the softwares functions.
### 1.2 Document Conventions
The Solar System OpenData - Hereby refered to as Planet API, is a public available API from OpenData, that contains informations about space bodies in our solar.
system.
### 1.3 Targeted User Group
This app is targeted towards a mobile user, that is interested in interested in space and space related topics.
## 2.0 Scenarious
### 2.1 All Real Uses
This app servers as an educational tool about our solar system, it can be used in classroms or for personal education.
### 2.2 User Categories
Most user categories will be users looking for education on space. These may include: Space enthusiasts, Teachers, Students and Astronomy majors.
### 2.3 App features
The app will have a basic overview of space bodies in our solar system. Information about space bodies will be provided by the Planet API and distributed in
information panels.
### 2.4 Not Included features
The app won't contain the map of the solar system or Space object visualization.

## 3.0 Rough App Architecture
### 3.1 App-User Interaction
The user opens the app and is greated to a 3 button menu with these labels: Planets, Moons, Other Space Bodies. Upon selecting planets, the app will show buttons
with labels and pictures of the planets in our solar system. When user clicks the desired planet, the app will show a picture with basic information about the planet
and it's moons. The same goes for the moons button and other Space bodies button.
### 3.1 Main menu
The main menu will be 3 large borderless buttons with pictures of the group that the buttons lead to. First button will be planets, with a same name label and a picture of earth.
The second button will be the moon button, with a same name label and a Gayemede picture.
The last button will have a picture of Pluto and a label.
![This is an image](https://cdn.discordapp.com/attachments/782722785075265576/1036945460134416394/FSPHONE.png)
### 3.2 Space body sorting menu
This menu will appear after selecting a space body group. Here the user can select a space body, the want to know the information about. Each space body button will
have a picture and a label. The user can also sort the objects by mass, velocity, tempature, density.
### 3.3 Space body information panel
Here the user can learn about the space bodies through labels with information such as mass, velocity, density, distance from sun Etc.
