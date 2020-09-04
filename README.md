Taking the first step
You’ll need Node.js installed.

# Install at least v12.16.1 or higher as this is the oldest active LTS version

Only releases that are or will become an LTS release are officially supported
If you don't have Node installed, we recommend installing NVM to assist managing multiple active Node.js versions.

# Setup your project
Before installing dependencies, you’ll need to initialize a new NPM project. This will allow you to use the CLI to install dependencies in your project.

#To do this, run:

```$ mkdir webdriverio-test && cd webdriverio-test```

```$ npm init -y```

The -y will answer 'yes' to all the prompts, giving you a standard NPM project. Feel free to omit the -y if you'd like to specify your own project details.

# Install WebdriverIO CLI
If you want to use WebdriverIO in your project for integration testing, we recommend using the test runner. It comes with lots of useful features that makes your life easier.
Since WebdriverIO version 5, the testrunner is in the @wdio/cli NPM package.

# Now, install the CLI:

``` $ npm i --save-dev @wdio/cli```

Generate Configuration File
Next, you’ll generate a configuration file to store your WebdriverIO settings.
To do that, just run the configuration utility:

``` $ npx wdio config -y ```
That's it! The configurator will install all required packages for you and create a config file called wdio.conf.js.


# Start the Testrunner
## Now, time to run your tests!

### To do so, just run:

``` $ npx wdio wdio.conf.js ```
Hurray! The test should pass, and you can start writing integration tests with WebdriverIO.
