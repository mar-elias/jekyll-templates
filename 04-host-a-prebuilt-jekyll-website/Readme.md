# Note:
The following still requires some processing by gitlab.

# 1. First build the Jekyll website:
`chmod +x ./_build.sh && ./_build.sh`

Note that `_config_REPLICA.yml` needs to have:
    1. the website changed.
    2. the email removed.
    3. the wallpaper changed.
    4. Youtube name hidden.

# 2. Then copy all contents of _site to a folder called 'public' in the repo.

# 3. Finally create (outside 'public' folder) the included `.gitlab-ci.yml`
