# TopDrawerLayout
[![State-of-the-art Shitcode](https://img.shields.io/static/v1?label=State-of-the-art&message=Shitcode&color=7B5804)](https://github.com/trekhleb/state-of-the-art-shitcode) [![](https://jitpack.io/v/inkDDD/TopDrawerLayout.svg)](https://jitpack.io/#inkDDD/TopDrawerLayout)


a edited version of DrawerLayout but drawer open from top
魔改下拉DrawerLayout

<img src="https://i.loli.net/2020/04/16/l3fNxwFGoBWcZ4I.jpg" width="300px"> <img src="https://i.loli.net/2020/04/16/F1yoAYOuKj6H2gf.jpg" width="300px">

## Setting up the dependency

**Step 1.** Add the JitPack repository to your build file

Add it in your root build.gradle at the end of repositories:

**DO NOT add to buildscript's dependencies** 

```groovy
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```

**Step 2.** Add the dependency

```groovy
dependencies {
    implementation 'com.github.inkDDD:TopDrawerLayout:0.1.0'
}
```

## Usage

Similar to original DrawerLayout but android:layout_gravity="top"