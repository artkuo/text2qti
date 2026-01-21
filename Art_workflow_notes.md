# Art's workflow notes for text2qti

Implemented a uv environment. No install, no setuptools. 

Run with 
`uv run text2qti demo/quiz.txt --pandoc-mathml`

and upload to D2L import course components. Note that import fails at assessments, use the main course tools (Gear icon at upper right). 

To view questions, go to quizzes. They are also in the question library with a folder for each upload.

* Tested demo quiz.txt
* Tested with a math element?, imported and viewed.
* Tested with images? imported and viewed. image was same folder as quiz, used markdown indented to same level as question.


## Things to avoid
There's a PR to make compatible with brightspace, but it didn't work here. We're using the default canvas flavor, which brightspace is able to import as a component.

