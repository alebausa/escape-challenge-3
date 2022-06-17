# Express escapes 🏆 Challenge 3

Copy this code on the <code>README.md</code> of the repository you are working on, and complete the **last and final challenge**:

---

## Challenge 3: enigmas, enigmas, enigmas. 🩻

Our app already has users and teams. The last part is actually the part we have been working on all day: creating the enigmas.

Create a new model called Enigma. Every <code>Enigma</code> will have the following fields:
- Title (string)
- Number (number)
- Description (string). What does the person have to do to solve it?
- Image (string). It will store an image URL from the Internet (pick any random images that you want). This field is optional.
- Team (id referencing the model <code>Team</code>). This will be a reference to the team that tried to solve the enigma.
- Solved (boolean). You will have to read about [input type checkbox](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/checkbox) to solve this one. This kind of input has a property *checked*: when this happens, we should store the boolean *true* in the document and that enigma will be considered *solved*.

Create all the views and routes needed in order to:
- Create Enigmas. All the teams from the database should be placed in a <code>select</code>. You should be able to choose *only one* team per enigma.
- List all the enigmas. A list of titles as anchors. In the view, the enigmas should be **visually separated by *solved* and *not solved***. Even though you solved them all, leave some *unsolved* enigmas in the database to test this feature.
- Also, remember how we had a route /enigma that was protected to only logged-in users? EVERYTHING related to enigmas should be protected not seen by users unless they are logged in.
- See the enigma's detail with the name of the team that tried to solve it.
- Edit enigmas.
- Delete enigmas.

## Final touches 💅🏽

Remember that, for the last evaluation, your app will be judged based on:
- Navigation
- App structure
- Code quality
- Number and naming of the commits
- Style (oh yes you thought we forgot about that?)

When you are ready to submit, feel free to present your work to the judges 😈

*...Happy coding ;)*

