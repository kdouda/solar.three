# solar.three

<img width="1117" alt="solar" src="https://user-images.githubusercontent.com/6208270/90980261-93572280-e55a-11ea-8d37-8197be4bc061.png">

Solar.three is a 3D web browser interactive rendering of a simplified version of our solar system. It was created as an experiment during 2014 as an excercise to learn JavaScript and basics of Three.js. Mathematically, the objects follow ellipses with no additional corrections. Starting positions are also not synchronized to a specific date.

# Running

Simply cloning this repo and opening orbity.html in your browser should render the webgl canvas in the entire browser window. You can pan, tilt and zoom using mouse controls. 

# Extending

Simply adding a new object to Models array created using the largeBody function and creating an orbit definition by calling the orbitAu function with orbital parameters of the object.

# Lessons learnt
* Lack of data structures makes this unmaintanable.
* Combining HTML and JS in one file is fine for prototyping to an extent.
* VCS should not contain publicly available libraries. Package manager should be used, ideally with a build tool to only get what we need out of these libraries.
* Three.js is fun.
* Figuring out the math behind parametric ellipses is also fun, especially the inclination.
* Commit your refactored code, this was once refactored to use pure JS prototypes, but I never commited it to GitHub.
