# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require_relative 'config/application'
require 'bundler/audit/task'
Bundler::Audit::Task.new

Rails.application.load_tasks
task default: 'bundle:audit'
