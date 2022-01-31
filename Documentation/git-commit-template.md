# Using Git Commit Message Templates to Write Better Commit Messages

The always enthusiastic and knowledgeable mr. [@jasaltvik](https://github.com/jasaltvik) shared with our team 
an article on writing (good) Git commit messages: 
[How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/). 
This excellent article explains why *good* Git commit messages are important, 
and explains what constitutes a good commit message. I wholeheartedly agree 
with what [@cbeams](https://github.com/cbeams) writes in his article. (Have you read it yet? If not, go 
[read it now](https://chris.beams.io/posts/git-commit/). I'll wait.) 
It's sensible stuff. So I decided to start following the 
[seven rules](https://chris.beams.io/posts/git-commit/#seven-rules) 
he proposes. 

...There's only one problem: My mind is already stuffed with things I should do 
and things to remember. The chance of me remembering every rule every time I 
commit something, are next to 0. So I made myself a Git commit message 
template. That way, I don't have to remember the rules, they are presented to 
me whenever I write a commit message. So now, when I do `git commit`, this is 
what I see in my editor: 

```
# Title: Summary, imperative, start upper case, don't end with a period
# No more than 50 chars. #### 50 chars is here:  #

# Remember blank line between title and body.

# Body: Explain *what* and *why* (not *how*). Include task ID (Jira issue).
# Wrap at 72 chars. ################################## which is here:  #

# At the end: Include Co-authored-by for all contributors. 
# Include at least one empty line before it. Format: 
# Co-authored-by: name <user@users.noreply.github.com>
#
# How to Write a Git Commit Message:
# https://chris.beams.io/posts/git-commit/
#
# 1. Separate subject from body with a blank line
# 2. Limit the subject line to 50 characters
# 3. Capitalize the subject line
# 4. Do not end the subject line with a period
# 5. Use the imperative mood in the subject line
# 6. Wrap the body at 72 characters
# 7. Use the body to explain what and why vs. how

# Please enter the commit message for your changes. Lines starting
# with '#' will be ignored, and an empty message aborts the commit.
#
# On branch master
# Your branch is up to date with 'origin/main'.
#
# Changes to be committed:
#       new file:   installation.md
#
```

What I see consists of two parts; first my own template, then Git's standard 
message asking me to "Please enter the commit message". 
No need to remember everything - or really much at all, except to *not* use 
`git commit -m "Commit message"`, as this means I won't see the template 
I made. 

## Template File 
Here is my template*, which i put in a file called `.gitmessage` in my 
home directory: 

```
# Title: Summary, imperative, start upper case, don't end with a period
# No more than 50 chars. #### 50 chars is here:  #

# Remember blank line between title and body.

# Body: Explain *what* and *why* (not *how*). Include task ID (Jira issue).
# Wrap at 72 chars. ################################## which is here:  #


# At the end: Include Co-authored-by for all contributors. 
# Include at least one empty line before it. Format: 
# Co-authored-by: name <user@users.noreply.github.com>
#
# How to Write a Git Commit Message:
# https://chris.beams.io/posts/git-commit/
#
# 1. Separate subject from body with a blank line
# 2. Limit the subject line to 50 characters
# 3. Capitalize the subject line
# 4. Do not end the subject line with a period
# 5. Use the imperative mood in the subject line
# 6. Wrap the body at 72 characters
# 7. Use the body to explain what and why vs. how
```

## Git Configuration 

To tell Git to use the template file (globally, not just in the current repo), 
I used the following command: 
 
`git config --global commit.template ~/.gitmessage`

And that's all there was to it. (Except I have my dotfiles in a repo, so I had 
to do some symlinking and update one of my config-scripts to be able to 
recreate this setup from scratch if I need to.) 

## Links and Documentation 

The Git documentation contains a chapter on 
[Customizing Git - Git Configuration](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration) 
which in turn contains a section on the `commit.template` configuration value. 

[Better Commit Messages with a .gitmessage Template](https://thoughtbot.com/blog/better-commit-messages-with-a-gitmessage-template) 
has a different kind of template, which is an actual template: It contains text 
which will become a part of the commit message. 

I also made a Gist on [Adding co-authors to Git commits](https://gist.github.com/lisawolderiksen/f9747a3ae1e58e9daa7d176ab98f1bad) to share the credit for collaborative efforts. 

## Addendum

An easy way to get this config using a single command:

`printf "# Title: Summary, imperative, start upper case, don't end with a period\n# No more than 50 chars. #### 50 chars is here:  #\n\n# Remember blank line between title and body.\n\n# Body: Explain *what* and *why* (not *how*). Include task ID (Jira issue).\n# Wrap at 72 chars. ################################## which is here:  #\n\n\n# At the end: Include Co-authored-by for all contributors. \n# Include at least one empty line before it. Format: \n# Co-authored-by: name <user@users.noreply.github.com>\n#\n# How to Write a Git Commit Message:\n# https://chris.beams.io/posts/git-commit/\n#\n# 1. Separate subject from body with a blank line\n# 2. Limit the subject line to 50 characters\n# 3. Capitalize the subject line\n# 4. Do not end the subject line with a period\n# 5. Use the imperative mood in the subject line\n# 6. Wrap the body at 72 characters\n# 7. Use the body to explain what and why vs. how\n" > ~/.gitmessage && git config --global commit.template ~/.gitmessage`

Thanks a lot to [@manav148](https://github.com/manav148), [@rany2](https://github.com/rany2) and [@drjasonharrison](https://github.com/drjasonharrison) for the suggestions in the comments! The command I included above includes some updates I made to the template that were not there at the time of the comments; the line length indicators and the missing space in the first item of the numbered list.

## Footnotes 

*) It may be argued that this is, strictly speaking, not a template, as 
no part of it is actually used/included in the commit message. :) 
