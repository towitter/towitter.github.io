# towitter.github.io
Personal webpage

# how to update content
First, open 'my-webpage' repository in RStudio. Add the desired content, save it, and
run the command 'hugo server' to preview on http://localhost:1313/ via browser. If it
is fine, run 'hugo' command. Updates are saved in 'public' folder. Now, commit and push
changes to Git. Copy the content of the 'public' folder to clipboard. Then, open the 
'towitter.github.io' repository in RStudio, add the copied content to the main directory.
Commit and push changes. The updates should be directle visible on towitter.github.io.

# associated domains
tobias-witter.com
www.tobias-witter.com

# create a new blogpost
Run in shell of 'my-website' repository: hugo new  --kind post post/my-article-name.
Add content to the blogpost and preview with 'hugo server' command an local host.
Follow the above mentioned steps for content update to get it on the webpage.
