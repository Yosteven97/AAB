1. Download bundletool at https://github.com/google/bundletool/releases or you can use bundletool inside this repo
2. Make folder, insert bundletool and aab file to folder
3. open terminal and running code below inside it
4. java -jar "bundletool-all-1.14.0.jar" build-apks --bundle="app-release.aab" --output="singleapp.apks" --mode="universal" 
5. rename singleapp.apks into singleapp.zip
6. unzip it and you can see universal.apk inside the folder