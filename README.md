<h1 align="center">
  <img src=".github/logo.png" alt="Be The Hero - Mobile App" width="200px"><br>
  Be The Hero - Mobile App
</h1>

## Contents
* [Semana OmniStack 11.0](#semana-omnistack-11.0)
* [The Project](#the-project)
* [This repo](#this-repo)
  * [Layout](#layout)
  * [Techs and libs](#techs-and-libs)
  * [Requirements](#requirements)
  * [Download & Installation](#download--installation)
  * [Running](#running)
* [Backend App (API)](https://github.com/alande-amorim/be-the-hero-backend)
* [Web App](https://github.com/alande-amorim/be-the-hero-web)

---
## Semana OmniStack 11.0
<a href="https://rocketseat.com.br/"><img align="center" alt="RocketSeat" src=".github/rocketseat.svg" width="120px" /></a>

Semana OmniStack 11.0 is the 11th edition of the one week long time limited web course hosted by RocketSeat that took place from March 23, 2020 to March 29, 2020.
The goal of these series of lessons is to present a solid and complete stack based on Javascript (Node.js, ReactJS and React Native) and to build a cool little project.

## The Project
The proposed project for the Semana Omnistack 11.0 is a web app to help NGOs (non governmental organizations) finding people willing fund their social projects.
After signing up, the NGOs will be able to register social projects they are currently seeking help to fund.
Those projects will be available for the general audience on the mobile app.
A backend piece will serve both apps.

---
## This repo

This repo holds the source code for the React Native mobile application. It was developed with Expo and is integrated with the [restful API](https://github.com/alande-amorim/be-the-hero-backend).

### Layout


The UI for this app was provided by Rocketseat and is available at [Figma](http://figma.com/file/2C2yvw7jsCOGmaNUDftX9n/Be-The-Hero---OmniStack-11).

### Techs and libs
- Node.js
- Expo
- React Native
- Axios

### Requirements
- Node v12+
- Npm 6+
- Expo installed on your smartphone
- [Be the Hero API](https://github.com/alande-amorim/be-the-hero-backend)

### Download & Installation

Clone and install this repository.

```bash
$ git clone https://github.com/alande-amorim/be-the-hero-mobile.git
$ cd be-the-hero-mobile
$ npm install
```

### Running

In order to run this app you'll need a running instance of the [API](https://github.com/alande-amorim/be-the-hero-backend). If you haven't done it yet, do it now and come back.

This app is setup to reach the API on `http://localhost:3333`. If for any reason your server is running on a different host/port, you need to adjust. Edit the file `src/services/api.js` to meet your needs.

While the backend node process is running, you can launch the app:
```bash
$ npm start
```
Scan the QR Code with your phone's camera.

Your phone must be connected to the same network that the node instance for the mobile app is running.
