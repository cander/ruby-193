This is an Ubuntu 14:04 image for doing development on Rails 4.1.x
application under Ruby 1.9.3.  It includes various packages for building
many native gems.  It also includes some extra packages we use in our app
like `libmysqlclient-dev` and `libqrencode-dev`.

This is intended as a base for a development environments.  As such, all the
tools and packages are left installed in the image - i.e., no effort has
been made to clean up any packages after the initial install to reduce the
image size.

Check out the
[Dockerfile](https://github.com/cander/ruby-193/blob/master/Dockerfile) for
the details.

Enjoy,
Charles.
