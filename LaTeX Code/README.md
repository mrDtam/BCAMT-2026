###  LaTeX Style Guide: Custom vs. Standard

When downloading and using these files, you have two options for your setup. Please read the notes below to ensure your documents compile correctly.

####  Option 1: Using `doug-test.sty` (Custom Shortcuts)
If you want to use the exact files provided in the main folder, **you must have the `doug-test.sty` file saved in the same directory** as your LaTeX document. 
*   **What it does:** This custom style file gives you access to my shortcut commands (like `\svert`, `\drawanytriangle`, and the custom `\quizfrontpage`).
*   **Note:** You must download the `.sty` file alongside the `.tex` files for them to compile.

####  Option 2: The "Dry Code" Files (Standard LaTeX)
If you are new to LaTeX or want to see exactly how the formatting is built from scratch, look inside the **Dry Code Files** folder.
*   **What it does:** These files show you what standard LaTeX looks like without any custom commands. 
*   **Note:** Every formatting trick (spacing, drawing, front pages) is written out using standard, built-in LaTeX packages (like `tikz`, `exam`, and `tasks`). You can copy and paste this code anywhere without needing a custom `.sty` file.
