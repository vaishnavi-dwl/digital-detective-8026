# Mission 2 Notes

## Task 2.1: Basic Terminal operations

| Operation / command | What it does | What I observed |
|---|---|---|
| Current-directory display: `pwd` | Displays the full path of the current working directory. | I observed the complete location of my assignment repository on my Mac. |
| Directory listing: `ls` | Lists files and folders in the current directory. | I could see the names of the files and folders present in my repository. |
| Detailed listing: `ls -l` | Displays files and folders with additional information such as permissions, owner, size and modification date. | I noticed that the output contained more information than the normal listing. |
| Change directory: `cd ..` | Moves from the current folder to its parent folder. | I observed that my current location changed to the folder one level above my repository. |
| Create directory: `mkdir practice` | Creates a new directory named `practice`. | A new folder named practice was created. |
| Create empty file: `touch practice/file.txt` | Creates an empty text file inside the practice folder. | An empty file named file.txt appeared inside the practice folder. |
| Copy file: `cp practice/file.txt practice/copy.txt` | Creates a duplicate of the original file with a different name. | Both the original file and its copy were present. |
| Move / rename file: `mv practice/copy.txt practice/renamed.txt` | Moves a file or changes its name. | The copied file was renamed to renamed.txt. |
| Display file contents: `cat practice/file.txt` | Displays the contents of a text file in Terminal. | The command displayed the contents of the original text file. Since it was empty, nothing appeared. |

## Task 2.2: Practising file changes safely

1. **Replacing vs adding text:** Replacing a file's contents using `>` removes the existing content and writes new content. Adding text using `>>` keeps the existing content and adds new text at the end.
2. **Copying vs moving:** Copying a file using `cp` creates another copy while keeping the original file. Moving a file using `mv` changes its location or name, and the file is no longer present at its original location under the old name.
3. **Current-directory display:** The `pwd` command displays the full path of the directory I am currently working in. It helps me understand my location in the folder structure.
4. **Why directory listing is useful:** The `ls` command helps me see the files and folders available in the current location. It makes navigating and managing files easier.

## Task 2.3: Flags and pipes

A pipe connects two commands and passes the output of the first command as input to the second command. In this example, `ls -lah` generates the directory listing, while `head -n 5` displays only its first five lines. Pipes help combine commands and process information efficiently.

## Task 2.4: Package managers

Homebrew 7.0.15

Package managers are useful because they make installing, updating and removing software easier. They manage software dependencies and help users maintain applications efficiently. Homebrew is a popular package manager for macOS that allows users to manage software through Terminal.
