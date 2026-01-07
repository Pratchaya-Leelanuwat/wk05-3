---01.variable.js---- https://github.com/Pratchaya-Leelanuwat/wk05-3/blob/main/01-variable.js

=== Variables & Data Types Practice ===

Constants:
MAX_USERS: 100
PI: 3.14159

Variable (let):
count after increment: 2

=== Primitive Data Types ===
Numbers: 25 5.9 -10
Strings: John Doe
Booleans: isStudent: true isTeacher: false
null: null
undefined: undefined

=== Object Data Types ===
Array: [ 'apple', 'banana', 'orange' ]
First fruit: apple
Array length: 3
Object: { name: 'John', age: 25, city: 'Bangkok', isStudent: true }
Person name: John
Person age: 25

=== typeof Operator ===
typeof 25: number
typeof 'hello': string
typeof true: boolean
typeof undefined: undefined
typeof []: object
typeof {}: object
typeof (() => {}): function

=== Type Coercion ===
'5' + 2: 52
'5' - 2: 3
'5' \* 2: 10
true + 1: 2

Explicit coercion:
String(25): 25
Number('25'): 25
Boolean(1): true
Boolean(0): false
Boolean(''): false
Boolean('hello'): true

=== Challenge: Person Object ===
Student object:
{
firstName: 'Alice',
lastName: 'Smith',
age: 20,
gpa: 3.8,
courses: [ 'HTML', 'CSS', 'JavaScript' ],
isActive: true,
getFullName: [Function: getFullName],
getInfo: [Function: getInfo]
}
Full name: Alice Smith
Info: Alice Smith, Age: 20, GPA: 3.8
Courses: HTML, CSS, JavaScript

=== Truthy vs Falsy ===
Falsy values:
0: false
"": false
null: false
undefined: false
false: false
NaN: false

Truthy values:
1: true
hello: true
true: true
[]: true
{}: true
() => {}: true

✅ Activity 1 completed!

--อธิบาย--
แสดงการทำงานของการเรียกใช้ตัวแปรที่ต่างกัน const,let,var การใช้ type of, การกำหนด object

---02-functions.js https://github.com/Pratchaya-Leelanuwat/wk05-3/blob/main/02-functions.js
=== Functions & Arrow Functions Practice ===

Function Declaration:
Hello, John!
Hello, Alice!

Function Expression:
add(5, 3): 8
add(10, 20): 30

Arrow Function (full syntax):
multiply(4, 5): 20
Arrow Function (shorthand):
square(5): 25
double(10): 20
getRandom(): 96

Default Parameters:
Anonymous is 0 years old from Unknown
John is 0 years old from Unknown
John is 25 years old from Unknown
John is 25 years old from Bangkok

Rest Parameters:
sum(1, 2, 3): 6
sum(5, 10, 15, 20): 50
sum(): 0
sumWithReduce(2, 4, 6, 8): 20

Destructuring Parameters:
Alice, 22 years old, from Chiang Mai

Validation Function:
{ valid: false, message: 'Email is required' }
{ valid: false, message: 'Invalid email format' }
{ valid: false, message: 'Missing domain extension' }
{ valid: true, message: 'Email is valid' }

Returning Objects:
{
firstName: 'John',
lastName: 'Doe',
age: 30,
email: 'john.doe@example.com',
getFullName: [Function: getFullName],
getAge: [Function: getAge]
}
Email: john.doe@example.com
Full name: John Doe

Callback Function:
Original: [ 1, 2, 3, 4, 5 ]
Doubled: [ 2, 4, 6, 8, 10 ]
Squared: [ 1, 4, 9, 16, 25 ]

Challenge: Calculator
5 + 3 = 8
10 - 4 = 6
6 \* 7 = 42
20 / 4 = 5
2 ^ 10 = 1024
Using operate('add', 5, 3) = 8

✅ Activity 2 completed!

--อธิบาย--
แสดงวิธีใช้ฟังก์ชันของ javascript ทั้งแบบ declaration และ expression มีการแสดงฟังก์ชันหลายแบบ เช่น ปฏิทิน การคำนวณ, calculator

---03-control-flow.js https://github.com/Pratchaya-Leelanuwat/wk05-3/blob/main/03-control-flow.js

=== Control Flow & Logic Practice ===

Age Classification:
Age 5: Child
Age 15: Teenager
Age 25: Adult
Age 65: Senior

Day Names:
Day 1: Monday
Day 2: Tuesday
Day 3: Wednesday
Day 4: Thursday
Day 5: Friday
Day 6: Saturday
Day 7: Sunday
Day 8: Unknown day

Weekday/Weekend:
Monday (1): Weekday
Saturday (6): Weekend

Logical Operators:
Can drive: true
Is special age: true
Is not adult: false

Short-Circuit Evaluation:
User name: John
User profile: undefined

