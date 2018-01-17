# MicroBlog - A Ruby on Rails application

I built this application for using the
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

I blogged extensively about the experience in [another repo](https://github.com/gsaarinen/100-Days-Of-Code/blob/master/log.md) if you want to read up about that. Long story short - it was a lot of work but fun 😎


## Running Locally

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

## License

All source code in this app as well as the [Ruby on Rails Tutorial](http://railstutorial.org/)
is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.


For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).
