# Panini Starter Kit
This repo is a starter kit to use Foundations Panini flat file compiler powered with GULP.
Based on Foundation 6 Framework: [foundation-6.4.2-custom](lib/foundation-6.4.2-custom)

## Usage

To use this Kit, your computer needs:

- [NodeJS](https://nodejs.org/en/) (0.12 or greater)
- [Git](https://git-scm.com/)

Download repo with Git:

`git clone https://github.com/larsmaeder/larsmaeder-panini-starterkit.git projectname`

Then open the folder in your command line, and install the needed dependencies:

```bash
cd projectname
npm install
```

Run `npm start` to run Gulp. Your finished site will be created in a folder called `dist`, viewable at this URL:

```
http://localhost:8000
```

To create compressed, production-ready assets, run `npm run build`.