Grading System:
Score 95: Grade A
Score 85: Grade B
Score 75: Grade C
Score 65: Grade D
Score 55: Grade F

Form Validation:
Valid user: { isValid: true, errors: [] }
Invalid user: {
isValid: false,
errors: [
'Name must be at least 3 characters',
'Valid email is required',
'Must be 18 or older',
'Password must be at least 6 characters',
'Must agree to terms'
]
}

Challenge: Traffic Light
red: 🛑🛑 STOP
yellow: 🟨🟨 SLOW DOWN
green: 🟢🟢 GO
blue: ❓ INVALID COLOR

✅ Activity 3 completed!

--อธิบาย--
โค้ดนี้แสดงถึงการทำงาน control flow มีการใช้ function ร่วมกับ if-else ในโปรแกรมเพื่อหาผลลัพธ์หรือแก้ไขปัญหา การ validate username, email, etc. การใช้
forEach ในการลูปแต่ละตัวออกมา

---04-loops.js https://github.com/Pratchaya-Leelanuwat/wk05-3/blob/main/04-loops.js

For loop (0-4):
i = 0
i = 1
i = 2
i = 3
i = 4

While loop (count down):
5...
4...
3...
2...
1...
Blastoff! 🚀🚀

For...of loop (fruits):

- apple
- banana
- orange

For...in loop (person properties):
name: John
age: 25
city: Bangkok

forEach (with index):
0: apple
1: banana
2: orange

map - transform elements:
Original: [ 1, 2, 3, 4, 5 ]
Doubled: [ 2, 4, 6, 8, 10 ]
Squared: [ 1, 4, 9, 16, 25 ]
As strings: [ 'Number: 1', 'Number: 2', 'Number: 3', 'Number: 4', 'Number: 5' ]

filter - select elements:
Even numbers: [ 2, 4 ]
Odd numbers: [ 1, 3, 5 ]
Numbers > 2: [ 3, 4, 5 ]

reduce - accumulate:
Sum: 15
Product: 120
Concatenated: 12345
Word count: { apple: 3, banana: 1, orange: 1 }

Method chaining:
Even numbers squared: 2²=4, 4²=16, 6²=36, 8²=64, 10²=100
Average: 30

Challenge: Student Analysis
Students: [
{ name: 'Alice', score: 95 },
{ name: 'Bob', score: 75 },
{ name: 'Charlie', score: 85 },
{ name: 'Diana', score: 92 },
{ name: 'Eve', score: 88 }
]
Names: Alice, Bob, Charlie, Diana, Eve
High scorers: Alice (95), Charlie (85), Diana (92), Eve (88)
Class average: 87.00
Top scorer: Alice (95)
Summary (sorted):
Alice: 95 (A)
Diana: 92 (A)
Eve: 88 (B)
Charlie: 85 (B)
Bob: 75 (C)

✅ Activity 4 completed!

--อธิบาย--
โค้ดนี้หลักๆเน้นไปที่การใช้ For loop มีทั้งการ for loop จาก object และแบบ array โดยใช้ for(int i=0; ...) อีกทั้งยังมีการใช้ .map() method ในการลูปเอามาแล้วไปทำอะไรบางอย่าง เช่น
const doubled = numbers.map((n) => n \* 2); คือการเอาตัวเลขแต่ละตัวไปคูณ 2

---05-integration.js https://github.com/Pratchaya-Leelanuwat/wk05-3/blob/main/05-integration.js

🎯🎯 === QUIZ APPLICATION === 🎯🎯

QUIZ RESULTS:
────────────────────────────────────────────────────────────
Q1: What is 5 + 3?
Your answer: 6
Correct answer: 8
❌ WRONG

Q2: What is the capital of Thailand?
Your answer: Phuket
Correct answer: Bangkok
❌ WRONG

Q3: What is the largest planet?
Your answer: Neptune
Correct answer: Jupiter
❌ WRONG

Q4: What is 2^8?
Your answer: 256
✅ CORRECT

Q5: Which is NOT a JavaScript data type?
Your answer: class
✅ CORRECT

────────────────────────────────────────────────────────────
FINAL SCORE: 2/5 (40.0%)
GRADE: F

FEEDBACK:
💪💪 Keep practicing. You'll improve!

📊📊 STATISTICS:
Total questions: 5
Correct: 2
Incorrect: 3
Success rate: 40.0%

Answer breakdown:
✅ Correct: 2
❌ Incorrect: 3

✅ All activities completed!
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

--อธิบาย--
โปรแกรมนี้คือการสร้าง quiz เกมแบบง่ายๆ โดยใช้ javascript จะมีการใช้ if-else เพื่อตรวจสอบคำผิด การกำหนด javascript array of object เพื่อเก็บข้อมูลคำถาม
การใช้ for loop (forEach) เพื่อลูปข้อมูลใน javascript array of object
