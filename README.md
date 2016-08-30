windows_package 'PuTTY version 0.60' do
  source 'http://the.earth.li/~sgtatham/putty/latest/x86/putty-0.60-installer.exe'
  installer_type :inno
  action :install
end
