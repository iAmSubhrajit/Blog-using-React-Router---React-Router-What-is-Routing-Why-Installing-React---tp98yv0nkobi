# Blog using React Router
Implement a routing system for a simple blog application that has the following routes:

/: This route should render the homepage component of the blog,, given in the Home.js file
/about: This route should render an about page component for the blog, given in the About.js file
/posts: This route should render a list of all the blog posts, given in the PostList.js file
/posts/:id: This route should render a specific blog post with the given id, given in the PostDetail.js file


1. In Blog.js file, add NavLinks to /about and and /posts. Text inside each of them should be "About" and "Posts" respectively

2. In the Blog.js file , add Routes for About, PostList, and PostDetail components inside the Switch component

3. Complete the PostDetail component so that it returns Post Detail: {id} inside a h1 tag where id is the id of the post whose page is being visited.

4. Inside the ul element of PostList Component, iterate over the posts object and render a Link for each of the object elements using the path as the url and the name as the text inside the Link Component.


Do not modify any other files.

[Demo Video](https://d3dyfaf3iutrxo.cloudfront.net/general/upload/0bcc6ee3a1384ab3b399038feef80067.mkv)
