task :default => :lib

desc "Espectativas de la clase fraccion"
task :lib do
  sh "rspec -I. spec/fraction_spec.rb"
end
desc "Formato documentacion"
task :spec do
  sh "rspec -I. spec/fraction_spec.rb --format documentation"
end
desc "Test en formato html"
task :thtml do
  sh "rspec -I. spec/fraction_spec.rb --format html"
end