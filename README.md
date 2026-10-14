# android
Android project for learning creating button and how it will behave

start - 20261014

1. initial commit menggunakan https://www.geeksforgeeks.org/android/button-in-kotlin/ sebagai referensi

2. Menambah di build.gradle.kts: 
 2.a. implementation(libs.androidx.constraintlayout)
 2.b. implementation(libs.androidx.appcompat)

3. Menambah 2 poin di poin 2 di libs.versions.toml

4. Mengubah 
<style name="Theme.Androidbutton" parent="android:Theme.Material.Light.NoActionBar" /> 
menjadi 
<style name="Theme.Androidbutton" parent="Theme.AppCompat.Light.NoActionBar" />
pada themes.xml di path "app/src/main/res/values"

end - 20261014