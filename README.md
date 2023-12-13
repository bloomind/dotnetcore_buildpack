# dotnetcore_buildpack
A Dotnet Core Buildpack for use with Scalingo to build aspnetcore 7.0 app

You can find reference [here](https://doc.scalingo.com/platform/deployment/buildpacks/custom)

It has been tested with Galaxy.

# Debugging 

Launch this command `docker run --pull always --rm --interactive --tty -e STACK=scalingo-22 -v ./dotnetcore_buildpack:/buildpack -v ./Galaxy_back:/build scalingo/scalingo-22:latest bash` in a directory containing the directory with the app to build and this one.