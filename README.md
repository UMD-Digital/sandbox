# DUG - Sass (Syntactically Awesome StyleSheets)


## Installation

**Install Ruby**

[Ruby installation link](https://www.ruby-lang.org/en/documentation/installation)


**Check Ruby Version**

`ruby -v`

**Install Sass Gem** 

`gem install sass`

**Install Sass Gem with Admin Permissions** 

`sudo gem install sass`

**Check Sass Version**

`sass -v`

**Update Sass**

`gem update sass`



## Sass Compile

**Sass Configurations**

Config.rb has the basic options and was created using the initialize compass project 

`compass init`

**Watch Sass Folder**

`sass --watch`



## SASS Output Options

**Using Command Line**

`compass watch --output-style=compressed`


**Using config.rb**

In the config.rb file line 9 the output style is set to **Expanded** but can be changed to the options below

`output_style = :expanded or :nested or :compact or :compressed`
