[Qiita: Gradle Versions Plugin によるバージョン管理](https://qiita.com/beyondseeker/items/ed12711ae18692121451) 用のサンプルコードプロジェクトです。

dependencyUpdates task の実行例：
```
$ ./gradlew dependencyUpdates

> Task :dependencyUpdates

------------------------------------------------------------
: Project Dependency Updates (report to plain text file)
------------------------------------------------------------

The following dependencies are using the latest milestone version:
 - androidx.constraintlayout:constraintlayout:1.1.3
 - androidx.core:core-ktx:1.3.1
 - androidx.test.espresso:espresso-core:3.2.0
 - androidx.test.ext:junit:1.1.1
 - com.android.tools.build:gradle:4.0.1
 - com.github.ben-manes.versions:com.github.ben-manes.versions.gradle.plugin:0.29.0
 - org.jetbrains.kotlin:kotlin-android-extensions:1.3.72
 - org.jetbrains.kotlin:kotlin-android-extensions-runtime:1.3.72
 - org.jetbrains.kotlin:kotlin-gradle-plugin:1.3.72
 - org.jetbrains.kotlin:kotlin-stdlib:1.3.72

The following dependencies have later milestone versions:
 - androidx.appcompat:appcompat [1.1.0 -> 1.2.0]
     https://developer.android.com/jetpack/androidx
 - junit:junit [4.12 -> 4.13]
     http://junit.org

Gradle release-candidate updates:
 - Gradle: [6.1.1 -> 6.5.1 -> 6.6-rc-6]
```
