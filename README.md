# Style Guide

Let's adhere to some basic stylistic standards for our Confluence documentation.

Our language is written in a voice that is personal, without referencing an individual.


### Navigation
- Pages with more than three distinct sections have a Table of Contents listing at the top.
- Pages are grouped into most-likely-use, with distinct, but related, content contained in Child Pages.
- Child pages are listed for relevant pages.
- Headers are identified for each section, to ease organization.

### Process
We write our documentation with the desired outcome, not documenting an individual's preference.
How a team member achieves the desired outcome is up to them.

1. Edit `~/.bash_profile` 
2. Add the following to the profile

         alias rei="ssh [username]@rei.sf.crunchyroll.com"
     
### Code
Commands containing a single argument are written with monospace text (the 'preformatted' option does the same thing, but to an entire line's styling, and prevents any indenting):

`cd /Users/`

Anything beyond a single argument is written in a code block, to make it easy to visually identify, and to avoid any confusion

    cat /Users/root/docs/aws-iam-users.txt | grep username

### File System / Path in context
File paths in documentation are written in `monospace` text, for clarity

The Screensaver Preferences are located, for each monitor, at `~/Library/Preferences/ByHost/com.apple.screensaver.RANDOMNUMBER.plist`

### Variables
Variables are identified in-context with _italics_ and in-code with brackets [username]@FQDN.com

### Links
Links are written in Fully Qualified Domain Name (FQDN), unless a common abbreviation is made in-text, and the FQDN link is made behind-the-scenes.

We support connections to [Rei](rei.sf.crunchyroll.com) , but if you're seeking admin access for content management, log into <https://admin.crunchyroll.com>
