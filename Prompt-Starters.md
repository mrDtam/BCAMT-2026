# BCAMT Workshop: LaTeX + AI

Here are some different ways to use your choice of AI along with LaTeX to make professional assessments. If you plan on uploading an old file to convert, it is recommended that you first convert your file to PDF first.

## Prompts

### 1. From scratch

> Create a LaTeX math quiz using the **exam class**. Include 3 trigonometric identities questions inside the **questions environment**, and **wrap the answers in solution blocks**. Have a **\printanswers toggle** at the top of the document.
>
### Optional Prompt Add-Ons

You can copy and paste any of these phrases onto the end of the prompts above to customize your assessment:

* **To assign points:** *"Assign point values to each question using `\question[points]`." Provide total score display at the top of the document.*
* **To add grading rubrics:** *"Include a brief grading rubric inside each solution block."*
* **To fix spacing for student work:** *"Add `\vspace{\stretch{1}}` after each question to give students room to work."*
* **To add a header:** *"Include a header at the top with lines for Name, Date, and Period."*

*  **Include a header at the top with lines for Name, Date, and Period. Assign point values to each question using \question[points]. Provide total score display at the top of the document. Wrap all answers inside solution blocks and include a brief grading rubric inside each solution block. Add \vspace{\stretch{1}} after short questions and \vspace{\stretch{2}} after complex questions to distribute the workspace evenly across the page.**

### 2. From a PDF

> Convert this PDF to LaTeX code, using the **exam class** and the **questions and parts environment**. Use **tikz** to reproduce any diagrams. **Wrap answers in solution blocks and have a \printanswers toggle** at the top of the document.
>> **Free AI Tiers:** Conversations may be limited quite a bit once files are uploaded. If you do not have a paid tiered of AI, it's recommended that you use LaTeX code as often as you can. If you hit a limit, you can paste just sections of your code to AI to edit.

### 3. From a LaTeX template

> Make a new assessment following this template exactly. Change the questions to __(Insert your requests)__. Return in copy and paste LaTeX code.

### 4. Fix broken LaTeX

> Here is a LaTeX snippet with errors. Identify the syntax or logic errors and output a corrected version. Explain the fixes briefly.

## Editing a LaTeX File
> Paste either the entire LaTeX code, or just the portion you want to edit.

> "Update the following code with ___(Insert your requests)___"

## Making new versions
> "Make a new version of this assessment, change the numbers and expressions, but keep the difficulty the same. **Wrap answers in solution blocks and have a printanswers toggle**.
>> **Paste your LaTeX code for the assessment**
