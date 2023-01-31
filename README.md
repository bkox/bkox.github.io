https://bkox.github.io

# install 
ubuntu 20.04 LTS

```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get -y install make build-essential ruby ruby-dev
```

```
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

```
sudo rm -rf /usr/lib/ruby/vendor_ruby/
sudo gem install jekyll bundler
sudo gem update --system
gem install minimal-mistakes-jekyll
gem install rake ???
```

# 빌드 명령어
```
bundle exec jekyll serve
bundle exec jekyll build
```
