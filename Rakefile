require 'rake/testtask'

Rake::TestTask.new do |t|
  t.libs = ["lib", "test"]
  t.test_files = FileList['test/*_test.rb']
  t.warning = false
end

desc "Run tests"
task :default => :test
