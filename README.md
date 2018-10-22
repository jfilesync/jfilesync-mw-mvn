# JFileSync MW - (Java File Sync - Multi Way) 

A multi way filesync tool written in pure Java.

It is inspired by [JFileSync](http://jfilesync.sourceforge.net/).

## Usage

...

## Building

    ./mvnw clean
    ./mvnw -U -pl \!jfsmw-app verify
    ./mvnw install
    ./mvnw -pl jfsmw-app -am bnd-indexer:index bnd-indexer:index@test-index bnd-resolver:resolve
    ./mvnw package

start the app:
    
    java -jar jfsmw-app/target/jfsmw.jar
    
or for debugging:

    java -jar jfsmw-app/target/debug.jar
