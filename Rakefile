require 'rubygems'
require 'bundler'
Bundler::GemHelper.install_tasks

require "rspec/core/rake_task"

task :default => [:spec]

desc "Run all examples"
RSpec::Core::RakeTask.new(:spec)
