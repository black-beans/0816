guard :coffeescript, :input => 'src/coffeescripts', :output => 'public/javascripts'

guard 'haml', :output => 'public', :input => 'src/haml' do
  watch %r{^src/haml/.+(\.html\.haml)}
end

guard 'compass' do
  watch(%r{^src/(.*)\.scss})
end

guard 'livereload' do
  watch(%r{public/stylesheets/(.+\.css).*$})
  watch(%r{public/javascripts/(.+\.js).*$})
  watch(%r{public/(.+\.html)$})
end
