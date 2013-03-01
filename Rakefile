# task :default => [:docs, :samples, :adunit]

# task :adunit do 
#   sh "sprockets -I. manifest.adunit.js > build/adunit.js"
#   sh "sprockets -I. manifest.spec.js > build/specs.js"
# end

# task :samples do
#   Dir["samples/*.coffee"].each do |sample|
#     sh "coffee -o build -c #{sample}"
#   end
# end

# task :docs do 
#   sh "docco src/*.coffee samples/*.coffee"
# end

task :server do 
  sh "thin -R static.ru start"
end
