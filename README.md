# React App Admin Simple Read File Text

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### `npm test`

See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

### `npm run eject`

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)


## Features App
### I. Admin Panel

- Only the admin can log in/access
- Admin Can:
  + Upload text files with specific type and specific language type and order can be added/edited in admin panel. admin should be able to
  + Change the complete theme and color
  + Types/Category added/edited in the admin panel. Type/Category will be displayed in the combo
  + File text with Space/Paragraph in txt file should be preserved.
  + Languages can added/edited in the admin panel. Languages will be displayed in the combo
  + Sub-category will can added/edited in the admin panel. Sub-Type/Sub-Category will be displayed in the combo
  + Default language, Default category, Default sub-category will be selected in settings

### II. Main Page

- Load the default language, default category, all the content titles on the left and 1st content on the right
- Any user will be search box and with category and sub-category as boxes. sub-category may or may not come as per the user added
- Handle Navigation arrows
- Number of occurrences on the content,...
- Highlight the keywords on the left hand side on search.
- On clicking the search result, ticket mark should come to note he has selected the file, right hand side content should be loaded and cursor should go to 1st occurences of the highlight keyword
- arrows will be available to navigate to next occurence inside the content
- Next and Previous buttons will be used to navigate to the next file