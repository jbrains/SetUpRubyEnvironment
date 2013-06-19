# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard :rspec, :cli => '--color --format doc' do
  watch(%r{^spec/.+_spec\.rb$}) { "spec" }
  watch(%r{^lib/(.+)\.rb$})     { "spec" }
  watch('spec/spec_helper.rb')  { "spec" }
end
