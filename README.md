1. $and: Matches documents that satisfy all the conditions specified in the array.

2. $or: Matches documents that satisfy at least one of the conditions specified in the array.

3. $not: Inverts the effect of a query expression, returning documents that do not match the specified condition.

4. $nor: Matches documents that fail to satisfy all the conditions specified in the array (the opposite of $or).

used more commands ->

$exists
Matches documents that have the specified field.
$type
Selects documents if a field is of the specified type.

tasks->
1. db.updateOne
2. db.updateMany
3. db.findOneAndUpdate
4. db.replaceOne
5. db.findAndUpdateOne

6. use .deleteOne
7. use .deleteMany
8. use .findOneAndDelete


