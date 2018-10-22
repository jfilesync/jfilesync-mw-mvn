# JFileSync MW - (Java File Sync - Multi Way) 

A multi way filesync tool written in pure Java.

It is inspired by [JFileSync](http://jfilesync.sourceforge.net/).

## Usage

...

## Building

    mvn clean
    mvn -U -pl \!jfsmw-app verify
    mvn install
    mvn -pl jfsmw-app -am bnd-indexer:index bnd-indexer:index@test-index bnd-resolver:resolve
    mvn package

start the app:
    
    java -jar jfsmw-app/target/jfsmw.jar
    
or for debugging:

    java -jar jfsmw-app/target/debug.jar
