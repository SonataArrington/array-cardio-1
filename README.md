Javascript Day/Project 4 of 31

Array Cardio 1

Just working through some arrays using filter, sort, map, and reduce. 


function(inventor) = a proper function<br>
inventor => =  an arrow function(best practice)

console.table will display a table instead of console.log

* .filter
    will return 
* .map
    will transform
* .sort
    will rearrange 
* .reduce
    will loop through 


const totalYears = inventors.reduce((total, inventor) => {
        return total + (inventor.passed - inventor.year)
      }, 0); <br> 

0 is where total will start