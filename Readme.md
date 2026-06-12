Options to create a `.gitlab-ci.yml`:

# 01-bare-jekyll-website/.gitlab-ci.yml
This project will build the jekyll code online (any push will be built).

# 03-jekyll+able/.gitlab-ci.yml
This project will build the jekyll code online (only tags will be built).

# 04-host-prebuilt-jekyll-website-gitlab.md/.gitlab-ci.yml
The necessary files need to be inside a `public` folder. It will be hosted as is at the domain root domain.com/

# 05-manual-copying/.gitlab-ci.yml (don't use this one)
Files are copied manually into a `publi` folder.
