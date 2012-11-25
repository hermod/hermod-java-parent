hermod-java-parent
==================

hermod-java-parent


Introduction
=============

The purpose of this Hermod project is to define a high level framework to build very fast messaging applications where it's very easy to switch between serialization or publisher/subscriber implementation.
Drivers

You can make an analogy with logger and SLF4J for example.

This project aims to be an API for publish subscriber concept (included serialization).

Study will be done into Java but target should be

* Provide a DSL to provide a basic message builder (Mandatory).
* Java binding (mandatory).
* C++ binding.
* C# binding. 

Our 3 drivers are:

* Performance
* Interoperability (for both: implementation and or language)
* Low coupling between components. 


Sub-projets are

* hermod-ser-* (Serialization part)
* hermod-net-* (Network/protocol part)
* hermod-feed-* (Feed Publish/Subcribe *) 
              
Hermod, what is the meaning ?

Hermod is the God of Speed and the Messager of the Gods in the norse mythology.

[![Build Status](https://buildhive.cloudbees.com/job/hermod/job/hermod-java-parent/badge/icon)](https://buildhive.cloudbees.com/job/hermod/job/hermod-java-parent/)


The [maven site](https://buildhive.cloudbees.com/job/hermod/job/hermod-java-parent/site/) link.

