# Build your first Angular app
This repository contains the output from the Angular first app tutorial [here](https://angular.dev/tutorials/first-app).

This covers the following topics:
1. Using `npm install` to install dependencies.
2. Using `ng serve` to build and serve Angular app locally for testing.
3. Using `ng generate home` to generate `home` component.
4. Editing template HTML code and adding `styleUrls` to add stylesheets in a separate file.
5. Adding additional components and importing them into the `home` component.
6. Using `ng generate interface <interface name>` to generate an interface, adding properties, and importing into `home` component.
7. Using `@Input()` decorator to pass data to a component for customization.
8. Adding property binding to a component tag as in `[attribute] = "value"` to indicate the assigned value should be treated as a property from the component class and not a string value.
9. Interpolating values into a template using `{{ expression }}` format.
10. Using `*ngFor` to list objects in a component.
11. Generating and using Angular services and injecting into components to read data from it. Adding routes to the application to include multiple pages in the application.
12. Adding a form to the app.
13. Adding search feature to the app.
14. Adding HTTP communcation to the app.


## Homes app 
This app is a demo version of a real estate app displaying multiple properties in different cities.
The home page displays the different homes with an option to filter by city.
<img width="1287" alt="Home page showing list of homes" src="https://github.com/s1j1k/homes-app/assets/89644676/73489ca8-df14-43a9-aeff-1d52a33d6176">

By clicking a the chosen property, users can view the details page where you can apply to live at the property.
<img width="1288" alt="Details page for one of the homes" src="https://github.com/s1j1k/homes-app/assets/89644676/a79af610-b451-4615-93ef-0808b588a626">

### Running the app locally
Before you start you need to install the correct version of `node.js` required by Angular.
With `node.js` and `npm` installed, install the latest version on angular using

```
npm install -g @angular/cli
```

The list of homes is provided by a local web server (`json-server`). To set up the JSON server follow the below:
1. Install `json-server` from npm using the following command

```
npm install -g json-server
```

2. Start the server before running the Angular app

```
json-server --watch db.json
```

In a separate terminal, build and serve the Angular app.
1. Install the dependencies.
```
npm install
```
2. Build and serve the app.
```
ng serve
```
