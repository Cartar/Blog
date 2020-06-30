# Blog

## How-to
* https://gohugo.io/hosting-and-deployment/hosting-on-github/
  * https://gohugo.io/getting-started/quick-start/
    * https://github.com/reuixiy/hugo-theme-meme

NOTE: it's best to fork the theme being used by hugo so changes can be pushed 
somewhere. Make sure to use the forked repo as the submodule theme. Similarly 
this is why the blog content is it's own repo. Hugo publishes to `public`, which
is defined to contain the submodule where `Cartar.github.io` is actually hosted.

## Content 

Tags and categories:
* Books
* Code
* Opinion
* Lessons

And of course, a strong about page linking to my other online presence :D 
Linking to my YouTube videos would be cool
- Images that link to videos! 

## Making changes
To test locally, simply run:
```sh
hugo server -D
```