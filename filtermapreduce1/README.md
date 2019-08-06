# Filter Map Reduce Practice #1

* Goal is 30 minute completion
* Use teams.json and people.json

### Objectives

* Create project from scratch
* Setup eslint, jest, git repo (locally)
* Test all non-trivial functionality
* Final test should demonstrate desired output
* Use terminal for all file manipulation (including copying json)
* Use VIM for MD creation
* Mark date, result time and comments in RESULTS.md on this repo

### Output: TeamsOverview() returns Object

* Create a method that will use teams and people and provide the output below
* Return an object that shows data for qualifying people of each team,  by gender
* Who are 'Qualifying People?' Males with balance > 2200, Females with balance > 2000
* Who's on what team? See Team.json, assigned by Eye Color.

```javascript
{
  [teamname]: {
    males: {
      count: 000,
      avgBalance: 000,
      totalBalance: 000
    },
    females: {
      count: 000,
      avgBalance: 000,
      totalBalance: 000
    }
  },
  [teamname]: ...
}
```

JSON String to test against: "{\"Team Cloud\":{\"males\":{\"count\":5,\"avgBalance\":2872.2,\"totalBalance\":14361},\"females\":{\"count\":4,\"avgBalance\":3072.88,\"totalBalance\":12291.52}},\"Team Leaf\":{\"males\":{\"count\":3,\"avgBalance\":2727.32,\"totalBalance\":8181.97},\"females\":{\"count\":7,\"avgBalance\":3311.29,\"totalBalance\":23179.04}},\"Team Puddle\":{\"males\":{\"count\":4,\"avgBalance\":2954.59,\"totalBalance\":11818.37},\"females\":{\"count\":6,\"avgBalance\":2860.63,\"totalBalance\":17163.76}}}"
