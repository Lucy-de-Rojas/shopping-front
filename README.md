# Shopping List Frontend For Practicing Deployment

When deploying the front end:

- Make sure you set the `REACT_APP_BACKEND_URL` environment variable (because at build time, the build process will take the values available and inject/hard code them into the generated files).
- Have a look at the typical build settings (for a typical project folder structure): https://docs.netlify.com/configure-builds/common-configurations/#create-react-app
