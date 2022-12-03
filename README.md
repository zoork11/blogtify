# blogtify
While working on a personal blog i searched for some kind of bootstrap or skeleton for a static blog with no cms in vue. Since i could not find anything that that came close to what i was looking for i created something myself.

This is basically the result of it. :)

Feel free to use it, alter it, do what ever you like with it.

# Intention
My intention was to create a very easy static personal blog without any cms. This is achieved by adding posts directly as a new static part to the front end.

Further I wanted to use the ease of modern UI frameworks, in this case vuetify, to stlye blog posts individually.

# Get started
The whole magic happens basically in `getPosts.js`, `FunBlog.vue` and `ViewPost.vue`.

`getPosts.js` provides the function `getPostsFromFolder` to load all files/componentes in `componentes/BlogPosts`.

With this function `FunBlog.vue` loads all the blog posts and shows their titels and adds a link to each blog post.

`ViewPost.vue` uses the same function to dynamically load and show the different blog posts component.

To use this skeleton:
1. Just add a blog posts in the folder `componentes/BlogPosts`
2. Follow the structure and add a unique id and a title to the blog post
3. Individually style the blog post and fill in your content

Thats it. Easy and simple.