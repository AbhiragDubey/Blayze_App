# Uncomment the next line to define a global platform for your project
 platform :ios, '13.0'

target 'BlazeVendor' do
  # Comment the next line if you don't want to use dynamic frameworks
  use_frameworks!
  pod 'Alamofire'
  pod 'SpinKit'
  pod 'IQKeyboardManagerSwift'
  pod 'MBProgressHUD'
  pod 'CountryPickerView'
  #pod 'Kingfisher'
  pod 'SwiftPhoneNumberFormatter'
  pod 'ActionSheetPicker-3.0'
  pod 'GoogleMaps'
  pod 'GooglePlaces'
  pod 'GooglePlacesSearchController'
  pod 'GrowingTextView', '0.7.2'
  pod 'DKImagePickerController', :subspecs => ['PhotoGallery', 'Camera', 'InlineCamera']
  pod 'SDWebImage'
  pod 'EzPopup'
  pod 'FloatRatingView', '~> 4'
  pod 'Firebase/Core'
  pod 'Firebase/Database'
  pod 'Firebase/Storage'
  pod 'Firebase/Auth'
  pod 'Firebase/Firestore'
  pod 'Firebase/Messaging'
  pod 'MessageKit'
  pod 'HGCircularSlider'
  pod 'AEOTPTextField'
  #pod "KRPullLoader"
  pod "KRPullLoader"
  pod 'Firebase/Crashlytics'
  pod 'QRCodeReader.swift', '~> 10.1.0'
  pod 'Stripe'
  pod 'StripeIdentity'
  # Pods for BlazeVendor

  target 'BlazeVendorTests' do
    use_frameworks!
    inherit! :search_paths
    # Pods for testing
  end

  target 'BlazeVendorUITests' do
    use_frameworks!
    # Pods for testing
  end

end

post_install do |installer|
    installer.pods_project.build_configurations.each do |config|
        config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
    end
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['IPHONEOS_DEPLOYMENT_TARGET'] = '13.0'
        end
    end
end
