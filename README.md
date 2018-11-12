Ruby Project Starter Template
====

This is a boilerplate template for a very simple Ruby project. It includes rspec, simplecov and a rubocop linter from Makers. [Pry](https://github.com/pry/pry) installed for debugging.

I've created a dummy 'starter-code' template so that all the test files can be linked up. Just change the names or delete and start from scratch.

*If you want a simple web app template with Sinatra and Capybara (for testing) try the branch called ruby_sinatra*

To Use:
---

- Clone or fork this project `git clone https://github.com/Whatapalaver/Simple_Ruby_Project.git`
- Change into the directory `cd Simple_Ruby_Project`
- Install dependencies `bundle install`
- You should also create a .gitignore file to prevent all the coverage files being sent to github: `echo "coverage" >> .gitignore`

To test:

- This command will run both the rspec tests and simplecov `bundle exec rspec`
- To view the coverage detail as a webpage run `open coverage/index.html`
