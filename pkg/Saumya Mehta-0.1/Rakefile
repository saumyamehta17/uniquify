require 'rubygems'
require 'echoe'
require 'rake'

Echoe.new('uniq_token', 0.1) do |p|
	p.description = 'This will generate a unique token'
	p.email       = 'smehta1289@gmail.com'
	p.url		  = 'https://github.com/sweetymehta/'
	p.name		  =  'Saumya Mehta'
	p.development_dependencies = []
end	

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each{ |x| load x }