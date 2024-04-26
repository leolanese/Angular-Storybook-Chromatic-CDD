# AngularStorybookChromaticCDD

```js
// create new angular project
ng new Angular-Storybook-Chromatic-CDD

// Initialize Storybook in your project
npx sb init
```

## Up to this point, we should have

- Angular App running:
localhost:4200

- StoryBook running:
localhost:6006

- Chromatic running:
https://www.chromatic.com/start

- Setup a new project in a Repo (I used gitHub)
Then `Choose your Project` from Chromatic and select the repo:
https://github.com/leolanese/Angular-Storybook-Chromatic-CDD

## Publish Angular-Storybook-Chromatic-CDD’s Storybook

```js
// Get the Chromatic package
npm install --save-dev chromatic

// Publish your Storybook (using your token provied by Chromatic)
npx chromatic --project-token=chpt_XXXXXXXXXXXXXXXXX

// No 'chromatic' script found in your package.json
// selection 'Y' to add in the package.json
// "chromatic": "npx chromatic --project-token=chpt_XXXXXXXXXXXXXXXXX"
```

## Back to chromatic.com
Now,  you should see a new published Storybook

## Getting into Action!
Now Click: `Catch a UI change` to Spot UI changes

```js
//  src/stories/Header.components

git add --all ; git commit -m 'Modified Header for testing' ; git push
```

---


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.2.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
