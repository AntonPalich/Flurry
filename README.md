Flurry
======

Latest Flurry SDK

To use 7.0.0 or higher FlurrySDK from cocoapods, add this line in your Pods file:

```
  pod 'FlurrySDK', '~>7.0'
```


If you also want the FlurryAds SDK, you can define pods to install both subspecs:

```
  pod 'FlurrySDK/FlurrySDK', '~>7.0'
  pod 'FlurrySDK/FlurryAds', '~>7.0'
```


If you want to use FlurrySDK for Apple Watch Extension:    
```
target :"Your Apple Watch Extension Target" do 
   pod 'FlurrySDK/FlurryWatchSDK', '~>7.0'
end   
```
Don't forget to read how to track events correctly in Apple Watch Extensions  in FlurryiOSAnalyticsREADMExx.pdf  
