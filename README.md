# NPM Package Demo

This is a companion project for [Build & publish your own private npm package for free](https://dev.to/mocasalter/build-publish-your-own-private-npm-package-for-free-47ol).

## Example

If you focus on the button via mouse, you won't see a focus outline. If you interact via keyboard, you will. 🎉

<img src="http://i.imgur.com/8zVT8We.gif" alt="Button Outline Demo" style="outline: 2px solid #c7bfc9" />

## Usage

1. `$ npm install` in both /tester-project and /smart-focus-ring
2.  `$ npm install -g parcel-bundler` to install parcel globally
3. In /tester-project, import smart-focus-ring either:
    1. Locally  
    ```bash
    $ npm link /YOUR-PATH/npm-package-demo/smart-focus-ring
    ```
    2. From your repo  
    ```bash
    $ npm i git+ssh://git@bitbucket.org:YOUR-USER-NAME/smart-focus-ring.git
    ```
    3) Or from npm  
    ```bash
    $ npm i smart-focus-ring
    ```
4. Run parcel `$ parcel index.html`
5. View in browser at the parcel gives you, probably localhost:1234
