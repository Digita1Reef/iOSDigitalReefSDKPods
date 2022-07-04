# iOSDigitalReefSDKPods
CocoaPods library for DigitalReef's SDK.

Steps to install

1. create xcode project
2. open terminal
3. navigate to project's directory
4. run these following cmds
  1. create Podfile in the project's directory. 
      
      pod init 
  2. open Podfile 
  3. add the following code in the Podfile and save it.

      platform :ios, '12.0'
      
      target 'TestDRPods' do
      
        use_frameworks!
        
        pod 'iOSDigitalReefSDKPods', :git => 'https://github.com/Digita1Reef/iOSDigitalReefSDKPods'
        
      end
  4. pod install
5. Then open project's .xcworkspace.

Note: 
1. To update pod use cmd

    pod update
2. To install a specific version in pod library use the cmd as follows

   for ex: 
   
   pod 'iOSDigitalReefSDKPods', :git => 'https://github.com/Digita1Reef/iOSDigitalReefSDKPods', :tag => '4.6.0'​
