DBpedia Spotlight Maven Repository
==========

#### How to use it?

Add this in your pom.xml file:
```
        <repository>
            <id>spotlight-releases-repository</id>
            <url>https://github.com/dbpedia-spotlight/maven-repo/raw/master/releases</url>
        </repository>
        
        <repository>
            <id>spotlight-snapshots-repository</id>
            <url>https://github.com/dbpedia-spotlight/maven-repo/raw/master/snapshots</url>
        </repository>
```

#### To deploy in this Maven repository

Add this in the pom.xml of the artifact to be deployed:

```
<distributionManagement>
        <repository>
            <id>spotlight-releases-repository</id>
            <url>https://github.com/dbpedia-spotlight/maven-repo/raw/master/releases</url>
        </repository>
        
        <repository>
            <id>spotlight-snapshots-repository</id>
            <url>https://github.com/dbpedia-spotlight/maven-repo/raw/master/snapshots</url>
        </repository>
</distributionManagement>
```

Thanks to [coffeecoders](http://coffeecoders.de/2011/09/using-github-as-a-personal-maven-repository/) to provide a helpful guide.
