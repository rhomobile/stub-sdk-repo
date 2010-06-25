namespace :device do
  namespace :bb do
    task :production do
      chdir File.dirname(__FILE__)
      mkdir_p "deploy/bb/target/web"
      File.open("deploy/bb/target/web/blah.txt", "w" ) { |f| f.write "BLAH" }
      puts "SOME LOG INFO"
      puts "MORE LOG INFO"
      puts "THIS IS BB"
    end
  end
  
end
