guard 'rspec', :cli => "--color --format nested" do
  watch(%r{^spec/.+_spec\.rb})
  watch(%r{^lib/(.+)\.rb}) { |m| "spec/unit/#{m[1]}_spec.rb" }
end
