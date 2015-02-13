require "bundler"
Bundler.setup

require "rake"
require "rspec/core"


RSpec::Core::RakeTask.new("spec") do |spec|
  spec.pattern = "spec/**/*_spec.rb"
end

task :default => :spec