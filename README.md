# React-I18next Crash Repro

This is a minimal reproduction case for a crash bug in react-i18next.

    Error in function Trans in ./node_modules/react-i18next/dist/es/Trans.js:36

    i18n is undefined

To run the repro yourself, `npm install && npm run develop` and then open http://localhost:8000/ and you should see an error dialog.
