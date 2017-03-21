# Simple React Gantt Diagram

Many thanks to http://taitems.github.io/jQuery.Gantt/

## Demo
[react_gantt](https://alexsuslov.github.io/react_gantt/)

demo based [React Static Boilerplate](https://github.com/kriasoft/react-static-boilerplate)

## Install

```
npm install react_gantt --save
```

## Use
```
import Gantt from 'react_gantt';
...

return (<Gantt {...{
  start: new Date(1970, 0, 1),
  stop: new Date(),
  data:[  {
    "name": "Sprint 0",
    "desc": "Analysis",
    "values": [{
      "from": 1320192000000,
      "to": 1322401600000,
      "label": "Requirement Gathering",
      "customClass": "ganttRed"
    }]
    ]
  }}
/>);
```
