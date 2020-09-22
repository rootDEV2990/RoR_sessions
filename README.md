# User Log In Page and Sessions with Rails 6
> Taking the sessions and cookies for a test drive. Follow my commits as i try and get this user log in and sessions going xD! Check out the feature branch you know #gitflow ;)

## Built With

- Ruby on Rails
- sqlite3 for the local development
- VScode
- Rubocop

## Guide

1. generate model for users, cd into /project_dir/ and type this in terminal
    rails g model User name:string email:string password_digest:string password_confirm:string
2. add method in model/User.rb
    has_secure_password
3. migrate database type in terminal 
    rails db:migrate


## Author

👤 **Miguel Angel Enciso Sanchez**

- Github: [@rootDEV2990](https://github.com/rootDEV2990)
- Twitter: [@m29902](https://twitter.com/m29902)
- Linkedin: [linkedin](https://www.linkedin.com/in/miguel-enciso-6474741a1/)
- Medium: [medium](https://medium.com/@website.dev)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- Microverse
- Heroku
## 📝 License

This project is [MIT](LICENSE) licensed.

