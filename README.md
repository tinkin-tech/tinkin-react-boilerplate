## Tinkin React Boilerplate 

## Description

This is a simple React Boilerplate created by Tinkin in order to help you with a basic folder structure and configuring useful libraries. You can use it as a base for the project and customize it as you want.

>! Remember to delete this README when you create your website.

## Technologies used

* **JS**: It was chosen `JS` and not `TypeScript` for simplicity of configuration and for being more known and easier to use than `TypeScript`.
* **SASS**: We chose `SASS` and not `CSS` for the advantages it offers such as `imports` and the structure in `tree` to put the styles.
* **React Testing Library**: We chose `React Testing Library` and not `Enzyme` for the reasons described in the official documentation of [React Testing Library](https://testing-library.com/docs/react-testing-library/intro#the-problem).

> If you are not familiar or do not like any of these technologies used you can change them and configure the boilerplate as you feel more comfortable.

## Boilerplate Structure

* **assets/**: This folder contains all the images used in the project, you can add folders like `images` and `icons` to give it a better structure.
* **components/**: In this folder as its name indicates all the components of the application are located, for this boilerplate a simple component was created for example.
* **constant/**: In this folder should be put all the constants of the application, as texts or enums needed.
* **scss/**: In this folder are the styles of the application, if you want you can create additional folders inside it to give more structure as: `components` to place the styles only referring to the components of the application.
* **tests/**: As the name says, in this folder are located the tests of the application components.

You can add or remove the folders you think necessary.

## Install Dependencies

You can use [nvm](https://github.com/nvm-sh/nvm) to install the `node` version used when creating the boilerplate by executing the following command:

```
nvm use
```

To install the dependencies you can use `yarn` or `npm`.

```
yarn install
```
o
```
npm i
```

## Run the project

To run the project in development mode run the following command:

```
yarn start
```
o
```
npm run start
```

This will open a tab in the browser configured by default on port `3000`.

You can see all available scripts in the `package.json` file.

## Automatic unit tests

The boilerplate is configured with automatic testing using the `React Testing Library`. If you haven't heard of this library before you can see its official documentation [here](https://testing-library.com/docs/react-testing-library/intro).

To run the tests use the command:

```
yarn test
```
o
```
npm t
```

If you don't want to use `React Testing Library`, you can remove it from the dependencies and install the library of your choice.