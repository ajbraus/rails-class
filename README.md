# Ruby on Rails

## Course Objectives & Competencies
* Master user-centered test-supported development
* Master debugging rails projects
* Master pushing rails projects to Heroku and debugging Heroku
* Master basic and advanced ActiveRecord associations and queries (`has_many through:`, polymorphism)
* Build an API in Rails using jBuilder
* Implement authentication in Rails with Devise and without
* Master the implementation of gems
* Use jQuery to make async requests to Rails API
* Build your own solo rails project

## Schedule

1. Week 1 - **The Power of Rails** - Generators & Outside-In & Single Resource Application
  * Class 1
    * rails new, rails g scaffold, rails g controller, rails g model
    * Two conventions: REST & OOP - Understand and memorize RESTful routes (resources)
  * Class 2
    * Opinionated vs unopinionated framework
    * Build and push a one a single resource app
  * Class 3
    * Associations with has_many
    * Build and push a two resource app with scaffolds and has_many.
1. Week 2 - **How to Code in Rails** - User-Centered Development
  * Class 1
    * User-centered development, start with the view, Errors are signposts
    * Build a single resource app
  * Class 2
    * Model validations
    * Continue building a single resource app
    * Add a second resource to the app with has_many
  * Class 3
    * ActiveRecord querying and has_many, belongs_to
    * Add a second resource to the app
1. Week 3 - **Look and Feel**
  * Class 1
    * Adding Assets
    * HAML
    * Bootstrap with CDM
    * Bootstrap smoke test, grid, typography
  * Class 2
    * Asset Pipeline 
    * Bootstrap with Gem
    * Bootstrap components, responsive helpers, forms
  * Class 3
    * Bootstrap with Bower
    * Bootstrap Javascript
    * Debugging w/ byebug and better_errors
1. Week 4 - **Protect Yourself with Minitest**
  * Class 1
    * Types of tests: Unit/Model, Integration/Controller, Acceptance/View. Focus on Contoller testing
    * Write model tests for two resource app
  * Class 2
    * Write controller tests for two resource app
  * Class 3
    * User-Centered, Test-Supported Development
    * Build full single resource app
1. Week 5 - **Advanced Routes & Associations**
  * Class 1
    * Nested and Named Routes
    * Double resource app
  * Class 2
    * Named Routes
  * Class 3
    * has_many :through & polymorphic associations
    * add comments has_many comments pattern
1. Week 6 
  * Class 1
    * has_secure_password, sign_up, session, current_user
  * Class 2
    * login, authenticate
    * Forgot Password pattern
  * Class 3
    * jQuery on Rails (async voting/commenting)
1. Week 7 - **Async and APIs with JSON & jQuery**
  * Class 1
    * Continue jQuery on Rails
  * Class 2
    * API Design & Jbuilder
  * Class 3
    * Start Project Week
  
1. Week 8 - Project Week
  
## Extra Resources

1. [Rails Guides: Routing](http://guides.rubyonrails.org/routing.html)
1. [Rails Guides: Associations](http://guides.rubyonrails.org/association_basics.html)
1. [Rails Guides: Nested Resources & Routes](http://guides.rubyonrails.org/routing.html#nested-resources)
1. [Rails Casts](http://railscasts.com/)
1. [Sinatra](http://www.sinatrarb.com/)
1. Action Cable (WebSockets in Rails)