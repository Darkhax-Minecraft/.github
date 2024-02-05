# Contributing Guidelines
Thank you for expressing interest in this project! Bug reports, feedback, pull requests, and other forms of contribution are welcomed!

## 🚀 Pull Requests
Pull requests are generally welcomed however it is often best to open an issue to discuss your intended changes before working on them. We also ask you keep the following in mind.

- Pull requests that port the mod to other versions of the game are no longer being considered. While we appreciate the sentiment these types of pull requests disrupt our workflow and can often cause more work than they save.
- Minor text changes that don't affect the compiled mod will be denied. For example fixing a localization error is fine but fixing a typo in the readme file will be declined. You can still open an issue to let us know about the text errors.
- We are not interested in Pull Requests that have been automated or written whole or in part by bots or AI. 

## 💌 Feature Requests
Feature requests are welcomed and can be submitted by opening an issue using the `⭐ Feedback` category. All feedback will be carefully considered however not all feedback can be accepted. Don't let this discourage you though, we love to hear your feedback! Just make sure to follow the template to the best of your ability and include all of the relevant details. 

## 🗣️ Translations / Localizations
Translations are very appreciated! You can submit a translation by opening a Pull Request. If you are unfamiliar with the Pull Request system you can also open an issue using the `⭐ Feedback` category and a project maintainer will sort it out.

### ⚠️Compression Warning⚠️
> If you open up the `.jar` file you will notice our language files are compressed. This is done to reduce file size and make our mods faster to download. This process is completely automatic and you should **NOT** include the compression in your PR. The normal `en_us.json` file that has not been compressed can be found on GitHub. You can also use a tool like [JsonLint](https://jsonlint.com/) to expand the JSON text. You can learn more about how we compress the JSON files [here](https://github.com/Darkhax-Minecraft/Bookshelf/blob/1.20.2/gradle/minify_jsons.gradle).    
> **Compressed Example**
> ```json
> {"example.property.name":"Hello World!","example.property.name.two":"Hello Again!"}
> ```
> **Uncompressed Example**
> ```json
> {
>   "example.property.name": "Hello World!",
>   "example.property.name.two": "Hello Again!"
> }
> ```
