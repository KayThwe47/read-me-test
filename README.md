# [Matching-Site](https://www.sumlight-lab.com/)

This website is developed about job searching for vietnamese workers and employee searching for japanese companies. It is developed by **ISTD** company and is published by [Sumlight-Lab](https://www.sumlight-lab.com/).
Vietnamese Workers can easily find  14 specific industries jobs by this website. After fully registration, the worker can find the **jobs that matches with his status** at his dashboard.
## Preview
![alt text](https://github.com/NyeinYadana/read-me-test/blob/0a2721c14ba43781657fdca1158682546b724eba/ms-preview%20.png)

The setups steps expect following tools installed on the system.

* ruby '2.7.0'
* 'rails', '~> 6.0.3'
* Postgresql v-10

You can read about the ruby on rails [here](https://rubyonrails.org/).
## Project Installation
1. Clone the repository
* With HTTPs
``` ruby
https://gitlab.com/mistd/matchingsite/sumlight-lab.git

```
* With SSH
``` ruby
git@gitlab.com:mistd/matchingsite/sumlight-lab.git

```

2. Check your ruby version and rails version
``` ruby
ruby -v
rails -v
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
Then you can see a preview of the template in your browser at url localhost:3000.

## About
SUMLIGHT-LAB(サムライト･ラボ)とは 日本で技術を身に着けたい ベトナムワーカー のため、最適な仕事探しを応援する アセスメント 機能付きマッチングサイトです。

**サムライト・ラボはベトナム人労働者が日本で活躍 できるよう全力でサポートします！**

This website hiring workers who have **Tokutei Ginou Visa**.

This visa helps employers hire foreigners trained under 14 specific industries.

1. Agriculture
2. Aviation
3. Building cleaning
4. Construction
5. Electronics & Electrical equipment
6. Fishing
7. Food & drink manufacturing
8. Hospitality
9. Industrial machinery
10. Materials industry
11. Nursing
12. Restaurant catering/banqueting
13. Ship building
14. Vehicular maintenance
