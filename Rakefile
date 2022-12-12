require "bundler"

task default: "serve"

desc "Serve the Jekyll site"
task :serve do
  system('bundle exec jekyll serve')
end

desc "Build the Jekyll site"
task :build do
  system('bundle exec jekyll build')
end

desc "Check for broken links"
task :brokenLinks do
  puts "Checking for broken links..."
  system('bundle exec jekyll build')
  system('bundle exec htmlproofer --check-html _site')
end
