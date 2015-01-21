# Overview #

Want to try Google's new Material Design with Rails but don't have the patience to set it up. This is for you. Materialize-rails is an empty rails app with the Materialize CSS Framework included into it.

The current Materialize gem is unavailable so I have manually included the latest Alpha build in the asset pipeline. Everything including the CSS, JS, Fonts and Icons work the last time I tested it.

### Usage

- Just `git clone`, `bundle install` and start the server using `rails server`
- The version of Materialize here is current as of 21 Jan 2015. If you want to include a newer version, just replace the files under `vendor/assets/` and rebuild the asset pipeline by running `rake assets:precompile RAILS_ENV=development`
- You can access the Materialize CSS docs at [Materialize CSS](http://materializecss.com). They have done a pretty awesome job.

###Licence
[WTFPL] (http://www.wtfpl.net) is a very permissive license for software and other scientific or artistic works that offers a great degree of freedom. In fact, it is probably the best license out there. Go crazy.
