require "bundler/gem_tasks"
require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs << './'
  t.pattern = 'test/test_*.rb'
  t.verbose = true
end

task :default => :test
