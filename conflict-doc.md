
I am creating this file in RStudio. If I made a file with the same name in my remote repo, via GitHub.com, and haven't pulled it first, I will get a merge conflict.     

I am creating this file directly on GitHub. If I make a file with the same name in my local repo, via RStudio, before pulling this one, I will get a merge conflict. 

I am editing this file on GitHub after resolving merge conflicts in RStudio. When I fetch and pull from upstream, I should see this addition.

I got another merge conflict after editing this file on GitHub, etching, and pulling. I saw the addition as expected, but git did not know how to merge the other text with the current state of this document. In other words, although I did resolve the merge conflict and successfully pushed to my fork, the difference is significant enough to cause another conflict.

This time when I edited it in RStudio to resolve the conflict, I left in the text from upstream that I had deleted in the last merge resolution (line 4) as well as the local changes (line 2).
 
I am making yet another change to the upstream repo (on GitHub)

Now I'm making another (GitHub, upstream) text addition at the end of the document. I have not removed any text. Now I'm adding a bit more text in the same place in another commit.

