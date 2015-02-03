# psd2html-job

You are applying for a PSD2HTML job at [Oceanhouse21](http://www.oceanhouse21.com)? Please follow these steps to submit your application:

## Step 1

Fork this project: https://github.com/oceanhouse21/psd2html-job/fork

*Note: the project is built with [generator-gulp-webapp](https://github.com/yeoman/generator-gulp-webapp)*

## Step 2

Clone the forked project to your local machine from terminal:

```
git clone https://github.com/yourname/psd2html-job
```

## Step 3

If not yet done, download and install [Vagrant](https://www.vagrantup.com/downloads) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads).

## Step 4

Log in to the Vagrant machine and start the web server from terminal:

```
cd psd2html-job
vagrant box add ubuntu/trusty64
vagrant up
vagrant ssh
# You need follow that install instructionst to install node (duration: ca. 5 min)
source <(curl -sL https://gist.githubusercontent.com/georgschlenkhoff/33d88a1c3ed710403575/raw/88221a2723e0c44b0d00a8cc7a430b148435d411/setup.sh)
cd /vagrant
gulp serve
```

## Step 5

Implement [Bootstrap's sticky footer template](http://getbootstrap.com/examples/sticky-footer/) into [app/index.html](https://github.com/oceanhouse21/psd2html-job/blob/master/app/index.html). Don't forget to add the [css snippets](http://getbootstrap.com/examples/sticky-footer/sticky-footer.css) to [app/styles/main.scss](https://github.com/oceanhouse21/psd2html-job/blob/master/app/styles/main.scss). Please leave Bootstrap installed via Bower.

To check your result visit http://localhost:9000.

## Step 6

Finally build the webapp from terminal:

```ruby
## Stop the server with Ctrl + C and run gulp
gulp
```

## Step 7

Commit your work and send a pull request to https://github.com/oceanhouse21/psd2html-job/pulls

## Applied

**That's it! We will check your work and get in contact with you asap.**
