task :default => :bin

desc "Espectativas de la clase fraccion"
task :bin do
  sh "rspec -I. spec/fraccion_spec.rb"
end
desc "Formato documentacion"
task :test do
  sh "rspec -I. spec/fraccion_spec.rb --format documentation"
end
desc "Test en formato html"
task :thtml do
  sh "rspec -I. spec/fraccion_spec.rb --format html"
end