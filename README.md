# Floqer's Assignment for Software Dev Internship Role

This assignment is designed to help us understand your technical skills.

## Points and Tips:
1. Feel free to use whichever language/components you like.
2. React (in TypeScript) is preferred because we use it.
3. Checkout Ant Design for components, but feel free to use whichever library you're comfortable with.
4. There is no hard rule, so be creative on these tasks.

## React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Task 1: Basic Table
### Data Information:
- You'll be working with the data set provided [here](https://www.kaggle.com/floqer/ml-engineer-salary-2020-2024).
- The dataset provides information on ML Engineer salaries from 2020 to 2024.
- You can either create an API to fetch this data or just put this data in a file in your frontend codebase.

### Description:
Based on this data, create a table (call it "main table") with the following columns:
1. Year
2. Number of total jobs for that year
3. Average salary in USD

Users should be able to sort the table by any column.

## Task 2: Analytics
### Description:
Now our users want to understand this data even further. Using the same data, create the following:
1. A line graph that shows how this number has changed from 2020 to 2024 (kaggle link above has a similar bar graph).
2. Now, when I click a row from our main table, a second table should appear that displays aggregated job titles and the number of jobs for that year. For example, if the user clicks on 2022, all the titles from 2022 should appear in another table, along with the sum of how many times each job appeared in 2022.
