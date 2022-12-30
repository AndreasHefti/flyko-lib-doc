Setting up an empty JVM based project
-------------------------------------
------------

In this chapter we will setting up a simple JVM based Fly-Ko-Lib project with Intellij IDE for desktop targets like
Windows, Mac and Linux. This will give you a quick start to go directly into coding and a setup to learn and experiment
with the Fly-Ko-Lib just right away. So lets start directly with Intellij IDE and make sure you already have installed the Kotlin plugin on the latest version.


In your Intellij IDE go to the :guilabel:`File` menu, :guilabel:`New` and choose :guilabel:`Project`

.. figure:: /img/setup0.png
   :align: center

   Firefly JVM Project Setup

In the setup dialog select :guilabel:`Kotlin Multiplatform`. Name your project and use :guilabel:`Library` from the
Multiplatform section (or :guilabel:`Console Application` if you want to setup a desktop only project)
This guide will use :guilabel:`Gradle Kotlin` for building the project so we recommend to stick with that.
The JDK version here is not that important at the moment. Just stick with your favorite JDK version.

.. figure:: /img/setup01.png
   :align: center

   Firefly JVM Project Setup

Click next and remove the :guilabel:`js` and :guilabel:`native` target from the target list

.. figure:: /img/setup2.png
   :align: center

   Firefly JVM Project Setup

Then click on :guilabel:`Finish` To create the empty project. You should get something like the following:

.. figure:: /img/setup3.png
   :align: center

   Firefly JVM Project Setup


