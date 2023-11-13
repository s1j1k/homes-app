# Build your first Angular app
This repository contains the output from the Angular first app tutorial [here](https://angular.dev/tutorials/first-app).

## Homes app 
This app is a demo version of a real estate app displaying multiple properties in different cities.
The home page displays the different homes with an option to filter by city.
![Screenshot of the home page showing the available homes](image.png)
By clicking a the chosen property, users can view the details page where you can apply to live at the property.
![Screenshot of the details page for a home](image-1.png)

### Running the app locally
The list of homes is provided by a local web server (`json-server`).
1. First install `json-server` from npm using the following command
```npm install -g json-server```
2. 
```json-server --watch db.json```

Now you can run the app in a separate terminal.
```ng serve```