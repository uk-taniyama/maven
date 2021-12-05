# maven

## gradle 

Add the following to the repository information of gradle:

```
    repositories {
        google()
        mavenCentral()
        maven {
            url "https://uk-taniyama.github.io/maven/repository"
        }
    }
```

## Quack

for Libray:

```
    implementation "com.github.uk-taniyama.quack:quack-java:${versions.quack}"
    testImplementation "com.github.uk-taniyama.quack:quack-jni:${versions.quack}"
```

for Windows, Linux, MacOS:

```
    implementation "com.github.uk-taniyama.quack:quack-jni:${versions.quack}"
```

for Android:

```
    implementation "com.github.uk-taniyama.quack:quack-java:${versions.quack}"
    testImplementation "com.github.uk-taniyama.quack:quack-jni:${versions.quack}"
```
