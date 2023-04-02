a group of friends have decided to start a secret society, the name of the society will be the first letter of each of their names, create a function that takes in an array of names and returns the name of the secret society.

const namesArray = ["Nikki", "Chris", "James", "Valeria", "Spencer", "Jake"]

<!-- Pseudo -->
//Input: array of names
//Output: first letter of each of their names to create the secret society name as a string

//Example: "NCJVSJ"

// Process:
// create function name secrectSociety
// I will use the method .map([0]) iterate through the newArray
// newArray = namesArray but only the charcter of each element
// 

const newArray = namesArray.map(name => {
    return name[0]
})
newArray.join("")