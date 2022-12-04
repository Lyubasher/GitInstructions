# Instructions for Git

>**git config user.name** - initialize username

>**git config user.mail** - initialize user mail

>**git status** - get information about git state

>**git add file_name** - track file

>**git commit -m "commit message"** - fix changes with files
> - -m (message)
> - -a (let us avoid repeating command *add*)

>**git log** - get information about commits

>**git checkout 1234** - transition between commits

>**git diff** - show differences in our file

## Instructions for commands with branches

>**git branch** - display out branches

>**git branch name** - create new branch

>**git merge name** - combine two branches

>**git reset --merge ORIG_HEAD** - cancellation of mergering branches (including after conflict)

>**git checkout -b name** - creating and transition to new branch

## Instructions for working with Remote Repositories

>**git clone _URL_** - clone remote repository 

GitHub will give you the repository **_URL_** to copy in order to clone a repository.

>**git remote add _name_ _URL_** - create a remote server (GitHub) for a repository you have on your local machine

**_name_** - name reference for the server, which is typically “origin”

**_URL_** - GitHub page of the empty repository

>**git push** - move local commits to the remote repository

>**git pull** - move changes from the remote repository to the local repository

>**_forking in GitHub_** (not a command) :

**_Fork_** is a copy of a complete repository to the user's GitHub Account from another account.It allows to freely experiment with changes without affecting the original project.

**_Pull request_** - send the changes to the owner of the repository as a request

![Forking Process](fork-pullrequest.png)


# Instructions for Markdown

* **_Text highlighting_**

To highlight the text in intalics, you need to frame it with * or underscores (*fox* or _fox_)

To make the text bold, you need to frame it with ** or double underscores (**fox** or __fox__)

Alternative ways of text highlighting are needed in order to combine both methods. For example, _the text can be in intalics and **bold**_.

* **_Quotes_**

To add quotes use sign >.

> Per aspera ad astra.

* **_Links_**

To add link use code - [link text](link address)

Please visit [GitHub](https://desktop.github.com/)

* **_Images_**

To add image use code - ![text for image](way to file)

![GitHub logo](github-logo.png) 

* **_Footnotes_**

To add footnote use code - [^x]

Dream[^1]

[^1] : [cats](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D1%88%D0%BA%D0%B0)

* **_Lists_**

To add unnumbered lists, you need to highlight the items with *.
For example:
* first
* second
* third 

To add numbered lists, you just need to number the items.
For example:
1. First
2. Second
3. Third

* **_Conclusion_**

That's all! For more details, please follow 
[Microsoft's Markdown Reference](https://learn.microsoft.com/ru-ru/contribute/markdown-reference).


Congratulate, you have finished studying the Markdown instruction!



