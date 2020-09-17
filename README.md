<h1 align="center">
	Telegram chatbot with Dialogflow.
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/luiz-araujo/telegram-chatbot-by-dio.svg?color=34cb79">
  <img alt="Project programing languages count" src="https://img.shields.io/github/languages/count/luiz-araujo/telegram-chatbot-by-dio?color=34cb79">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/luiz-araujo/telegram-chatbot-by-dio?color=34cb79">
  <a href="https://www.linkedin.com/in/luiz-araujojr/">
    <img alt="Made by Luiz Araújo" src="https://img.shields.io/badge/made%20by-Luiz Araújo-%20?color=34cb79">
  </a>
  <img alt="GitHub license" src="https://img.shields.io/github/license/luiz-araujo/telegram-chatbot-by-dio?color=34cb79">
  <a href="https://github.com/luiz-araujo/telegram-chatbot-by-dio/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/luiz-araujo/telegram-chatbot-by-dio.svg?color=34cb79">
  </a>
</p>

<p align="center">
  <a href="#project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-run">How to run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#built-with">Built with</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">License</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#get-in-touch">Get in touch!</a>
</p>

## Project

This code was made in DIO's Bootcamp Node.js Web Developer.
A chatbot for Telegram was built using Dialogflow to assist user interactions.
The user will request suggestions for videos to work out.

## How to run

#### Requirements

To clone and run the application you will need:

- [Git](https://git-scm.com)
- [Node](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [Telegram Account](https://web.telegram.org/)
- [Dialogflow](https://dialogflow.cloud.google.com/)

Create bot

- Sign up Telegram (web, desktop or mobile client)
- Open the app or visit the website
- Search for @BotFather and start the conversation
- Submit the command /newbot and execute the instructions
- Save the token sent by @BotFather (We will use it in the code)

Create conversation's flow in [Dialogflow](https://dialogflow.com/)

- Create a new agent
- Choose an existing project or create a new one
- Click on the gear to configure the agent
- Click on the service id, you will be redirected to the GCP panel, click on the 3 dots below - actions and create a key to type json
- After downloading the key, replace the contents of the agent.json file with the contents of - your key
- Create a new intention called "Specific training"
- Add training phrases with some parts of the body
- Define entities of type "body" and their synonyms

To generate credentials

- [Youtube Credentials](https://console.developers.google.com/start/api?id=youtube)
- [Dialogflow Credentials](https://console.cloud.google.com/iam-admin/serviceaccounts) - Remember to go to the service account created by Dialogflow and generate your json file with credentials

From your command line:

```bash
# Clone this repository
$ git clone https://github.com/luiz-araujo/telegram-chatbot-by-dio.git

# Go into the folder repository
$ cd telegram-chatbot-by-dio

# Install dependencies
$ yarn install

# Save your own credentials in configs folder

# Run yarn start to start local server
$ yarn start
```

## Built With

- [Dialogflow](https://dialogflow.cloud.google.com/) — Dialogflow is a natural language understanding platform used to design and integrate a conversational user interface into mobile apps, web applications, devices, bots, interactive voice response systems, and so on.

## How to contribute

- Make a fork;
- Create a branch with your feature: `git checkout -b my-feature`;
- Commit changes: `git commit -m 'feat: My new feature'`;
- Make a push to your branch: `git push origin my-feature`.

After merging your receipt request to done, you can delete a branch from yours.

## License

This project is under the MIT license. See the [LICENSE](https://github.com/luiz-araujo/telegram-chatbot-by-dio/blob/master/LICENSE) for details.

## Get in touch!

<a href="https://www.linkedin.com/in/luiz-araujojr/" target="_blank" >
  <img alt="Linkedin - Luiz Araújo" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
</a>&nbsp;&nbsp;&nbsp;

---

Made with ❤️ by Luiz Araújo.
