To update the theme run `bundle update`.

Fetch and update bundled gems by running the following: `bundle`

# Other commands used in this project:

```
gem install bundler
bundle install

bundle exec rake preview
# http://localhost:4000/test/

bundle exec rake serve

bundle exec jekyll serve
bundle exec jekyll serve --watch --port 8080
bundle exec jekyll serve --port 8080
bundle exec jekyll serve --port 8080 --incremental
bundle exec jekyll serve --port 80 --watch --incremental

# http://localhost/

# http://localhost:8080/

# http://localhost:4000/
```

# Links:

https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/

https://www.youtube.com/watch?v=7o7DRrCstdo

https://github.com/planetjekyll/awesome-jekyll-plugins

# Start Local Server.cmd

```
@echo off
cd RoboticEVA.github.io
call bundle exec jekyll serve --port 80 --watch
pause
```