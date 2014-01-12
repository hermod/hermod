Introduction
=============

The purpose of this Hermod project is to define a high level framework to build very fast messaging applications where it's very easy to switch between serialization or publisher/subscriber implementations.

Goals/Drivers
=============

You can make an analogy with logger and SLF4J (API) / logback (Implementation)  for example.

This project aims to be an API and an Implemention for
* serialization,
* publish/subscribe concept.

The project will be firstly done on java but other bindings will follow :

* Java (JVM) binding,
* C# (CLR) binding (in progress),
* C++ (native) binding (TODO),
* Javascript (javascript engine) binding (potentatially TODO?).

Our 3 drivers are:

* Performance,
* Interoperability (for both: implementation and/or language),
* Low coupling between components. 

# Subprojets #

* [hermod-ser](https://github.com/hermod/hermod-ser) (Serialization API and Implementation)
* [hermod-feed](https://github.com/hermod/hermod-feed) (Feed Publish/Subcribe API and Implementation) 


Hermod, what is the meaning ?
=============================

Hermod is the God of Speed and the Messager of the Gods in the norse mythology.
