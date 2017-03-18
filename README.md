# FastHub Translations [![Slack Status](https://fasthub.herokuapp.com/badge.svg)](https://fasthub.herokuapp.com)

This repository contains [FastHub](https://github.com/k0shk0sh/FastHub) strings. Take below steps if you are interested in translating.

## Contributing Guide

If you have a question in mind, feel free to come our public [Slack](https://fasthub.herokuapp.com) channel.

1. First fork the repository by clicking **Fork** button.
1. Clone your own forked repository to your computer with `git clone https://github.com/<your-username>/FastHub-translations` and cd into it `cd FastHub-translations`.
1. Create and switch branch by typing `git checkout -b <language>` where `<language>` is the language you want to translate to.
1. Create a folder named `values-<language-code>`, where `<language-code>` is your 2 letter code for your language. For example `values-es` for Spanish, `values-fr` for French.
1. Copy `values/strings.xml` to inside `values-??` folder with `cp values/strings.xml values-??/`.
1. Open `values-??/strings.xml` on your editor of choice.
1. Translate and keep in mind those important points.
	1. Obey XML format. So, `<string name="do-not-change">ONLY TRANSLATE HERE</string>`.
	1. Don't translate Git terms. Such as *pull request, push, commit, branch*...
	1. There are special characters and variables. Such as `\n` for newline, `\t` for tab. Keep them in the same position in your sentences. Do not delete them!
	1. Don't translate lines that contain `translatable="false"` statement.
	1. Don't add extra spaces or periods anywhere. Don't delete current ones. Keep them as is.
1. Once finished the translations, add files to the git index with `git add values-??/strings.xml` and commit it with `git commit -m 'Language: Strings translated'`.
1. Then push your local changes to your forked repository branch by typing `git push origin <language>`.
1. Finally, create a pull request from your branch to our *master* with **Pull Request** button.

# Translators

- **English**: Default
