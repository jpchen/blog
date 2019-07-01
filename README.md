# [Blog](http://blog.jonathanpchen.com)

## Write 
```
# Create new post
$ rake post title="A Title" [date="2015-08-16"] [tags="[tag1, tag2]"] 

# Create new draft post
$ rake draft title="A Title" [date="2015-08-16"] [tags="[tag1, tag2]"]
```
which will create a post in `_posts/`.  Or cp an existing post.

## Build
https://github.com/aweekj/Kiko-plus

To build locally (the url needs to be changed to `localhost:8000`):
```
jekyll build; jekyll serve --config _config_dev.yml --watch
```
