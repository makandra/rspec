source :rubygems

gemspec

gem "flexmock", '>= 0.8.6', '<1'
gem "heckle", '>= 1.4.2'
gem "hoe", '>= 2.0'
gem "mocha", '>= 0.9.5', '< 0.12'
gem "rake", '>= 0.8.4'
gem "rr", '>= 0.10.0', '< 1'
gem "ruby-debug", :platforms => :mri_18
gem "ruby-debug19", "~> 0.11.6", :platforms => :mri_19
if RUBY_VERSION < '1.9'
  gem "nokogiri", '~> 1.5.0'
  gem 'rcov'
  gem 'fakefs', '~> 0.5.0'
else
  gem "test-unit", "1.2.3"
  gem "nokogiri", '>= 1.2.3'
end

case RUBY_VERSION
  when '1.9.1'; gem 'ruby-debug-base19', '0.11.23'
  when '1.9.2'; gem 'ruby-debug-base19', '0.11.24'
end
