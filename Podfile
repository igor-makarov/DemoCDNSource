require 'cocoapods'

repo_url = 'https://cdn.jsdelivr.net/cocoa/'

unless Dir.exist?(File.expand_path('~/.cocoapods/repos/jsDelivr-Specs'))
  Pod::Command::Repo::AddCDN.run(['jsDelivr-Specs', repo_url])
end

source repo_url

target 'DemoCDNSource' do
  use_frameworks!
  pod 'RxSwift'
end
