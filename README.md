# Abulafia's manim utils and tricks

These are links to my public gists providing my solutions to common problems I faced using manim. Some of them are in response to other users requests too.

## Generic tricks

* [Light theme for manim](https://gist.github.com/abul4fia/353b9a2c3d000088a82175fa64e0ce24). Import this and have your animation using white background and black text/lines.

* [Concise syntax for manim's ValueTrackers](https://gist.github.com/abul4fia/5115dbb660ad4414cb5568d6870801c0).
A little trick to shorten the syntax for assigning or getting values from ValueTrackers.

* [How Animation works (more or less)](https://gist.github.com/abul4fia/4537d5f257152b7980de4a50bda2cf53).
A brief explanation of how manim's animations work under the hood, which may be useful to extend them or program your own ones.

* [Manim's transforms](https://gist.github.com/abul4fia/a18ee1f701ba960c56ac6ed6f6246a55).
Summary of differences between `Transform`, `ReplacementTransform` and `TransformFromCopy`.

* [Working with sections in manim](https://gist.github.com/abul4fia/47a375c8899dd830ce17df5c48b388bd).
How to structure a long animation script to make easier to work with it.


## Beyond AnimationGroup

* [Generic sequences of animations run in parallel](https://gist.github.com/abul4fia/ce6a2a543ba6aaf586f60aefb3be3563).
Allows to create a list of animations that can be "triggered" to run in background, while other animations are running.

* [Play animations in given timeline](https://gist.github.com/abul4fia/edda4f8d46f00b88371882cbaa01f2d0). 
This one has been converted in an official manim plugin, i.e. you can `pip install manim-play-timeline`. The repo for it is [here](https://github.com/abul4fia/manim-play-timeline)

## Helpers for deal with text and code objects

* [Finding shapes in TeX mobjects](https://gist.github.com/abul4fia/3bbe8e0c1d19a007cad035bb8be90387).
Generic set of functions to find a particular sequence of glyphs (symbols) in a tex mobject, which can be used to change their appearance, or as part of transforms.

* [Latex items environment](https://gist.github.com/abul4fia/475577ef58e4cd3babc2028be7f960fa).
Latex template to use latex items, instead of manim's `BulletedList`

* [Code utilities](https://gist.github.com/abul4fia/b1e49ff695725c38e22969c8b8a0dc3e).
Functions to locate a substring inside a `Code` mobject, useful to highlight it, for example.

## Custom mobjects

* [Landscape barchart for manim](https://gist.github.com/abul4fia/e41aa1f1c5c16085da50d0edb956ea0b).
Provides `LandscapeBarChart` class to create and animate horizontal bar charts.

* [Text box for manim](https://gist.github.com/abul4fia/3a349b2f6893b53915cec56ebe58dad6).
Provides `create_textbox()` function to create a text box that automatically adjust the size of the text to the size of the box, with severl options to customize it.

* [Orthogonal connections](https://gist.github.com/abul4fia/fc74f5d6b0ef8243003c98c9c4c867bd). 
Create connections between mobjects that are composed only of horizontal and vertical lines. Through a custom syntax you can specify where the corners may happen.

* [New LatexTip for latex-style arrows](https://gist.github.com/abul4fia/c096930dd7cafe9b6a8c5c3723b618e0). 
New arrow tip shape.


## Fixes and silly things

* [How to fix objects and transforms in a manim 3D scene](https://gist.github.com/abul4fia/1419b181e8e3410ef78e6acc25c3df94). 
A trick to fix the position and orientation of something (eg, a title) in a 3D scene, even if the camera is moving.

* [Quine in manim](https://gist.github.com/abul4fia/58e34e140aa987539e078f85fa999fb6). 
A Quine is a program that outputs himself.
