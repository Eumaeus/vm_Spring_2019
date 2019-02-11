
# GIT Workflow

Assumptions: 

	1. You are in the the `vm_Spring_2019` virtual machine
	1. You are Allie and your personal GitHub repo is the `allie` directory. **Substitute your name and the name of your own Git repository's directory!**

## Setup

1. `vagrant up`
1. `vagrant ssh`
1. `cd /vagrant`

## Your Repository

1. `cd allie` (**or** `cd /vagrant/allie` )
1. `git pull`
1. Do some work on a file, perhaps editing `README.md`
1. `git add README.md`
1. `git commit -m "message about what you did"`
1. `git push`

## Adding a New File

1. `cd allie` (**or** `cd /vagrant/allie` )
1. Create a new empty file with `touch AllieShare.txt`
1. See it with `ls`.
1. You can edit it in Atom.
1. **Save it.**
1. `git add AllieShare.txt`
1. `git commit -m "Created new file."`
1. `git push`

## Inviting Collaboration

1. Go to your repository on GitHub.com. (Make sure you are logged in.)
1. Click "Settings".
1. Click "Collaborators" on the left.
1. Re-type your password when asked.
1. Under "Search by username, full name or email address" enter your buddy's GitHub user name. Make sure it is the right one.
1. Click "Add Collaborator". An email invitation will be sent.

## Collaborating

1. Get an email invitation from GitHub.
1. Accept it. There will be a link to the repository.
1. Go to the repository on GitHub.com.
1. Be sure you are logged into GitHub.
1. Click on the green "Clone or download" button.
1. Click the clipboard icon to copy the address.
1. **In the VM**
	1. `cd /vagrant`
	1. `git clone [paste the GitHub URL]`
	1. See the new repo with `ls`.

## Getting Help

- Use Google. 
- If the problem is with GitHub, be sure to add the word "GitHub".
- If the problem is with Git in the CLI, be sure to add the word "Git".
- Add the word "Beginners".
- E.g. 
	- "Git pull beginners"
	- "GitHub add collaborator beginners"