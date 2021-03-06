# 42Intra API Scripts
Scripts for updating things on the [42 School](https://www.42.us.org/)  Intra Platform.

### Usage

1. [Install Ruby](https://www.ruby-lang.org/en/documentation/installation/)

2. To install Oauth2, type this in the command line:
```
gem install oauth2 -v 1.2.0
```
3. Either clone the whole repo or go to the script you want to use and hit the "raw" button to easily copy it into your favorite IDE (Sublime Text, Visual Studio Code, etc). Save the file.

4. Open the file. Set the UID and SECRET variables. Get them from the [42Intra API Settings](https://profile.intra.42.fr/oauth/applications) page.  Set any other relevant variables. Read the code! There's not a lot of protection to stop you from changing settings if you're an admin, so make sure you know what the code is doing.

5. Run the script by typing this in the command line:
```
ruby putFileNameHere.rb
```
