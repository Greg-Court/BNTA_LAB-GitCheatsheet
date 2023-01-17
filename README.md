# Terminal

- **pwd** → print working directory
- **cd path** → change directory
- **ls** → list files
  - **-a** → list hidden files
  - **-l** → list file details
- **mkdir** → create directory
- **touch** → create file
- **open** → open file using default application
- **rm** → delete file
  - **-r** → recursive flag
  - **-f** → force flag
- **cp** → copy
  - **-r** → recursive flag for folders

- **cat** → get the resident mac cat to read the file
- **echo ... >>** → append to file
- **echo ... >** → overwrite file

- ***CMD + T*** → new tab in terminal command


# GitHub

## Main Commands

- git log → shows commit log
- git config --global init.defaultBranch main → change default branch to main
- git status → show status
- git add → add files to staging area
- git commit → commit files (locally)
- git push origin main → push files to repo


## Process to push changes
1. git status
2. git add <files> (or .)
3. git commit -m “message”
4. git push origin main  (to push locally created changes to the remote repository) (“main” is the branch name, and "origin" is a shorthand name for the remote repository that a project was originally cloned from)

## Creating a repository via GitHub
1. Create repo on GitHub
2. Copy SSH link
3. Paste git clone + ssh link

## Initialising a repository from our system rather than remotely
1. git init
2. git add .
3. git commit -m “first commit”
4. go to github, create repository, and copy git remote add origin git@github.com… paste that into terminal in local repository
5. git push origin main

## Ignoring files
1. touch .gitignore file
2. git config --global core.excludesFile ~/.gitignore
3. echo filename into .gitignore
4. add .gitignore to staging area
5. commit changes
6. push origin main

# Markdown

Headings

## H2
### H3

Bold	**bold text**

Italic	*italicized text*

Bold Italicized ***bold italicised text***

Blockquote	

> blockquote
>> double blocc quot

Ordered List
1. First item
2. Second item
3. Third item

Unordered List
- First item
- Second item
- Third item

Code	`code`

Horizontal Rule	

---

Link	[title](https://www.example.com)

Image	![alt text](image.jpg)

Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |

Fenced Code Block	

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

<!-- this
is
all
commented!!! -->