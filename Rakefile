task :default => [:install]

@packages = %w(ruby-test language-ruby-on-rails cucumber vim-mode autocomplete-snippets autocomplete-plus autocomplete-paths)

desc "Install Atom packages"
task :install do
  @packages.each {|pkg| system("apm install #{pkg}")}
end
