<h1 align="center">
    <img alt="GoStack" src=".github/logo.png" width="200px" />
</h1>

<h3 align="center">
 Module and Challenge 5: First project with ReactJS
</h3>

<blockquote align="center">Developed during Rocketseat's GoStack9 Bootcamp</blockquote>

## About
Application that uses the GitHub API to display repositories.

## Functionalities

#### 1. Catching Errors

Add a try / catch around the code present in the handleSubmit function in the Main component and if a repository is not found in the Github API add a red border around the input where the user entered the repository name.

#### 2. Duplicate Repository

Before calling the API in the handleSubmit function, check to see if the repository is not duplicated, ie if it does not already exist in the state of repositories.

If so, an error is triggered, and the code will fall into the catch of try / catch created in the previous functionality.

#### 3. Status Filter

Add a state filter to the Issues listing we created in the repository detail. The state represents whether the issue is open, closed, or an option to display them all.

#### 4. Pagination

Add pagination to the issues listed in the repository detail.

Just add a next page and previous page button. The previous page button should be disabled on the first page.
