# Step for configuration java in machine
1. brew install jenv
1. echo 'export PATH="$HOME/.jenv/bin:$PATH"' >> ~/.zshrc
1. echo 'eval "$(jenv init -)"' >> ~/.zshrc
1. source ~/.zshrc
1. brew tap adoptopenjdk/openjdk
1. brew install --cask adoptopenjdk8 or brew install AdoptOpenJDK/openjdk/adoptopenjdk{11,14}
1. /usr/libexec/java_home -V
1. jenv add /Library/Java/JavaVirtualMachines/adoptopenjdk-8.jdk/Contents/Home
1. java --version
### Setar global
jenv global 1.8
### Setar local
jenv local 11
