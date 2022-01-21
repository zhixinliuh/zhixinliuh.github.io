---
layout: project
type: project
image: images/hotelresize.jpeg
title: Hotel Checkin
permalink: projects/hotelCheck
# All dates must be YYYY-MM-DD format!
date: 2018-10-01
labels:
  - Javascript
--- 
One of our project for high school STEM class was to create an hotel simple checkin system this was part of the code i used to show the name or the room number that is bounded to the room.
```js
//created an object that has no data
var classroom={
	classnumber:"f103",
  students:18,
};
var userIput= prompt("classnumber or students?");
var lowercase=userIput.toLowerCase();
if ((lowercase === "classnumber") || (lowercase === "students")){
	window.alert(classroom[lowercase]);
}
//given 3 more trys to give answers
else {
	for (i=1;i<3;i++){
  var userIput= prompt("classnumber or students?. you have tried " +i + "times");
	var lowercase=userIput.toLowerCase();
	if ((lowercase === "classnumber") || (lowercase === "students")){
  i=3;
	window.alert(classroom[lowercase]);
  	}
	}
}
```
