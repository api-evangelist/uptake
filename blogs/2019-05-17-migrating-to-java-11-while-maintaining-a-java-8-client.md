---
title: "Migrating to Java 11 while maintaining a Java 8 client library"
url: "https://medium.com/uptake-tech/migrating-to-java-11-while-maintaining-a-java-8-client-library-f618a3ca6499?source=rss----996245d67cd---4"
date: "2019-05-17"
author: "Jason Brown"
feed_url: "https://medium.com/feed/uptake-tech"
---
The Auth-Service, Uptake’s Identity and Access Management suite, has been on Java 8 since the first git commit in November 2016. We have been big adopters of Java 8 features, including lambda expressions, Stream API, method referencing, optionals, and the Nashorn Javascript Engine. We use Nashorn to allow other teams to compose authorization policies in Javascript which are then compiled to Java.
