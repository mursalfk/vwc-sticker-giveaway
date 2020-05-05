# Free Sticker for a Pull Request

This project provides a command line interface (CLI) that allows you to encrypt your mailing address with a public key. We can then decrypt it with with our private key and mail you a sticker.

![](https://i.ibb.co/N22m19g/vwc-outlined.png)

## Instructions

Note: You must have Node 8 or later installed locally.
Note: Your commit must contain **only 1 file**. Verify that you did not change any existing code before making your PR.

1. `fork this repo`
1. `git clone` your fork url
1. Enter the project and run `npm install && git checkout -b mysticker`
1. `npm run address` and enter your address carefully.
1. Copy the encrypted address to a new file in `/stickers/<your-github-username>.txt`
1. `git add . && git commit -m <your-message>`
1. `git push origin mysticker`
1. Open new pull request on Github
1. Wait 1 to 2 weeks for the sticker 💌

Pro Tip: [Follow us on Twitter](https://twitter.com/vetswhocode) to learn more about Vets Who Code.

## Working

You can have a look at the inner workings [here](working.md).
