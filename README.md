# Day-04
# 1.How to compare the two JSON have the same properties without order?

var obj1 = JSON.stringify({ name: "person1", age: 5 })

var obj2 = JSON.stringify({ age: 5, name: "person1" })

console.log(obj1 !== obj2)
