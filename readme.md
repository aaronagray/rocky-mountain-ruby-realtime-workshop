## Outline

* Intro to Realtime
* Meteor
  * Demo
  * Install
  * Tutorial

* ActionCable
  * Demo
  * Install

## Meteor

### Objectives
* Install Meteor and related dependencies
* Build todo app
* Deploy app to the web
* Compile application for iOS

# ActionCable

ActionCable is a client and server side Rails library for real-time communication that combines websockets with Redis to manage resources. In a nit shell, it provides realtime application features familiar to chat, collaboration, and social applications.

## Objectives
* Install dependencies required to run Rails 5 ActionCable
* Demonstrate ActionCable from example app

### ActionCable Overview
* One Cable per session
  * In Rails, sockets are called cables.
  * One is opened for every session.
* Many Channels
  * Each Cable may have many channels.
  * A Channel is like a resource for sockets (comments, messages, location, etc.).
* Broadcasters
  * Sends data through specific channels

## The Stack
* Puma (see "Drifting Ruby: ActionCable Screencast" for alternative)
* Redis
* Websockets
