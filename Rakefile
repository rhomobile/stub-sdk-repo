$start = pwd

namespace "device" do
  namespace "bb" do
    task :production do
      puts "PWD: #{pwd}"
      mkdir_p 'bin'
      mkdir_p 'deploy/bb/target/web'
      chdir 'deploy/bb/target/web'
      File.open("success.txt","w") { |f| f.write "success" }
      File.open("file2.txt","w") { |f| f.write "file2" }
      puts "SOME LOG INFO"
      puts "MORE LOG INFO"
      puts "THIS IS BB"
      chdir $start
    end    
  end
  namespace "wm" do
     task :production do
       puts "PWD: #{pwd}"
       mkdir_p 'bin/target'
       chdir 'bin/target'
       File.open("success.txt","w") { |f| f.write "success" }
       File.open("file2.txt","w") { |f| f.write "file2" }
       puts "SOME LOG INFO"
       puts "MORE LOG INFO"
       puts "THIS IS WM"
       chdir $start
     end    
   end
end
