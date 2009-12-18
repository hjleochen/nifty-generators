require 'rubygems'
require 'rake'
require 'echoe'

Echoe.new('leo-nifty-generators', '0.3.1') do |p|
  p.project        = "niftygenerators"
  p.description    = "A collection of useful generator scripts for Rails."
  p.url            = "http://github.com/hjleochen/nifty-generators"
  p.author         = 'H.J.Leochen'
  p.email          = "hjleochen (at) hotmail (dot) com"
  p.ignore_pattern = ["script/*"]
  p.development_dependencies = []
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
