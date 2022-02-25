# How to Convert Word Files to Markdown Using Pandoc

## PART 3: How to do the Conversion

Now it is time to do the hardest part. Once we complete this, it is smooth sailing from here.

### Tools

* Command-Line interface

### Steps

1. Navigate to the directory with your edited Word document through the Command-Line.

    "What??!? I don't know how to do that!!" Don't worry it's not too hard. If you do know, you may skip to step 2.

    The Command-Line starts you in the root of all folders and files: the C: drive. The folder (directory) with your edited Word document is a sub-directory of your C: drive... kinda. It is probably burried deep in the many sub-folders you have. Which is why we need to navigate to it. For me, the path would be C:/Documents/School/ENGL 3814/[insert name of assignment].

    Use the `cd + [insert file path]` command to change your current working directory. For me, I would type "cd C:/Documents/School/ENGL 3814/[insert name of assignment]"
2. Use the `pandoc -s [source file] -t markdown --extract-media=images -o [output file]` command to do the conversion

    "[source file]" will be the name of your edited Word document and "[output file]" will be the name of the new Markdown file pandoc will create. You get to pick this name.

You have now converted from Word to Markdown! Only one more step to go!

-------
[Next Step](Modifying-markdown-file.md)

Back to [main page](index.md)
