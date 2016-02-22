task :default => :create

task :create do |t|
    chdir "dict-en"
    sh "zip -r9 dict-en.zip . --exclude .DS_Store"
    sh "mv dict-en.zip ../dict-en.oxt"
end

task :clean do |t|
    sh "rm dict-en.oxt"
end
