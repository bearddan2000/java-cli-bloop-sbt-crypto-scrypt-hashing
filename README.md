# java-cli-bloop-sbt-crypto-scrypt-hashing

## Description
A demo for Scrypt one-way hashing of
a password.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt

## Docker stack
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://www.javatips.net/api/passrepo-master/src/com/lambdaworks/crypto/SCryptUtil.java
- http://www.itcsolutions.eu/2011/08/22/how-to-use-bouncy-castle-cryptographic-api-in-netbeans-or-eclipse-for-java-jse-projects/
