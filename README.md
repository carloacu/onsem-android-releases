Onsem Android releases
======================

Maven repository for the Onsem Android releases


### Command line to generate a version

```bash
mvn install:install-file -DgroupId=com.github.carloacu -DartifactId=onsem-android -Dversion=1.0.4 -Dfile=onsem-release.aar -Dpackaging=aar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true
```

