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
