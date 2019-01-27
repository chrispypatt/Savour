# Uncomment the next line to define a global platform for your project
platform :ios, 9.0

target 'Savour Prod' do
  pod 'Firebase'
  pod 'Firebase/Auth'
  pod 'Firebase/Core'
  pod 'Firebase/Database'
  pod 'SDWebImage/WebP'
  pod 'Firebase/Storage'
  pod 'FirebaseUI/Storage'
  pod 'FacebookSDK'
  pod 'FacebookSDK/LoginKit'
  pod 'Pulsator'
  pod 'Firebase/Messaging'
  pod 'OneSignal'
  pod 'AcknowList'
  pod 'GeoFire'
  pod "GTProgressBar"
  pod 'Firebase/Functions'
  pod 'Fabric', '~> 1.7.6'
  pod 'Crashlytics', '~> 3.10.1'
  pod 'LCUIComponents'



  # pod 'Firebase/Firestore'

  # Comment the next line if you're not using Swift and don't want to use dynamic 		frameworks
  use_frameworks!

end

target 'Savour Test' do
  pod 'Firebase'
  pod 'Firebase/Auth'
  pod 'Firebase/Core'
  pod 'Firebase/Database'
  pod 'SDWebImage/WebP'
  pod 'Firebase/Storage'
  pod 'FirebaseUI/Storage'
  pod 'FacebookSDK'
  pod 'FacebookSDK/LoginKit'
  pod 'Pulsator'
  pod 'Firebase/Messaging'
  pod 'OneSignal'
  pod 'AcknowList'
  pod 'GeoFire'
  pod "GTProgressBar"
  pod 'Firebase/Functions'
  pod 'Fabric', '~> 1.7.6'
  pod 'Crashlytics', '~> 3.10.1'
  pod 'LCUIComponents'


  # pod 'Firebase/Firestore'

  # Comment the next line if you're not using Swift and don't want to use dynamic 		frameworks
  use_frameworks!

end


target 'OneSignalNotificationServiceExtension' do
  pod 'OneSignal'
  use_frameworks!
end


post_install do | installer |
  require 'fileutils'
  FileUtils.cp_r('Pods/Target Support Files/Pods-Savour Prod/Pods-Savour Prod-acknowledgements.plist', 'Savour/Acknowledgements.plist', :remove_destination => true)
end
