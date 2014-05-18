task :default => [:install]

@packages = %w(ruby-test, cucumber, vim-mode, autocomplete-snippets, autocomplete-plus)

desc "Install Atom packages"
task :install do
  @packages.each {|pkg| system("apm install #{pkg}")}
end
