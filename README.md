# LinkedIn Clone

Built using React.js, Redux, Firebase, React Player & Styled-Components

## Features

-   Login using Google (Firebase Authentication)
-   Create posts
-   Share photos and videos (React player for videos)
-   Like posts

## Running a local build

1. Clone this repo

2. Install the dependencies

    ```bash
    npm install
    ```
3. Setup Firebase

    - Create Firebase account
    - Create a new project
    - Copy your firebase project config from there

        - Paste the config details inside firebase/config.js file (Create a new file if it doesn't exist). Then export as firebaseConfig.

    ```bash
    export const firebaseConfig = {/* paste config here*/};
    ```

    - Setup authentication using Google

4. Run a production build of the project
    ```bash
    npm run build
    ```

### `npm install`

Installs the project dependencies

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Acknowledgements

Thanks to these creators for their tutorials and permission to use their code. If you want to build a similar project, check out these links:

-   [Free Code Camp on Youtube](https://www.youtube.com/watch?v=HimR8Xtz17U&pp=ygUObGlua2VkaW4gY2xvbmU%3D)
-   [Rafeh Qazi](https://github.com/CleverProgrammers)
-   [Sonny Sangha's Youtube Channel](https://www.youtube.com/@SonnySangha/featured)