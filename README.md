# Meme-Share-App

- This app displays you new memes by using an data from an API.
- You can also share the url of that image to your frieinds via different text messaging apps.

# API LINK
https://meme-api.herokuapp.com/gimme

# API LIBRARY
Volley is an HTTP library that makes networking for Android apps easier and most importantly, faster. Volley is available on GitHub.

 You need to add the below dependency in your gradle build file:
 
 dependencies {
    
    implementation 'com.android.volley:volley:1.2.1'
    
 }

# Glide Library
Glide is a fast and efficient open source media management and image loading framework for Android that wraps media decoding, memory and disk caching, and resource pooling into a simple and easy to use interface.

repositories {
  
    google()
  
    mavenCentral()
  
}

dependencies {
  
    implementation 'com.github.bumptech.glide:glide:4.12.0'
  
    annotationProcessor 'com.github.bumptech.glide:compiler:4.12.0'
  
}
