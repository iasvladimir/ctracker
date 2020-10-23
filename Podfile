# Uncomment the next line to define a global platform for your project
source 'https://cdn.cocoapods.org/'
platform :ios, '13.0'

inhibit_all_warnings!
use_frameworks!

def firebase 
  pod 'Firebase/Analytics'
  pod 'Firebase/Crashlytics'
end

target 'ctracker' do
  # Pods for ctracker
  pod 'SwiftLint'
  firebase

  target 'ctrackerTests' do
    inherit! :search_paths
  end

end
