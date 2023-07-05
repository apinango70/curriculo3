***INSTRUCCIONES PARA INSTALAR LA GEMA JEKYLL***

gem install bundler jekyll

jekyll new my-awesome-site

cd my-awesome-site


1.- borrar Gemfile.lock
2.- ejecutar bundle install


si da error con la gema webrick en ruby 3 ejecutar

bundle add webrick


3.- Ejecutar servidor localhost

bundle exec jekyll serve
# => Now browse to http://localhost:4000
