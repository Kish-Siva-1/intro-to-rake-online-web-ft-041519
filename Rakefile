desc 'outputs hello to the terminal'

namespace :greeting do 
  task :hello do
    puts "hello from Rake!"
  end
  
  task :hola do
    puts "hola de Rake!"
  end
end 

task :console => :environment do
  Pry.start
end

namespace :greeting do 
  task :hello do
    puts "hello from Rake!"
  end
  
  task :hola do
    puts "hola de Rake!"
  end
end