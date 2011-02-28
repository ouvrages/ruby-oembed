require File.expand_path(File.join(__FILE__, '../lib/oembed/version'))

begin
  require 'jeweler'
  
  Dir[File.join(File.dirname(__FILE__), "lib/tasks/*.rake")].sort.each { |ext| load ext }
  
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "ruby-oembed"
    gemspec.version = OEmbed::Version
    gemspec.homepage = "http://github.com/judofyr/ruby-oembed"
    gemspec.summary = "oEmbed for Ruby"
    gemspec.description = "An oEmbed consumer library written in Ruby, letting you easily get embeddable HTML representations of supported web pages, based on their URLs. See http://oembed.com for more information about the protocol."
    gemspec.license = "MIT"
    gemspec.email = "arisbartee@gmail.com"
    gemspec.authors = ["Magnus Holm","Alex Kessinger","Aris Bartee","Marcos Wright Kuhns"]
    gemspec.add_development_dependency("json")
    gemspec.add_development_dependency("xml-simple")
    gemspec.add_development_dependency("rspec", ">=2.0")
    
    gemspec.rdoc_options = %W(
      --main README.rdoc
      --title #{gemspec.full_name}
      --inline-source
      --exclude tasks
      CHANGELOG.rdoc
    )
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: gem install jeweler"
end
