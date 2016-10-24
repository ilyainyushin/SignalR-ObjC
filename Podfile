project 'SignalR.Client.ObjC/SignalR.Client.ObjC.xcodeproj'
workspace 'SignalR.Client.ObjC'

target "SignalR.Client.iOS" do
    use_frameworks!
    platform :ios, '8.0'
    
    pod 'AFNetworking', '> 3.0'
    pod 'SocketRocket', '> 0.5'
    
    target "SignalR.Client.iOSTests" do
        pod 'OCMock'
        pod 'URLMock', '1.3.2'
    end
end

target :"SignalR.Client.OSX" do
    use_frameworks!
    platform :osx, '10.9'
    
    pod 'AFNetworking', '> 3.0'
    pod 'SocketRocket', '> 0.5'
    
    target :"SignalR.Client.OSXTests" do
        pod 'OCMock'
        pod 'URLMock', '1.3.2'
    end
end