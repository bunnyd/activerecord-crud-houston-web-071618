ENV["SINATRA_ENV"] ||= "development"

require_relative './config/environment'
require 'sinatra/activerecord/rake'

# Type `rake -T` on your command line to see the available rake tasks.
ActiveRecord::Base.logger = Logger.new(STDOUT)

task :console do
  Pry.start
end
