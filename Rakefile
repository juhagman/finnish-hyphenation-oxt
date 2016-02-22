task :default => :create

task :create do |t|
    chdir "dict-fi"
    sh "zip -r9 dict-fi.zip . --exclude .DS_Store"
    sh "mv dict-fi.zip ../dict-fi.oxt"
end

task :clean do |t|
    sh "rm dict-fi.oxt"
end
