desc 'outputs hello to the terminal'

namespace :greeting do 
  task :hello do
    puts "hello from Rake!"
  end
  
  task :hola do
    puts "hola de Rake!"
  end
end 

task :environment do 
  require_relative "./config/environment.rb" 
end

task :console => :environment do
  Pry.start
end
 
namespace :db do 
  task :migrate => :environment do
    Student. 
  end
  
  task :seed =>  do
    puts "hola de Rake!"
  end
end