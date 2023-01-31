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

vendor_ruby 폴더 삭제 (∵ 이 폴더 때문에 여기저기서 에러 발생)
제조사의 커스터마이즈를 목적으로 만들어진 폴더
jekyll을 포함해 우리가 사용하려는 환경은 사용자 홈에 설치된 ruby임. 즉, 삭제해도 무방
```
sudo rm -rf /usr/lib/ruby/vendor_ruby/
```

```
sudo gem update --system
sudo gem install jekyll bundler
gem install minimal-mistakes-jekyll
```

![image](https://user-images.githubusercontent.com/121213023/215683306-56a0b9c3-fdfe-4468-8e2d-8f4773fa273a.png)
```
gem install rake
```

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

vendor_ruby 폴더 삭제 (∵ 이 폴더 때문에 여기저기서 에러 발생)
제조사의 커스터마이즈를 목적으로 만들어진 폴더
jekyll을 포함해 우리가 사용하려는 환경은 사용자 홈에 설치된 ruby임. 즉, 삭제해도 무방
```
sudo rm -rf /usr/lib/ruby/vendor_ruby/
```

```
sudo gem update --system
sudo gem install jekyll bundler
gem install minimal-mistakes-jekyll
```

![image](https://user-images.githubusercontent.com/121213023/215683306-56a0b9c3-fdfe-4468-8e2d-8f4773fa273a.png)
```
gem install rake
```

![image](https://user-images.githubusercontent.com/121213023/215684062-87fda3f9-5503-48e1-8bc0-73f7b6af23ce.png)


# 빌드 명령어
```
bundle exec jekyll serve
bundle exec jekyll build
```
