<h4 align="center">
  Sending survey emails with nodemailer and SMTP Ethereal.
</h4>
<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/joao96/Survey4U?style=flat-square">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/joao96/Survey4U?style=flat-square">
  <img alt="License" src="https://img.shields.io/github/license/joao96/Survey4U">
</p>

<p align="center">
  <a href="#checkered_flag-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-setup">Setup</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#sparkles-how-to-use">How To Use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#page_facing_up-license">License</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#get-in-touch-monocle_face">Get in touch</a>
</p>

## :checkered_flag: Technologies

- [Node](https://nodejs.org/en/)
- [Express](https://expressjs.com/)
- [Nodemailer](https://nodemailer.com/about/)
- [handlebars](https://handlebarsjs.com/)
- [sqlite3](https://www.sqlite.org/index.html)
- [TypeORM](https://typeorm.io/#/)
- [Yup](https://github.com/jquense/yup)
- [Jest](https://jestjs.io/)

- [VS Code][vc] with [EditorConfig][vceditconfig] and [ESLint][vceslint]

## :information_source: Setup

In order to run this application, it's required that you have [Git](https://git-scm.com), [Node.js v10.16][nodejs] or higher + [Yarn v1.13][yarn] or higher installed on your computer. From your command line:

**Step 1:** Clone this repo & run a `cd` into project's folder.

**Step 2:** install node modules as below:

```
npm install
```

if you prefer:

```
yarn
```

**Step 3:**

```
yarn dev
```

Once the server is up, check out the [routes](https://github.com/joao96/Survey4U/blob/master/src/routes.ts) file.

<!-- ## :page_facing_up: License

<a href="https://github.com/joao96/the-simplest-todo/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/joao96/the-simplest-todo?style=flat-square">
</a>

<br />

This project is licensed under the MIT. -->

## :sparkles: How To Use

Once the server is up, you are able to:

- Create a user, providing a name and an email;
- Create a survey, providing a title and a description;
- List all surveys;
- Send emails to users, providing the survey id;
- Answer surveys;
- Calculate the NPS (Net Promoter Score) for a certain survey.

## :page_facing_up: License

<a href="https://github.com/joao96/the-simplest-todo/blob/main/LICENSE">
    <img alt="License" src="https://img.shields.io/github/license/joao96/Survey4U">
</a>

<br />

This project is licensed under the MIT.


## Get in touch! :monocle_face:

[![Linkedin Badge](https://img.shields.io/badge/-João%20Victor%20Poletti-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jvpoletti/)](https://www.linkedin.com/in/jvpoletti/)
[![Gmail Badge](https://img.shields.io/badge/-jvpoletti@gmail.com-ff512f?style=flat-square&logo=Gmail&logoColor=white&link=mailto:jvpoletti@gmail.com)](mailto:jvpoletti@gmail.com)

<br />

Made with :green_heart: by [João Victor Poletti](https://github.com/joao96)

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/
[vceditconfig]: https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig
[vceslint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
