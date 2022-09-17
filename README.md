# install-multiple-version-java
brew install jenv
echo 'export PATH="$HOME/.jenv/bin:$PATH"' >> ~/.zshrc
echo 'eval "$(jenv init -)"' >> ~/.zshrc
source ~/.zshrc
brew tap adoptopenjdk/openjdk
brew install --cask adoptopenjdk8 or brew install AdoptOpenJDK/openjdk/adoptopenjdk{11,14}
/usr/libexec/java_home -V
jenv add /Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home
java --version
### Setar global
jenv global 1.8
### Setar local
jenv local 11
