namespace :greeting do
  desc 'outputs hello to the terminal'
  task :hello do
    puts "hello from Rake!"
  end

  desc 'Colloquializes hello'
  task :slang do
    puts "what it do blood?"
  end
  desc 'outputs hello in spanish'
  task :hola do
    puts "Hola, como estas?"
  end
end

namespace :db do
  desc 'migrate changes to your database'
  task :migrate => :environment do
    Student.create_table
  end
end

task :environment do
  require_relative './config/environment'
end
