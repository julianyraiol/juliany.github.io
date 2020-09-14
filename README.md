Install Ruby dependencies

sudo apt-get install ruby-full build-essential zlib1g-dev

echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc


Finally, install Jekyll and Bundler:
gem install jekyll bundler


Execute to install dependencies of the project:

bundle 

To run:
bundle exec jekyll serve


Template from: https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll