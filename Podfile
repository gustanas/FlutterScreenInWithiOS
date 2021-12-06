# Uncomment the next line to define a global platform for your project
platform :ios, '10.0'

# my_flutter is in the root folder
flutter_application_path = './my_flutter'
load File.join(flutter_application_path, '.ios', 'Flutter', 'podhelper.rb')

target 'MyFlutterApp' do
  install_all_flutter_pods(flutter_application_path)
end
