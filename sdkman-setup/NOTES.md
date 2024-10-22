# Setup and Maintain Java Toolkits with SDKMAN

## Initial Setup
1.  `curl -s "https://get.sdkman.io" | bash`
2.  `source "$HOME/.sdkman/bin/sdkman-init.sh"`
3.  `sdk version`

## Java
4.  `sdk list java`
5.  `sdk install java 21.0.5-tem`
6.  `java -version`
7.  `sdk install java 17.0.13-tem`
8.  `java -version`
9.  `sdk use java 21.0.5-tem`
10. `sdk default java 21.0.5-tem`

## Gradle
1. `sdk list gradle`
2. `sdk install gradle`
3. `gradle -v`

## General
1. `sdk upgrade`
2. `sdk uninstall java 17.0.13-tem`
