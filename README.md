# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


STEPS OF DEVELOPMENT :
I HAVE USED THE WORD 'TODO' INSTEAD OF THE WORD WIDGET FOR MY EASE AND BETTER UNDERSTANDING OF MY OWN.

step1: First i have used the power of context api and useContext hook for the management of state. I have made a jsx file and exported the context, the provider and the method which takes the context along with the useContext hook. There i have initialised the functionality as well of the context like addTodo, deleteTodo, UpdateTodo, todos, completeCheck etc.

step2 : now as the user is entering the todo title in the input section the todo is sent to the localstorage and is fetched from there too when the UI is rendered again with the help of useEffect hook.

step3: the complete functionality of methods intialised at the context.jsx file is defined at the app.jsx file like addingTodo, UpdateTodo, completeCheck, deleteTodo etc. this functionality is provided to the components like TodoForm and TodoItem with the help of context provider.

step4 : the components are designed with the help of tailwind css for a better UI and the inputs like todo title and the functaility like adding , updating, deleting is passed. 

step5: debugging involves the passing of data in props, using callback function properly as per the logic like map, filter.
Maintaing a decent UI for better understanding.
