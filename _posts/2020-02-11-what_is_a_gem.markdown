---
layout: post
title:      "What is a Gem?"
date:       2020-02-11 14:31:15 +0000
permalink:  what_is_a_gem
---


![](http://unsplash.com/photos/dpQqhZRyF7w)


If you are new to computer programming, starting a bootcamp or have actually ask yourself what a gem is, this article is for you. If you are like me, when you hear the word gem, your brain might automatically think about a beautiful, shiny rock. We must ‘code switch’, pun intended, to think about computer programming. 

In short, a gem is a packaged set of code, specifically Ruby, that executes certain functions in your programs. There are all different kinds of gems, but each one is a package manager. A package manager is a collection of software tools that standardizes the processes of installing, upgrading, configuring and removing computer programs for an operating system.

A couple of examples of gems I have currently used in the first few weeks of my programming bootcamp at Flatiron school, are Pry and ActiveRecord. Pry is an alternative IRB (Interactive Ruby Shell) or in other words, an environment where you can problem solve and debug your Ruby code. ActiveRecord is another gem used when working with relational SQL databases such as MySQl and Postgres. It provides ORM (Object Relational Mapping) to map Ruby objects into a database table. It allows you to utilize CRUD methods to create, read, update and delete data within a database. Other examples of gems include the ‘oj gem’ which is a JSON formatter or ‘rspec-rails’ which is used as a testing environment. For an extensive list gems, check out this website: https://rubygems.org/gems?page=2. To date, there are currently over 10,000 gems. 

To utilize a gem, first pick one with the functionality that you are looking for. In your IRB or terminal, type install gem_name.  For example, if you wanted to install the gem pry, type ‘install pry’ and press enter. This will load the code and dependencies necessary for your gem to function. Your project should have a gem file called gemfile.rb. You will need to require the gem in any files that you want it to run in. Type 'require gem_name' at the top of the file. To get a list of all of the gems locally installed type 'gem list'. If you want to uninstall a gem, type 'gem uninstall gem_name'. If I wanted to uninstall the pry gem, you would type 'gem uninstall pry'. For gem guides and directions, you can utilize this site: https://guides.rubygems.org/rubygems-basics/#installing-gems.

It is worthy to note that there can be security issues as a result of installing malicious gems. Since gems run their own code in an application, it gives them the opportunity to possibly compromise the user system or server. As best practice, download gems that are more popularly used and have reviews about them online. Gems can be a useful tool to help amplify the functionality of your application, from automating tasks, to changing the color of text and many other options. See the resources below for more information and help.

Resources: 

* Pry: https://github.com/pry/pry
* Active Record Basics: https://guides.rubyonrails.org/active_record_basics.html
* To find, install and publish gems: https://rubygems.org/
* For frequently asked questions about gems: https://guides.rubygems.org/faqs/



