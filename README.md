# 🥳 httparty-ruby-automation 🥳
Test automation project using HTTParty for Back-end tests. We are going to use the API http://fakerestapi.azurewebsites.net/swagger/ui/index#/ to our tests.

## :point_right: Technologies :point_left:	

- HTTParty
- Ruby
- Cucumber
- RSpec

## :man_technologist:	Setting up the environment :woman_technologist:	
- It is necessary to install Ruby 
[Ruby](https://rubyinstaller.org/) 

- Then, let's open the terminal and write the following command to install the bundler:
```
gem install bundler --force
```

- To intall the dependencies, use:
```
bundle install
```

## Running the tests
```
cucumber -p prd -t @REST
```
