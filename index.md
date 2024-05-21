# Portfolio

---

## More to come

I'm currently in the process of re-implementing and uploading more of my projects to this website. **Stay tuned and check back later!**

All code can be found on my [GitHub profile](https://github.com/cljord)

---

### [Gas Station Finder](https://scopevisio-takehome.vercel.app/) <br>

Part of a take-home assignment for a job interview. The task was to download .json data that the city of Cologne made available. This dataset contained information about gas stations in the area in and around Cologne, which should be "displayed appropriately".

I used Mapbox to display the gas stations on a map of cologne and then created a grid of cards with pagination.

**Skills: Frontend (React, HTML, CSS, JavaScript)**

The second part of the task consisted of coming up with ideas on how to make collaborative coding simple on this project. My ideas were to use a Linter (ESLint), Code formatter (Prettier), and run tests. I went a step further and, instead of only coming up with ideas, implemented a GitHub actions pipeline for this.

**Skills: CI/CD (GitHub actions, ESLint, Prettier)**

Finally, the third part of the task was to think about how to design your own CRUD interface for this. Again, I went a step further and implemented a basic version of this interface.

**Skills: Backend (Node.js, Express, PostgreSQL)**
<img src="images/gasstation.gif?raw=true"/>

---

### [The Smartbrain](https://smartbrain-frontend-pno3.onrender.com/) <br>

Using the PERN stack (PostgreSQL, Express.js, React.js, Node.js), you can register and sign up, then enter a link. Using a face detection model (with an API call to Clarifai), you will receive a bounding box around one face.

Current todo is to extend it so the bounding box will appear around all faces (if multiple people are in the picture), but wanted to showcase it already.

Uses encryption, but you can sign in with user ax@ax.com and password "ax" to test it yourself and avoid using your real email address (you can also register with a fake address). Capstone project from an online course I completed next to my studies.

**Please note: Due to the free hosting I am using, the database spins down after a while. If you register or sign in and nothing happens, just keep the window open for up to a minute.**
<img src="images/smartbrain.gif?raw=true"/>

---

### [Wolfenstein 3D-style Raycaster](https://cljord.github.io/raycaster/) <br>
A simple [Raycaster](https://en.wikipedia.org/wiki/Ray_casting) in the style of [Wolfenstein 3D](https://en.wikipedia.org/wiki/Wolfenstein_3D) (you might also know this style from the [Windows 3D Maze Screensaver](https://en.wikipedia.org/wiki/3D_Maze)), written in pure JavaScript and using the [p5.js](https://p5js.org/) library for line drawing and keyboard input. No other libraries used. Move around with the arrow keys.
<img src="images/raycaster.gif?raw=true"/>

---

# Education

- M.Sc. Computer Science at University of Bonn, 2021 - December 2023.

The title of my thesis was **"Utilising fractional values in primal heuristics to solve MaxCut with Branch-and-Bound"** and was concerned with: parallelising the execution of heuristics during the main branch-and-bound search - modifying and implementing MaxCut-specific heuristics to speed up the computation process - using improvement heuristics - running a large-scale experimental comparison.

This resulted in considerable speed-ups and increased the efficiency of the solver when solving the MaxCut problem.

- B.Sc. Informatik (Computer Science) at University of Bonn, 2018-2021.

The title of my thesis was **"Klassifikation temporaler Graphen mit Graphkernen" ("Classification of temporal graphs with graph kernels")**. I modified an [algorithm](https://dl.acm.org/doi/abs/10.1145/3018661.3018731) for counting occurences of structures in temporal graphs so it could be used with node-labeled data.

This allowed the adaptation of a [static graphlet kernel](https://proceedings.mlr.press/v5/shervashidze09a.html) to work with labeled, temporal graphs and subsequent classification of these graphs with a [Support Vector Machine](https://en.wikipedia.org/wiki/Support_vector_machine).

In practice, this would allow e.g. distinguishing real from fake news when informations travels through a network, as these have different spread patterns. The results achieved here were quite strong and we ended up publishing a paper on the basis of my work, see below.

---

# Publication

I have exactly one paper to my name:

[A Temporal Graphlet Kernel For Classifying Dissemination in Evolving Networks. L Oettershagen, NM Kriege, C Jordan, P Mutzel](https://epubs.siam.org/doi/abs/10.1137/1.9781611977653.ch3).

It is based on the results of my Bachelor's thesis, but with improvements. It received the **Best Paper Award** at the [18th International Workshop on Mining and Learning with Graphs](http://www.mlgworkshop.org/2023/).


---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
