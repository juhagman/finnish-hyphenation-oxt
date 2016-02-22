task :default => :create
task :create do |t|
    sh "zip -r dict-en.zip dict-en/"
    sh "mv dict-en.zip dict-en.oxt"
end

task :clean do |t|
    sh "rm dict-en.oxt"
end
