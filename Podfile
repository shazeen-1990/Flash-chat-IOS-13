use_frameworks! :linkage => :static

platform :ios, '13.0'

target 'Flash Chat iOS13' do
  
  # Pods for Flash Chat iOS13
  
  
  #pod 'CLTypingLabel', '~> 0.4.0'
  pod 'FirebaseAuth'
  pod 'FirebaseFirestore'

end
post_install do |installer|
 installer.pods_project.targets.each do |target|
  target.build_configurations.each do |config|
   config.build_settings.delete 'IPHONEOS_DEPLOYMENT_TARGET'
  end
 end
end
