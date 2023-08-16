# Admin Dashboard App

### Some Dependencies and packages used

- React
- [Material UI](https://mui.com/)
- [FullCalendar](https://fullcalendar.io/docs/react)
- [React Router](https://reactrouter.com/en/main)
- [Nivo chart](https://nivo.rocks/)
- [Google Font](https://fonts.google.com/specimen/Source+Sans+3?query=source+)
- [Raect-pro-sidebar](https://www.npmjs.com/package/react-pro-sidebar)
- [Formik](https://formik.org/) to handle our form

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

### useful extentions

- [tailwind shades](https://github.com/bourhaouta/vscode-tailwindshades) helped to generate color paletes

### Observations

in the css, one may note that the rules for the scrollbar are not encouraged for project destined for production. because at the time of writting this, not all browser support this

### Architectural concerns

the organisation of the codebase is mainly made by features
