# Micro Reddit 

>This project is a Ruby on Rails project. The exercise is based on building with active records & how validations and associations work between different models generated within the Ruby on Rails framework.

# Getting Started
You should have Ruby & Ruby on Rails already installed on your machine before you begin.

To get a local copy of the repository please run the following commands on your terminal:

```
$ cd <folder>
```

```
$ git clone git@github.com:jacobrees/Micro-Reddit.git
```

To install all of the ruby dependencies run the command `bundle install`

```
$ bundle install
```

To migrate the database run 'rake db:migrate' you will have to do this in order to do the next steps.

```
$ rake db:migrate
```

# Testing
To launch the rails console inside of your terminal you will need to navigate into the repository you have just cloned. You will do this by using `cd` inside of your terminal. Once you are inside of this folder run the command `rails console` and this start the interactive console. 

Below shows the following commands you will need to run to achieve this:

```
$ cd Micro-Reddit
```

```
$ rails console
```

### Commands 

-  Create a new user 

```
 User.create({username: 'jacobe', email: 'jacobe@Rees', password: '12234' })
```
#### Requirement 
-> username , email and password 


-  Create a new post 

```
 Post.create({title: 'post1', body: 'post stuff', user_id: 1 })
```
#### Requirement 
-> title, body and user_id
-> user_id must exist in the users table


-  Create a new comment 

```
 Comment.create({body: 'comment body', user_id: 1, post_id: 1 })
```
#### Requirement 
-> body, user_id and post_id 
-> user_id & post_id must exist in the users and posts table

## Built With

- Ruby (Version - 2.7.0)
- Ruby on Rails 5.2.4.3


## Authors

👤 **Jacob Rees**

- Github: [@jacobrees](https://github.com/jacobrees)
- Linkedin: [jacob-rees-a6507b1a6](https://www.linkedin.com/in/jacob-rees-a6507b1a6/)


👤 **Razika Rahal**

- Github: [@rahalrazika](https://github.com/rahalrazika)
- Linkedin : [Razika Rahal](https://www.linkedin.com/in/razika-rahal-85539bbb/)
- Twitter: [@RereRere055](https://twitter.com/RereRere055)


## 🤝 Contributing

Contributions, issues and feature requests are welcome!

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Project inspired by Microverse Program
