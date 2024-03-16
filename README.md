# Styling React Apps

## Static & Dynamic Styling for Pretty Apps

# Task: Apply CSS to React Components

- Styling with Vanilla CSS
- Scoping Styles with CSS Modules
- CSS-in-JS Styling with "Styled Components"
- Styling with Tailwind CSS
- Static & Dynamic (Conditional) Styling

# Steps

## 0. Setting up the Project

1.  run `npm install`
2.  run `npm run dev`

## 1. Module Introduction & Starting Project

1.  create `README.md`

## 2. Splitting CSS Code Across Multiple Files

1. create `Header.css` & paste the styles to it cut from `index.css`
2. import `Header.css` in `Header.jsx`

## 3. Vanilla CSS Styles Are NOT Scoped To Components!

1. example of vanilla CSS style not being scoped in components

## 4. Styling React Apps with Inline Styles

1. apply inline styles in `Header.jsx`

## 5. Dynamic & Conditional Inline Styles

1. add dynamic & conditional style using inline styling in `Authinputs.jsx`

## 6. Dynamic & Conditional Styling with CSS Files & CSS Classes

1. add dynamic & conditional styles with CSS files & CSS classes using template literals

## 7. Scoping CSS Rules with CSS Modules

1. rename `Header.css` to `Header.module.css`
2. import `import classes from './Header.module.css';` in `Header.jsx`
3. apply `.paragraph` class

## 8. Introducing "Styled Components" (Third-party Package)

1. run `npm install styled-components`
2. add `import { styled } from 'styled-components';` in `Authinputs.jsx`
3. use `styled` component in the code in `Authinputs.jsx`

## 9. Creating Flexible Components with Styled Components

1. add `Label` & `Input` components in `Authinputs.jsx`

## 10. Dynamic & Conditional Styling with Styled Components

1. use styled components for `label` & `input` to apply dynamic styles to `Email` & `Password`
2. prefix the props you only want to use in your styled components with `$` to avoid clashes with built-in props

## 11. Styled Components: Pseudo Selectors, Nested Rules & Media Queries

1. replace the built-in `header` component with a styled `StyledHeader`component
2. use `&` to apply CSS styles to elements inside their parent

## 12. Creating Reusable Components & Component Combinations

1. create `Button.jsx` component
2. create `Input.jsx` component

## 13. Introducing Tailwind CSS For React App Styling

1. install Tailwind CSS
2. configure Tailwind CSS in `tailwind.config.js`
3. add the Tailwind directives to `index.css`
4. install Tailwind CSS IntelliSense extension in Visual Studio Code
5. use Tailwind CSS in `Header.jsx`

## 14. Adding & Using Tailwind CSS In A React Project

1. customize Tailwind CSS by adding custom styles in `index.css`
2. create a new utility file that alows to use a custom font in `tailwind.config.js` & use it in `Header.jsx`

## 15. Tailwind: Media Queries & Pseudo Selectors

1. use media queries in `Header.jsx`
2. use pseudo selectors in `Button.jsx`
