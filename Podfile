#
#  Podfile
#

# Pod sources
source 'https://github.com/CocoaPods/Specs.git'

# Initial configuration
use_frameworks!
inhibit_all_warnings!

def testing_pods
    pod 'Expecta'
    pod 'Specta'
    pod 'Quick'
    pod 'Nimble'
end

target 'NGRValidatorTests-iOS' do
    platform :ios, '9.0'
    testing_pods
end

target 'NGRValidatorTests-MacOS' do
    platform :osx, '10.11.4'
    testing_pods
end
