require 'bundler/gem_tasks'

require 'dotenv/tasks'
require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs << 'test'
  t.test_files = Dir.glob('test/**/*_test.rb').sort
  t.verbose = true
end

task :test => :dotenv
