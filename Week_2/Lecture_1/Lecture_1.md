###
Type of primitives
- Strings
- Undefined
- Booleans
- Number

javascript = objects
python = dictionary
ruby = hash

objects don't have a length property, so that is why for let loops won't work. for (let i=0; i < arr.length; i++){}
to reference key values in objects, it's best to use 'this'. so for example in a object named 'person' to get someones age
you should do this.age instead of person.age.
use function() in objects instead of =>
for looping in objects, use for in loops only.