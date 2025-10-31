# Individual Assignment Notes: Basic React
## Chapter 3: Imperative vs Declarative Coding
Quotes from (https://nextjs.org/learn/react-foundations/updating-ui-with-javascript)

The code above (index.html) is a good example of imperative programming. You're writing the steps for how the user interface should be updated. But when it comes to building user interfaces, a declarative approach is often preferred because it can speed up the development process. Instead of having to write DOM methods, it would be helpful if developers were able to declare what they want to show (in this case, an h1 tag with some text).

In other words, imperative programming is like giving a chef step-by-step instructions on how to make a pizza. Declarative programming is like ordering a pizza without being concerned about the steps it takes to make the pizza. 🍕

React is a popular declarative library that you can use build user interfaces.

Declarative Ex: "A Hawaiian Pizza please"
Imperative Ex:  *instructions on how to make hawaiian pizza*

## Concerns
The instructions were not clear if I was to use the existing index.html or not. Since the instructions implied I should create my own index, I developed myIndex.html. Ready for replacement if necessary. Unsure how to show modifications to the provided index.html or view it from Live Server Extension.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
