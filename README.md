# MatrixForum
Web Forum project built with WebMatrix


Test edit from Tom

Notes from Curtis:
- I was looking into storing the photos in the db, but it's cumbersome because you have to 
  convert the image file to a binary array and then store it.  Retreiving is in reverse (get the 
  binary blob and convert it back to an image).  I didn't want to figure out the commands, so
  the best alternative is to store the filename.  Makes sense to me.
  
- I've been adding TODO notes to the code as I go so I don't forget about doing something later.
  Feel free to add some as you go as well.

- The basic framework for the Admin page is there, but it's not in the format of the assignment
  See the TODO's

- I just noticed that there's a User Admin page called Manage which we can reformat for the 
  Forum


Member Page
===========
Hey, I think I figured something out about the assignment.  Maybe you already understood it this way.
I thought the "Member page" was for individual members and each Member has their own "Member page" 
posting board that other users post to.   
After looking at the sample pictures in the assignment page, I think "Member page" is for ALL members
to post messages (IOW, messages aren't "To:" anyone specific).  When you click "follow", it lists all
the posts by that one member.
