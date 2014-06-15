task :default => [:install]

@packages = %w(ruby-test cucumber vim-mode language-ruby-on-rails autocomplete-snippets autocomplete-plus autocomplete-paths language-haml rubymotion)

desc "Install Atom packages"
task :install do
  @packages.each {|pkg| system("apm install #{pkg}")}
end
