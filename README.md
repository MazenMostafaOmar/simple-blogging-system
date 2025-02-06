# simple-blogging-system
this is a simple blogging system built using Laravel, where users can Create, Edit and delete blog posts.
 It provides a basic CRUD (Create, Read, Update, Delete) functionality for managing articles 
features
      • Home Page: Displays a list of all blog posts. 
      • Post Management: Create, edit, update, and delete pOsts. 
      • Post Details: View individual blog posts 
      • Authentication: User login and registration for managing posts (use laravel ui package). 
      • Database Integration: Stores blog posts using migrations files.
      • Add validation on Store & Update 
           ◦ Title & description are required , minimum length for iS 3 chars and unique, for description the minimum length is 10 chars,make sure when updating post without changing Title it still work 
           ◦ Make sure to display error messages of failed validation
