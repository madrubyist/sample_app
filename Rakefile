#!/usr/bin/env rake
# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

SampleApp::Application.load_tasks

require File.expand_path('../config/application', __FILE__)
#require 'rake/dsl_definition'
require 'rake'

SampleApp::Application.send :include, ::Rake::DSL if defined? ::Rake::DSL 
