
環境構築

::

   bundle install

themeの新規作成

::

   export THEME_NAME='zinc'
   bundle exec compass create $THEME_NAME -r bootstrap-sass --using bootstrap

theme cssの更新

::

   cd $THEME_NAME
   bundle exec compass compile

theme cssの確認

::

   php -S 0.0.0.0:8000

   http://localhost:8000/?name=flatly

See Also

- https://github.com/twbs/bootstrap-sass#b-compass-without-rails
