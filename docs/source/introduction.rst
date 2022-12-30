Introduction
=============
------------

The main goal of the Firefly framework is to provide a top-level 2D game API that comes with an in-build
Component-Entity-System architecture to organize all the game-objects, data and assets in a well-defined
form and helps a lot on keeping the game code-base as flexible as possible for changes.

Since almost everything in Firefly is a component, to create them is following always the very same principle with a
builder DSL while business-code stays in their System(s). This leads to more flexibility when content or behavior must
be changed or need to be extended.

Firefly also intent to be as less restrictive as possible to make it easy to extend functionality and integrate other
libraries. Firefly shall help you with that and not strain you with rigid conventions.

What is Firefly and Fly-Ko-Lib
------------------------------
------------

Firefly - Fly-Ko-Lib claims to be a top level game development library and API with a strong focus on 2D games.
Fly-Ko-Lib is entirely written in `Kotlin <https://kotlinlang.org/>`_ language and setup as a
`Koltin Multiplatform project <https://kotlinlang.org/docs/multiplatform.html>`_.
This means you can write your primary game code once and it will stay the same for all your target platforms. You have
only to deal with target platform specific coding for target specific adapters that are well abstracted within the
Fly-Ko-Lib API.

For example you can fist start with develop your game for the well supported desktop target (Win / Mac / Linux) and
bundle up and ship it for these platforms first. Make sure that all your main game code is written in pure Kotlin
without direct dependencies to JRE libraries ot other specific target libraries. This is easy possible if you follow
the simple Fly-Ko-Lib design and development principles as described in this documentation. Once you have your game-code
finished you can use or implement well abstracted target specific adapters to address your game from within the targets
runtime environment.

Firefly is for you if you're someone who likes to work with the code-first approach, meaning you prefer to use your
favorite IDE as the central tool for your game development process as opposed to an authoring-tool like Unity or Godot,
for example. So if you are such kind of game developer and also familiar with Kotlin or willingly to learn Kotlin for
game development, give it a try!

.. note::

    This documentation is not intended to teach you how to do Kotlin development. If you are interested in learning
    Kotlin we recommend to start with the `Kotlin Documentation <https://kotlinlang.org/docs/home.html>`_.



What is implemented
-------------------
------------

Since Fly-Ko-Lib is a Kotlin Multiplatform project in its early state, the question is, what is implemented so far
and ready to use and what needs to be tackled by yourself or will be provided in the future.

Currently (v0.3) only the JVM targets low level interfaces are fully implemented.
This means that you are able to package your game for all JVM targets that are mainly desktop (Win / Mac / Linux)
as well as Android and iOS with `RoboVM <https://github.com/MobiVM/robovm>`_.

.. note::

    Android and iOS with RoboVM has no particular application adapter implementations so far and was not tested.
    It should be easy possible to work with Android Studio and/or RoboVM Studio and Firefly JVM target projects
    to build a game for this two mobile device targets.

    We will provide you with adapter and documentation for this as soon as possible but for now you have to try
    yourself with that.

For desktop targets like Windows, Mac and Linux you can just start with your game development and are ready to go for
bundling and publishing your game for this platforms. Just start with the following chapter to setup a JVM based project.

Setting up an empty JVM based project as a start
------------------------------------------------------
------------

TODO

