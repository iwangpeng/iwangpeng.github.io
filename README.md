# Gradle

Add this to your source repositories

    repositories {
        maven { url "http://iwangpeng.github.io/repository/" }
        mavenCentral()
    }

## Aarki
    compile 'com.aarki:monetization:3.0'

## NativeX

**android:minSdkVersion = 11**

    compile 'com.nativex:monetization:5.5.6'
    compile 'com.google.code.gson:gson:2.3.1'
    
## Fyber

Fyber has added support for Gradle/Maven integrations since version 7.1.0.

See http://developer.fyber.com/content/current/android/basics/downloads/

    repositories {
        maven {
            name "Fyber's maven repo"
            url "https://fyber.bintray.com/maven"
        }
    }

    dependencies {
        compile 'com.fyber:fyber-sdk:8.0.0'
    }
    
## TrialPay
    compile 'com.trialpay.android:monetization:2.2014463'
    
## Kiip
    compile 'me.kiip.sdk:kiip:2.3.1'

## SupersonicAds
    compile 'com.supersonic:supersonicads:6.0.0'
    
## Woobi
    compile 'com.woobi:monetization:1.3'
    
## AdColony

**android:minSdkVersion = 10**

    compile 'com.jirbo.adcolony:adcolony:2.3.0'
    
## Vungle

**android:minSdkVersion = 9**

    compile 'com.vungle:vungle:3.3.2'
    compile 'com.nineoldandroids:library:2.4.0'
    compile 'com.squareup.dagger:dagger:1.2.2'

## AppLovin
    compile 'com.applovin:applovin:6.4.2'

## Flurry Analytics
    compile 'com.flurry.android:analytics:5.4.0'

## AdMob Mediation Adapter - MoPub
    compile 'com.mopub.mobileads.dfp.adapters:mopub-adapter:1.0.0'

## CrossWalk project

See https://crosswalk-project.org/

    compile 'org.xwalk:xwalk_core_library:15.44.384.13'
