CONFIG = :snc
###########################################################################
case CONFIG
when :pqr
  GEMS_PATH = 'http://localhost/rubygems/'
  SPREE_PATH = 'file:///home/pqr/work/jaf/spree'
when :snc
  GEMS_PATH = 'file:///home/test/.rvm/gems/ruby-1.9.3-p392/bundler/gems/'
  SPREE_PATH = 'file:///media/Data/jaf/spree'
when :raul
  GEMS_PATH = 'http://localhost/rubygems/'
  SPREE_PATH= 'file:///home/raul/RubymineProjects/spree'  
else
  GEMS_PATH = 'http://rubygems.org'
  SPREE_PATH = 'https://github.com/radar'
end
########################################################################

source GEMS_PATH

gem 'spree_auth_devise', 	:git => "#{SPREE_PATH}/spree_auth_devise", :branch => '2-0-stable'

gemspec
