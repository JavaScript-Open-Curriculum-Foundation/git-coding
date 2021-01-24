---
# This file is best viewed in vscode using vscode-reveal
# https://marketplace.visualstudio.com/items?itemName=evilz.vscode-reveal
title: "JavaScript"
logoImg: "https://raw.githubusercontent.com/HansUXdev/JavaScript-First/2acf5840c15af96602aceb66303ea69c5b75e344/logo.svg"
theme: "night"
highlightTheme: "Monokai "
#transition: " slide "
#transitionSpeed: " default " 
#slideNumber: true
#loop: true
#autoSlide: 5000 
# openButton: false
#enableMenu: false
# controlsLayout: 'edges'
# controls: true
#enableChalkboard: false
# enableTitleFooter: false
#autoSlideStoppable: true
---

<style>
</style>


### Creating Merge Conflicts 

 
```bash
mkdir git-repo
cd git-repo
git init
touch my_code.sh
echo "echo Hello" > my_code.sh
git add my_code.sh
git commit -am 'initial'
git checkout -b new_branch
echo "echo \"Hello World\"" > my_code.sh
git commit -am 'first commit on new_branch'
git checkout master
echo "echo \"Hello World!\"" > my_code.sh
git commit -am 'second commit on master'
git merge new_branch
```
1.  Create a new directory called "git-repo" {.fragment .current-only data-code-focus=1-1 }
2.  Change the directory {.fragment .current-only data-code-focus=2-2 }
3.  creates an empty Git repository{.fragment .current-only data-code-focus=3-3 }
4.  create a file called my_code.sh {.fragment .current-only data-code-focus=4-4 }
5.  add some commands to the file, should now read `echo hello` {.fragment .current-only data-code-focus=5-5 }
6.  add the file to the git repository {.fragment .current-only data-code-focus=6-6 }
7.  Make your first commit {.fragment .current-only data-code-focus=7-7 }
8.  Switch to a new branch called "new_branch" {.fragment .current-only data-code-focus=8-8 }
9.  Change the file {.fragment .current-only data-code-focus=9-9 }
10. Commit {.fragment .current-only data-code-focus=10-10 }
11. Go to the main branch {.fragment .current-only data-code-focus=11-11 }
12. Change the text again {.fragment .current-only data-code-focus=12-12 }
13. Commit changes {.fragment .current-only data-code-focus=13-13 }
14. merge the branches {.fragment .current-only data-code-focus=14-14 }


---

