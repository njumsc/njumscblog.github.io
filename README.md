# NJU MSC Blog

Blog for NJU MSC

Master contains the website.

Dev contains the source code

Access [https://njumsc.github.io](https://njumsc.github.io) for the website.

# Write

1. Clone the `dev` branch (instead of master)
2. `npm install`
3. `hexo new {title}` to create a post
4. Write the content in /source/{title}.md. Put assets (like images) under /source/{title}, and use it as {% asset_img {relative path to /source/{title}} %}
5. `hexo clean` clean up all previously built files
6. `hexo generate` generate files
7. `hexo serve` open a local server and check the website locally
8. `hexo deploy` deploy contents into master branch.

Refer to [Hexo Website](https://hexo.io/zh-cn/docs/index.html) for details.