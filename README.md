This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## [My Movies](https://rachel-blue.github.io/my-movies/#/)
View the webpage on github pages https://rachel-blue.github.io/ravenous/
This project utilizes the yelp api to search, and view resturants based off of several
search inputs to narrow results.

This was a tutorail project from Codecademy. 

This project was generated with React version 16.12.0 and `create-react-app`

## How to run the project locally
### `Local Setup`
1. Install Node.js (recommended version v13.4.0)
2. Clone this repo
3. Run `npm install` in the cloned repo's root
4. Run `npm start` to view the locally hosted site in the browser

### `Development server`
Run `npm start` for a dev server. 
Page will automatically open in browser, 
or navigate to [http://localhost:3000](http://localhost:3000) to view it in the browser.
The page will reload if you make edits.
You will also see any lint errors in the console.

### `Create a Build`
Run `npm run build` to build the project for produciton. The build artifacts will be stored
in the `build/` directory. 

### `Deploy to GitHub Pages`
To deploy to gh pages you must have read/write access to this repo. You must als have the
gh-pages dependency installed. 

`npm run deploy` 


## Project Notes
### `With more time`
Though the form does have a preventDefault on it, it's currently quite prone to input errors.
If the user doesn't select either 'Best Match', 'Highest Rated', or 'Most Reviewed', the api call will
fail when the search input is entered. Simmilarly the website will crash if a search for a food type is 
made without specifying a location. (However a location only will still yield results).

With more time I'd like to make the search feature a little more friendly. 
* Set 'Best Match' to be selected by default
* Stop form submission if at least location isn't selected
* Allow mouse click or keyboard 'enter' to submit the form




