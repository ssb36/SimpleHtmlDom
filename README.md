## Maximum Marks - 12

- The Submission should not contain spaces, for example /js-101 folder/eval will not work
- Do not push node_modules and package_lock.json to github

```
✅ able to submit the app - 1 (default)
✅ Check if the api call made  - 2 mark
✅ Student is able to loop through the data and append in the dom - 2 marks
✅ Check the Filter Part - 1 mark
✅ Check sorting ascending order - 1 mark
✅ Check sorting descending order - 1 mark
✅ Check sorting+filter Ascending order - 2 mark
✅ Check sorting+filter descending order - 2 mark

```



## Description

### `Instructions`

- Read entire question carefully for at-least 15 mins, understand it and then code it.
- Don’t jump directly into code.
- Commit your code every hour with proper commit message to your repository (we will monitor every commit)

# Problem Statement

- Build a Country finder app, where a user can find all countries and its info.

- Use https://restcountries.com/v3.1/all API to fetch all countries list.

- Your app will have only one page where you need to display all countries in form of cards with following information

  - Country name(h3 tag) (data.name.common)
  - Image of flag(img tag) (data.flags.png)
  - Population(p tag) (data.population)
  - Region(p tag) (data.region)
  - Capital(p tag) (data.capital)

- Please follow the above tags else you will not get marks.

- Your card should look like. Please make sure you follow the tags.

  ![Screenshot 2022-09-17 at 4.03.01 PM.png](https://i.imgur.com/hxzwIG4.png)

- Your app should also have sort and filtering functionality

  - Sort by Population
  - Filter by Region
    - All (by default all the countries from the API should be displayed)
    - Africa
    - Americas
    - Asia
    - Europe
    - Oceania

- Note that sort and filter should work simultaneously.
  - Should be able to sort the filtered results and vice versa.
  
  ![](https://i.imgur.com/ycYI8FL.gif)

## Boilerplate

- index.html


#### General guidelines
- so we request you to read the problem carefully and debug before itself
