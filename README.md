# npm / WordPress Boilerplate

## Prerequisites
The following is a list of things you’ll need before you can get started:
- [Git](https://git-scm.com/): Distributed version control system. (Pre-installed on MacOS)
- [npm](https://www.npmjs.com/get-npm): Node package manager. (Pre-installed on MacOS)

## Getting Started

### Clone repository
- **Option 1:** `$ git clone https://github.com/communify-agency/npm-wordpress-boilerplate.git`
- **Option 2:** Use a Git GUI. Two free apps include [Github Desktop](https://desktop.github.com) and [SourceTree](https://www.sourcetreeapp.com).

After cloning the repository, a folder named `npm-wordpress-boilerplate` will be created. Rename this to whatever makes sense for your project.

### Install WordPress
1) From the directory created above, type: `$ npm run wordpress` to run the npm script. The latest version of WordPress will be downloaded and extracted to the `dist` folder.
2) Visit your WordPress site to set up database and finish installation by visiting `localhost:8080` or whatever virtual host/address you have set up.

### Profit
From this point, you can begin creating and installing themes and plugins. Adjust `.gitignore` to track any custom themes and plugins.
