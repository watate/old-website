# Install
gem install bundler jekyll
bundle install

# I pushed too early and forgot some files now there's a page error
See: https://stackoverflow.com/questions/11577147/how-to-fix-http-404-on-github-pages
git commit --allow-empty -m "Trigger rebuild"
git push

# Test
bundle exec jekyll serve

# Posts
The "posts" folder is where I'm supposed to put my posts but I don't really have any need for posts (at the moment)

# Homepage
Homepage is in index.md (Don't ask me why or how). Make changes there if you need to update your homepage