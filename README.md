# Abgov Angular Material Theme

Angular Material Theme (Adding SCSS) for [Alberta ui-components](https://ui-components.alberta.ca/?path=/story/overview--page).

You can  use this theme, or create your own by customizing scss variables.

Please note that the version of Angular material theme is supported right now: 14 and below. 

## Install

Using yarn.
```sh
yarn add @abgov/angular-material-theme
```

Using npm.
```sh
npm install @abgov/angular-material-theme
````

## Usage
- Step 1: Under your main styles.css, add the below import: 
```
@import "@abgov/angular-material-theme/dist/angular-material/styles.min.css";
```

- Step 2: Under your main app.component.ts, add the below:
```
export class AppComponent {
  @HostBinding('class') class = 'goa-angular';
}
```

