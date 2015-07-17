# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require 'ci/reporter/rake/minitest'
task :minitest => 'ci:setup:minitest'

require File.expand_path('../config/application', __FILE__)

Rails.application.load_tasks
