# psd2html-job

You are applying for a PSD2HTML job at [Oceanhouse21](http://www.oceanhouse21.com)? Please follow these steps to submit your application:

## Step 1

Fork this project (build with [generator-gulp-webapp](https://github.com/yeoman/generator-gulp-webapp): https://github.com/oceanhouse21/psd2html-job

## Step 2

Clone the forked project to your local machine:

```
git clone https://github.com/yourname/psd2html-job
```

## Step 3

Download and install [Vagrant](https://www.vagrantup.com/) from here: [www.vagrantup.com/downloads](https://www.vagrantup.com/downloads) and also [VirtualBox](https://www.virtualbox.org/wiki/Downloads).

## Step 4

Log in to the Vagrant machine and start the web server:

```
cd psd2html-job
vagrant box add ubuntu/trusty64
vagrant up
vagrant ssh
cd /vagrant
gulp serve
```

## Step 5

Implement the [Bootstrap sticky footer template](http://getbootstrap.com/examples/sticky-footer/) into the app/index.html file. Don't forget to add the css snippets to app/styles/main.scss. Please leave Bootstrap installed via Bower.

To check your result visit [http://localhost:9000](http://localhost:9000).

## Step 6

Finally build the webapp in Vagrant

```ruby
## Stop the server with Ctrl + c and run gulp
gulp
```

## Step 7

Commit your work and send a pull request to [https://github.com/yourname/psd2html-job/pulls](https://github.com/yourname/psd2html-job/pulls)

## Applied

**That's it! We will check your work and get in contact with you asap.**
