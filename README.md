# open-api-libraries

##### Add this at ```build.gradle(Project)```
```kotlin
 dependencies {
      
        classpath "com.google.dagger:hilt-android-gradle-plugin:2.38.1"

        // NOTE: Do not place your application dependencies here; they belong
        // in the individual module build.gradle files
    }
}

```


##### Add this at  ```build.gradle(Module)```
```kotlin
plugins {
    id 'com.android.application'
    id 'kotlin-android'
    id 'kotlin-kapt'
    id 'dagger.hilt.android.plugin'
}

```


```kotlin
dependencies {

//noinspection GradleDependency
    implementation "androidx.compose.material:material-icons-core:$compose_version"
    implementation "androidx.compose.material:material-icons-extended:$compose_version"
    implementation "androidx.lifecycle:lifecycle-viewmodel-compose:1.0.0-alpha07"
    implementation "androidx.navigation:navigation-compose:2.4.0-alpha07"
    implementation "androidx.constraintlayout:constraintlayout-compose:1.0.0-beta02"

    // Retrofit
    implementation 'com.squareup.retrofit2:retrofit:2.9.0'
    implementation 'com.squareup.retrofit2:converter-gson:2.9.0'
    implementation "com.squareup.okhttp3:okhttp:4.9.1"
    implementation "com.squareup.okhttp3:logging-interceptor:4.9.1"

    implementation "com.squareup.retrofit2:retrofit:2.9.0"
    implementation "com.squareup.retrofit2:converter-moshi:2.9.0"


    // Room
    implementation "androidx.room:room-runtime:2.3.0"
    kapt "androidx.room:room-compiler:2.3.0"
    // Kotlin Extensions and Coroutines support for Room
    implementation "androidx.room:room-ktx:2.3.0"

    // Glide
    implementation 'com.github.bumptech.glide:glide:4.12.0'
    kapt 'com.github.bumptech.glide:compiler:4.12.0'

    //Paging
    implementation("androidx.paging:paging-compose:1.0.0-alpha12")
    implementation "com.squareup.moshi:moshi-kotlin:1.9.3"

    //swipe refresh
    implementation 'androidx.swiperefreshlayout:swiperefreshlayout:1.1.0'

    //Datastore
    implementation "androidx.datastore:datastore-preferences:1.0.0"

    implementation "org.jetbrains.kotlin:kotlin-reflect:1.5.21"

    //get Dominant image color
    implementation 'androidx.palette:palette-ktx:1.0.0'

    implementation 'com.github.Toxa2033:ScaleAndSwipeDismissImageView:v0.7'


    // Timber
    implementation 'com.jakewharton.timber:timber:4.7.1'

    // Coroutines
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-core:1.5.0'
    implementation 'org.jetbrains.kotlinx:kotlinx-coroutines-android:1.5.0'

    // Coroutine Lifecycle Scopes
    implementation "androidx.lifecycle:lifecycle-viewmodel-ktx:2.3.1"
    implementation "androidx.lifecycle:lifecycle-runtime-ktx:2.3.1"

    // Coil
    implementation "io.coil-kt:coil:1.2.2"
    implementation "com.google.accompanist:accompanist-coil:0.7.0"

    //Dagger - Hilt
    implementation "com.google.dagger:hilt-android:2.38.1"
    kapt "com.google.dagger:hilt-android-compiler:2.38.1"
    implementation "androidx.hilt:hilt-lifecycle-viewmodel:1.0.0-alpha03"
    kapt "androidx.hilt:hilt-compiler:1.0.0"
    implementation 'androidx.hilt:hilt-navigation-compose:1.0.0-alpha03'

    //noinspection GradleCompatible
    implementation 'com.android.support:palette-v7:28.0.0'


    // Local Unit Tests
    implementation "androidx.test:core:1.4.0"
    testImplementation "junit:junit:4.13.2"
    testImplementation "org.hamcrest:hamcrest-all:1.3"
    testImplementation "androidx.arch.core:core-testing:2.1.0"
    testImplementation "org.robolectric:robolectric:4.3.1"
    testImplementation "org.jetbrains.kotlinx:kotlinx-coroutines-test:1.5.0"
    testImplementation "com.google.truth:truth:1.1.3"
    testImplementation "org.mockito:mockito-core:2.21.0"

    // Instrumented Unit Tests
    androidTestImplementation "junit:junit:4.13.2"
    androidTestImplementation "com.linkedin.dexmaker:dexmaker-mockito:2.12.1"
    androidTestImplementation "org.jetbrains.kotlinx:kotlinx-coroutines-test:1.5.0"
    androidTestImplementation "androidx.arch.core:core-testing:2.1.0"
    androidTestImplementation "com.google.truth:truth:1.1.3"
    androidTestImplementation 'androidx.test.ext:junit:1.1.3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'
    androidTestImplementation "org.mockito:mockito-core:2.21.0"
    androidTestImplementation 'com.google.dagger:hilt-android-testing:2.28-alpha'
    kaptAndroidTest 'com.google.dagger:hilt-android-compiler:2.38.1'
    testImplementation 'com.google.truth:truth:1.1.3'
    androidTestImplementation 'com.google.truth:truth:1.1.3'

    // Test helpers for LiveData
    testImplementation "android.arch.core:core-testing:1.1.1"

    // Test helpers for Room
    testImplementation "android.arch.persistence.room:testing:1.1.1"


    // If using indicators, also depend on
    implementation "com.google.accompanist:accompanist-pager-indicators:0.12.0"
    //Navigation
    implementation "androidx.navigation:navigation-compose:2.4.0-alpha07"
    
    }


```
