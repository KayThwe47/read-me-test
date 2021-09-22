# [Matching-Site](https://www.sumlight-lab.com/)

This website is developed about job searching for vietnamese workers and employee searching for japanese companies. It is developed by **ISTD** company and is published by [Sumlight-Lab](https://www.sumlight-lab.com/).

## Preview


The setups steps expect following tools installed on the system.

* ruby '2.7.0'
* 'rails', '~> 6.0.3'
* Postgresql v-10

You can read about the ruby on rails [here](https://rubyonrails.org/).
## Project Installation
1. Clone the repository
``` ruby
https://gitlab.com/mistd/matchingsite/sumlight-lab.git

```

2. Check your ruby version
``` ruby
ruby -v
``` 
If your ruby version is not above the ruby version, you must change your ruby version.
* rbenv
``` ruby
rbenv install 2.7.0
``` 
* rvm
``` ruby
rvm install ruby-2.7.0
``` 

## Installation dependencies
1. Use bundle and yarn.
``` ruby
bundle install
yarn install
```
or

``` ruby
bundle && yarn
```
2. Database creation
``` ruby
rails db:drop
rails db:create
rails db:migrate
rails db:seed
```
or

You can use the following command instead of above the commands.
``` ruby
rails db:migrate:reset
rails db:seed
```

## Run command

``` ruby
rails server
```
or 

``` ruby
rails s
```
