# Habit Tracker

``` tracker
searchType: tag
searchTarget: exercise-pushup
folder: Daily
endDate: 2021-01-31
line:
    title: PushUp
    yAxisLabel: Count
    lineColor: "#d65d0e"
```

``` tracker
searchType: tag
searchTarget: exercise-plank
folder: Daily
line:
    title: Plank
    yAxisLabel: Hold
    yAxisUnit: sec
    lineColor: "#458588"
    pointColor: red
```

``` tracker
searchType: tag
searchTarget: meditation
folder: Daily
accum: true
penalty: -1
line:
    title: Meditation
    yAxisLabel: Count
```

## Summary
### Meditation
``` tracker
searchType: tag
searchTarget: meditation
folder: Daily
summary:
    template: "Longest Streak: {{maxStreak()}} day(s)\nLongest Breaks: {{maxBreaks()}} day(s)\nLast streak: {{currentStreak()}} day(s)"
```

### CleanUp
``` tracker
searchType: tag
searchTarget: clean-up
folder: Daily
summary:
    template: "Last Break: {{currentBreaks()}} day(s)"
```

### Work log
``` tracker
searchType: tag
searchTarget: work_log
folder: Daily
accum: true
startDate: 2021-01-01
line:
    title: Work Log
    yAxisLabel: Count
    pointSize: 5
    pointColor: white
    pointBorderWidth: 2
    pointBorderColor: "#d65d0e"
```

Please also check those search targets in markdown files under folder 'diary'.

Example:
https://youtu.be/W_leEJHBZW4


From:
https://github.com/pyrochlore/obsidian-tracker/blob/master/examples/HabitTracker.md