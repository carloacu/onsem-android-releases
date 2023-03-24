Onsem Android releases
======================

Maven repository for the Onsem Android releases<br/>
Url of the project: https://github.com/carloacu/onsem-android

### Command line to install maven

```bash
sudo apt install maven
```

### Command line to generate a version

```bash
mvn install:install-file -DgroupId=com.github.carloacu -DartifactId=onsem-android -Dversion=1.0.4 -Dfile=onsem-release.aar -Dpackaging=aar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true
```

