A class projected I worked on with Vaughn Franz in Sprind 2020 for our Object Oriented Design Class.

EasyAnimator is a simple Java application that displays shape animations in 3 formats: text, svg and visual (using the javax Swing library). The inputs to the application are animcation text files (such as hanoi.txt)descrbing the size of the canvas, the shapes and their motions throughout the animation. These files can be found in src/ folder.

To run the program, execute the command java -jar {path-to-EasyAnimator.jar} -in {path-to-animation-txt-file} -view {view-type (text, svg, or visual)} -speed {an integer} -out out

Ex: java -jar A8/resources/A8-TheRemake.jar -in src/hanoi.txt -view visual -speed 50 -out out
