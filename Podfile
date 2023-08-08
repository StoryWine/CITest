source 'https://github.com/CocoaPods/Specs.git'
inhibit_all_warnings!
use_frameworks!

target 'CI' do
  platform :ios, '9.0'

  post_install do |installer|
    installer.pods_project.build_configurations.each do |config|
      config.build_settings["EXCLUDED_ARCHS[sdk=iphonesimulator*]"] = "arm64"
    end
  end

    # 网络
    #pod 'Alamofire'
    #pod 'Kingfisher'

    # 布局
    pod 'SnapKit'

    # 数据
    #pod 'SwiftyJSON'
    #pod 'ObjectMapper'
    
end
