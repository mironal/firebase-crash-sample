# Uncomment the next line to define a global platform for your project
platform :ios, '9.3'
# Comment the next line if you don't want to use dynamic frameworks
use_frameworks!

target 'App' do

  # Pods for App

  # v6.20.0 does crash.
  pod 'Firebase/Analytics', '6.20.0'

  # v6.15.0 does not crash.
  #pod 'Firebase/Analytics', '6.15.0'

  target 'AppTests' do
    # Pods for testing
  end

  target 'firebase-crash-sample' do
    inherit! :complete

  # Pods for firebase-crash-sample

    target 'firebase-crash-sampleTests' do
    inherit! :search_paths
    # Pods for testing
    end

    target 'firebase-crash-sampleUITests' do
    # Pods for testing
    end

  end
end

