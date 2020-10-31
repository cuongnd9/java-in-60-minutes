# java-in-60-minutes

- [ x ] Setup environment on MacOS (5 minutes)

1. Download JDK: https://jdk.java.net/15/

2. Extract it & move to /Library/Java/JavaVirtualMachines/

```sh
tar -xvf openjdk-15.0.1_osx-x64_bin.tar
sudo mv jdk-15.0.1.jdk /Library/Java/JavaVirtualMachines
```

3. Open .bash_profile and add the following entries at the end of it.

```sh
JAVA_HOME="/Library/Java/JavaVirtualMachines/jdk-15.0.1.jdk/Contents/Home"
PATH="${JAVA_HOME}/bin:${PATH}"
export PATH
```

4. Verify the JDK installation

```sh
java --version
```

5. Download Maven: https://maven.apache.org/download.cgi

6. Extract it & move to /opt

```sh
tar -xvf apache-maven-3.6.3-bin.tar
sudo mv apache-maven-3.6.3/ /opt
```

7. Open .bash_profile and add the following entries at the end of it.

```
export PATH=/opt/apache-maven-3.6.3/bin:$PATH
```

8. Verify the Maven installation

```sh
mvn --version
```

- [ ] Java Core (20 minutes)

- [ ] Spring Boot (30 minutes)

- [ ] Docker (5 minutes)
