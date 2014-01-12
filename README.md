# Introduction

The purpose of this Hermod project is to define a high level framework to build very fast messaging applications where it's very easy to switch between serialization or publisher/subscriber implementations.


# Goals/Drivers

You can make an analogy with logger and SLF4J (API) / logback (Implementation)  for example.

This project aims to be an API and an Implemention for
* serialization,
* publish/subscribe concept.

The project will be firstly done on java but other bindings will follow :

* Java (JVM) binding,
* C# (CLR) binding,
* C++ (native) binding,
* Javascript (js engine) binding.

Our 3 drivers are:

* Performance,
* Interoperability (for both implementation and/or language),
* Low coupling between components.


# Subprojects

## Hermod Serialization (Serialization API and Implementations)
* [hermod-ser](https://github.com/hermod/hermod-ser) 
 
## Hermod Feed (Feed Publish/Subcribe API and Implementations)
* [hermod-feed](https://github.com/hermod/hermod-feed) 


# Hermod, what is the meaning ?

Hermod is the God of Speed and the Messager of the Gods in the norse mythology.
