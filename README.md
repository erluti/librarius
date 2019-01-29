# Librarius

Librarius is a [Ruby on Rails](https://rubyonrails.org/) class project for the
Spring 2019 Ruby CodeLouisville class.  We'll be working on it week-by-week
until we have a complete project.

## Catch Up

If you miss a week and aren't sure what we did, check the [CHANGELOG.md](https://github.com/magikid/librarius/blob/master/CHANGELOG.md) file.  I'll be documenting what we did each week there.  In addition, you can checkout that week's work to see the code that we wrote.

## Installation

To install, clone this repo and run bundle install inside the project folder to
install prerequisites.  After that, you should be able to start a rails server.

```bash
git clone git@github.com:magikid/librarius.git
cd librarius
bundle install
bin/rails server
```

## Usage

The structure of this application follows a typical Model-View-Controller
application.  Models are used for interacting with the database.  They can
be found in the `app/models` folder.  Controllers control the logical flow of
the website and combine models and views together.  Controllers are stored in
the `app/controller` folder. The views are specific to a controller and they are
what is displayed to the user.  They are stored in the
`app/view/controller_name/` folder and named after the method that they're used
with.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.  For minor changes, open a PR to the master branch.

### Mentors
If you're working on this without me, please create a new branch based on master for the week's work, make your commits, then open a PR back to master.  I'd appreciate it if in your changes you could update the [CHANGELOG.md](https://github.com/magikid/librarius/blob/master/CHANGELOG.md) with what you worked on but if you let me know what you did, I don't mind updating it.

## License
[MIT](https://choosealicense.com/licenses/mit/)
