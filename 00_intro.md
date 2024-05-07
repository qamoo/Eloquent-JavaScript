{{meta {load_files: ["code/intro.js"]}}}

# Introduction

{{quote {author: "Ellen Ullman", title: "Close to the Machine: Technophilia and its Discontents", chapter: true}

We think we are creating the system for our own purposes. We believe we are making it in our own image... But the computer is not really like us. It is a projection of a very slim part of ourselves: that portion devoted to logic, order, rule, and clarity.

우리는 우리 자신의 목적을 위해 시스템을 만들고 있다고 생각합니다. 우리는 우리 자신을 형상으로하여 시스템을 만들고 있다고 믿습니다... 그러나 컴퓨터는 실제로 우리와 같지 않습니다. 컴퓨터는 우리의 매우 한정된 부분만을 반영한 것입니다. 그 부분은 논리, 질서, 규칙, 명료성에 집중되어 있죠. 

quote}}

{{figure {url: "img/chapter_picture_00.jpg", alt: "Illustration of a screwdriver next to a circuit board of about the same size", chapter: "framed"}}}

This is a book about instructing ((computer))s. Computers are about as common as screwdrivers today, but they are quite a bit more complex, and making them do what you want them to do isn't always easy.   
이 책은 ((컴퓨터))에게 일을 시키는 것에 관한 책입니다. 컴퓨터는 오늘날 나사 드라이버만큼 흔하지만, 훨씬 더 복잡하며, 원하는 대로 작동하도록 만드는 것은 항상 쉽지 않습니다.

If the task you have for your computer is a common, well-understood one, such as showing you your email or acting like a calculator, you can open the appropriate ((application)) and get to work. But for unique or open-ended tasks, there often is no appropriate application.   
컴퓨터에게 시키는 일이 이메일을 보여주거나 계산을 하는 일 등 일반적이고 단순한 작업이라면 적절한 응용 프로그램을 찾아 실행하고 작업을 할 수 있습니다. 그러나 일반적이지 않거나 단순하게 해결되지 않는 작업의 경우 적절한 ((응용 프로그램))이 없는 경우가 많습니다.

That is where ((programming)) may come in. _Programming_ is the act of constructing a _program_—a set of precise instructions telling a computer what to do. Because computers are dumb, pedantic beasts, programming is fundamentally tedious and frustrating.  
이때 우리에게 ((프로그래밍))이 필요합니다. _프로그래밍_은 _프로그램_을 구성하는 행위입니다. 프로그램은 컴퓨터에게 무엇을 해야하는지 정확하게 알려주는 것입니다. 컴퓨터는 말을 못하고 까탈스러운 짐승이기 때문에, 프로그래밍은 본질적으로 지루하고 짜증 나는 일입니다.

{{index [programming, "joy of"], speed}}

Fortunately, if you can get over that fact—and maybe even enjoy the rigor of thinking in terms that dumb machines can deal with—programming can be rewarding. It allows you to do things in seconds that would take _forever_ by hand. It is a way to make your computer tool do things that it couldn't do before. On top of that, it makes for a wonderful game of puzzle solving and abstract thinking.
그럼에도 불구하고, 만약 여러분이 이 사실을 극복하고 멍청한 기계가 다룰 수 있는 용어로 사고하는 엄밀함을 즐길 수만 있다면 어쩌면 프로그래밍은 보람찰 수 있습니다. 프로그래밍을 통해 손으로는 영원히 걸릴 일을 단 몇 초 안에 처리할 수 있습니다. 이전에는 할 수 없었던 일들을 컴퓨터를 통해 할 수 있게된 것이죠. 그 위에, 퍼즐 해결과 추상적 사고의 멋진 게임을 만듭니다.

Most programming is done with ((programming language))s. A _programming language_ is an artificially constructed language used to instruct computers. It is interesting that the most effective way we've found to communicate with a computer borrows so heavily from the way we communicate with each other. Like human languages, computer languages allow words and phrases to be combined in new ways, making it possible to express ever new concepts.  
프로그래밍 대부분은 프로그래밍 언어로 이루어집니다. 프로그래밍 언어는 컴퓨터에 명령을 내리는 데 사용되는 인공으로 구축된 언어입니다. 우리가 컴퓨터와 소통하는 가장 효과적인 방법이 우리가 서로 소통하는 방식에서 크게 영감을 받았다는 것은 흥미로운 점입니다. 인간의 언어처럼, 컴퓨터 언어는 단어와 구문을 새롭게 결합하여 새로운 개념을 표현할 수 있게 만들어줍니다.

{{index [JavaScript, "availability of"], "casual computing"}}

At one point, language-based interfaces, such as the BASIC and DOS prompts of the 1980s and 1990s, were the main method of interacting with computers. For routine computer use, these have largely been replaced with visual interfaces, which are easier to learn but offer less freedom. But if you know where to look, the languages are still there. One of them, _JavaScript_, is built into every modern web ((browser))—and is thus available on almost every device.   
과거에는 언어 기반 인터페이스가 주 컴퓨터 상호작용 방법이었습니다. 1980년대와 1990년대의 BASIC 및 DOS 프롬프트가 그 예입니다. 그러나 컴퓨터 사용에 대해서는 이러한 인터페이스들이 주로 시각적 인터페이스로 대체되었습니다. 시각적 인터페이스는 배우기 쉽지만 자유도는 떨어집니다. 하지만 찾아보면 여전히 언어들이 있습니다. 그 중 하나인 JavaScript는 모든 현대 웹 브라우저에 내장되어 있으며, 따라서 거의 모든 기기에서 사용할 수 있습니다.

{{indexsee "web browser", browser}}

This book will try to make you familiar enough with this language to do useful and amusing things with it.   
이 책은 여러분이 이 언어를 충분히 익숙하게 만들어, 유용하고 재미있는 일을 할 수 있도록 노력할 것입니다.

## On programming

{{index [programming, "difficulty of"]}}

Besides explaining JavaScript, I will introduce the basic principles of programming. Programming, it turns out, is hard. The fundamental rules are simple and clear, but programs built on top of these rules tend to become complex enough to introduce their own rules and complexity. You're building your own maze, in a way, and you can easily get lost in it.   
JavaScript를 설명하는 것 외에도, 프로그래밍의 기본 원칙을 소개할 것입니다. 프로그래밍은 어렵습니다. 기본 규칙은 간단하고 명확하지만, 이러한 규칙 위에 구축된 프로그램들은 자체적인 규칙과 복잡성을 도입하여 복잡해집니다. 어느 정도로는 자신만의 미로를 만들고 있으며, 쉽게 그 속에서 길을 잃을 수 있습니다.

{{index learning}}

There will be times when reading this book feels terribly frustrating. If you are new to programming, there will be a lot of new material to digest. Much of this material will then be _combined_ in ways that require you to make additional connections.   
이 책을 읽는 동안 가끔은 매우 좌절스러울 때가 있을 것입니다. 프로그래밍에 처음이라면, 소화해야 할 새로운 자료가 많을 것입니다. 이 자료의 많은 부분이 추가적인 연결을 만들도록 조합될 것입니다.

It is up to you to make the necessary effort. When you are struggling to follow the book, do not jump to any conclusions about your own capabilities. You are fine—you just need to keep at it. Take a break, reread some material, and make sure you read and understand the example programs and ((exercises)). Learning is hard work, but everything you learn is yours and will make further learning easier.   
피할 수 없는 노력은 여러분에 달려 있습니다. 이 책을 따라가는 데 어려움을 겪을 때, 자신의 능력에 대한 결론을 바로 내리지 마십시오. 여러분은 괜찮습니다—그저 계속 노력해야 할 뿐입니다. 휴식을 취하고, 일부 자료를 다시 읽고, 예제 프로그램과 연습문제를 읽고 이해하는 것이 중요합니다. 배우는 것은 어렵지만, 배운 모든 것은 여러분의 것이며, 더 많은 학습을 쉽게 만들어 줄 것입니다.

{{quote {author: "Ursula K. Le Guin", title: "The Left Hand of Darkness"}

{{index "Le Guin, Ursula K."}}

When action grows unprofitable, gather information; when information grows unprofitable, sleep.  
행동이 더 이상 이익을 주지 않을 때에는 정보를 수집하십시오; 정보가 더 이상 이익을 주지 않을 때에는 잠을 자십시오.
quote}}

{{index [program, "nature of"], data}}

A program is many things. It is a piece of text typed by a programmer, it is the directing force that makes the computer do what it does, it is data in the computer's memory, and at the same time it controls the actions performed on this memory. Analogies that try to compare programs to familiar objects tend to fall short. A superficially fitting one is to compare a program to a machine—lots of separate parts tend to be involved, and to make the whole thing tick, we have to consider the ways in which these parts interconnect and contribute to the operation of the whole.   
프로그램은 여러 가지로 이루어져 있습니다. 프로그래머가 입력한 텍스트 조각이며, 컴퓨터가 수행하는 작업을 지시하는 동력이기도 합니다. 또한 컴퓨터 메모리 내의 데이터이며, 동시에 이 메모리에서 수행되는 작업을 제어합니다. 프로그램을 친숙한 객체와 비교하려는 유사성은 종종 부족합니다. 얕은 유사성 중 하나는 프로그램을 기계와 비교하는 것입니다. 많은 독립적인 부품들이 관련되어 있으며, 전체 시스템을 작동시키기 위해 이러한 부품들이 어떻게 상호 연결되고 전체 작동에 기여하는지를 고려해야 합니다.

A ((computer)) is a physical machine that acts as a host for these immaterial machines. Computers themselves can do only stupidly straightforward things. The reason they are so useful is that they do these things at an incredibly high ((speed)). A program can ingeniously combine an enormous number of these simple actions to do very complicated things.   
컴퓨터는 이러한 무형의 기계들의 호스트 역할을 하는 물리적 기계입니다. 컴퓨터 자체는 매우 단순한 일만 수행할 수 있습니다. 그들이 굉장히 유용한 이유는 이러한 일들을 굉장히 빠른 속도로 수행하기 때문입니다. 프로그램은 엄청난 수의 이러한 간단한 작업을 영리하게 조합하여 매우 복잡한 일을 수행할 수 있습니다.

{{index [programming, "joy of"]}}

A program is a building of thought. It is costless to build, it is weightless, and it grows easily under our typing hands. But as a program grows, so does its ((complexity)). The skill of programming is the skill of building programs that don't confuse yourself. The best programs are those that manage to do something interesting while still being easy to understand.   
프로그램은 사고의 건축물입니다. 만들기는 무료이며, 무게가 없으며, 우리의 타이핑 손 아래에서 쉽게 자라납니다. 그러나 프로그램이 커질수록 복잡성도 커집니다. 프로그래밍의 기술은 자신을 혼란스럽게 하지 않는 프로그램을 만드는 기술입니다. 가장 좋은 프로그램은 여전히 이해하기 쉬운 동시에 흥미로운 작업을 수행하는 것입니다.

{{index "programming style", "best practices"}}

Some programmers believe that this complexity is best managed by using only a small set of well-understood techniques in their programs. They have composed strict rules ("best practices") prescribing the form programs should have and carefully stay within their safe little zone.   
일부 프로그래머는 복잡성을 가장 잘 관리하는 방법으로 프로그램에서 잘 이해된 소수의 기술만 사용하는 것이 좋다고 믿습니다. 그들은 프로그램이 가져야 할 형태에 대한 엄격한 규칙("최상의 관행")을 작성하여 안전한 작은 영역 내에서 주의 깊게 머무릅니다.

{{index experiment}}

This is not only boring, it is ineffective. New problems often require new solutions. The field of programming is young and still developing rapidly, and it is varied enough to have room for wildly different approaches. There are many terrible mistakes to make in program design, and you should go ahead and make them at least once so that you understand them. A sense of what a good program looks like is developed with practice, not learned from a list of rules.   
이것은 지루할 뿐만 아니라 비효율적입니다. 새로운 문제는 종종 새로운 해결책을 요구합니다. 프로그래밍 분야는 젊고 여전히 빠르게 발전하고 있으며, 극명하게 다른 접근 방식에도 충분한 여유가 있습니다. 프로그램 설계에서 많은 실수를 할 수 있으며, 그것들을 이해하기 위해 적어도 한 번은 실수를 해 보아야 합니다. 좋은 프로그램이 어떻게 보이는지에 대한 감각은 규칙 목록에서 배우는 것이 아니라 실습을 통해 발전됩니다.

## Why language matters 왜 언어가 중요한가     

{{index "programming language", "machine code", "binary data"}}

In the beginning, at the birth of computing, there were no programming languages. Programs looked something like this:   
처음에는 컴퓨팅의 탄생 시에 프로그래밍 언어가 없었습니다. 프로그램은 이렇게 보였습니다:

```{lang: null}
00110001 00000000 00000000
00110001 00000001 00000001
00110011 00000001 00000010
01010001 00001011 00000010
00100010 00000010 00001000
01000011 00000001 00000000
01000001 00000001 00000001
00010000 00000010 00000000
01100010 00000000 00000000
```

{{index [programming, "history of"], "punch card", complexity}}

This is a program to add the numbers from 1 to 10 together and print the result: `1 + 2 + ... + 10 = 55`. It could run on a simple hypothetical machine. To program early computers, it was necessary to set large arrays of switches in the right position or punch holes in strips of cardboard and feed them to the computer. You can imagine how tedious and error-prone this procedure was. Even writing simple programs required much cleverness and discipline. Complex ones were nearly inconceivable.   
이것은 1부터 10까지의 숫자를 더하여 결과를 출력하는 프로그램입니다: 1 + 2 + ... + 10 = 55. 이것은 간단한 가상 머신에서 실행될 수 있습니다. 초기 컴퓨터를 프로그래밍하려면 큰 스위치 배열을 올바른 위치로 설정하거나, 판지 조각에 구멍을 뚫고 컴퓨터에 공급해야 했습니다. 이 절차가 얼마나 지루하고 오류 발생 가능성이 높은지 상상할 수 있습니다. 심지어 간단한 프로그램을 작성하는 것조차 많은 기교와 집중력이 필요했습니다. 복잡한 프로그램은 거의 상상하기 어려웠습니다.

{{index bit, "wizard (mighty)"}}

Of course, manually entering these arcane patterns of bits (the ones and zeros) did give the programmer a profound sense of being a mighty wizard. And that has to be worth something in terms of job satisfaction.   
물론, 이런 이진수(1과 0)의 불가해한 패턴을 수동으로 입력하는 것은 프로그래머에게 강력한 마법사가 된 느낌을 주었습니다. 이는 직업 만족도 측면에서 어떤 가치가 있는지에 대해 생각해 볼 만합니다.


{{index memory, instruction}}

Each line of the previous program contains a single instruction. It could be written in English like this:   
앞선 프로그램의 각 줄은 한 개의 명령을 포함하고 있습니다. 다음과 같이 작성할 수 있습니다:


 1. Store the number 0 in memory location 0.   
 1. 메모리 위치 0에 숫자 0을 저장합니다.   
 2. Store the number 1 in memory location 1.   
 2. 메모리 위치 1에 숫자 1을 저장합니다.   
 3. Store the value of memory location 1 in memory location 2.   
 3. 메모리 위치 1의 값을 메모리 위치 2에 저장합니다.   
 4. Subtract the number 11 from the value in memory location 2.   
 4. 메모리 위치 2의 값에서 숫자 11을 빼냅니다.   
 5. If the value in memory location 2 is the number 0, continue with instruction 9.   
 5. 메모리 위치 2의 값이 숫자 0이면, 9번 명령으로 계속합니다.   
 6. Add the value of memory location 1 to memory location 0.   
 6. 메모리 위치 0에 메모리 위치 1의 값을 더합니다.   
 7. Add the number 1 to the value of memory location 1.   
 7. 메모리 위치 1의 값에 숫자 1을 더합니다.   
 8. Continue with instruction 3.   
 8. 3번 명령으로 계속합니다.   
 9. Output the value of memory location 0.   
 9. 메모리 위치 0의 값을 출력합니다.   
{{index readability, naming, binding}}

Although that is already more readable than the soup of bits, it is still rather obscure. Using names instead of numbers for the instructions and memory locations helps:   
비록 숫자 대신에 이름을 사용한 지시문과 메모리 위치를 사용하면 이해하기 쉽지만, 여전히 상당히 난해합니다.

```{lang: "null"}
 Set “total” to 0.
 Set “count” to 1.
[loop]
 Set “compare” to “count”.
 Subtract 11 from “compare”.
 If “compare” is zero, continue at [end].
 Add “count” to “total”.
 Add 1 to “count”.
 Continue at [loop].
[end]
 Output “total”.
```

{{index loop, jump, "summing example"}}

Can you see how the program works at this point? The first two lines give two memory locations their starting values: `total` will be used to build up the result of the computation, and `count` will keep track of the number that we are currently looking at. The lines using `compare` are probably the most confusing ones. The program wants to see whether `count` is equal to 11 to decide whether it can stop running. Because our hypothetical machine is rather primitive, it can only test whether a number is zero and make a decision based on that. It therefore uses the memory location labeled `compare` to compute the value of `count - 11` and makes a decision based on that value. The next two lines add the value of `count` to the result and increment `count` by 1 every time the program decides that `count` is not 11 yet.   
위 프로그램이 어떻게 작동하는지 아시겠나요? 첫 두 줄은 두 개의 메모리 위치에 초기값을 할당합니다. total은 계산 결과를 누적할 때 사용되고, count는 현재 검사 중인 숫자를 추적합니다. compare를 사용하는 줄들이 아마도 가장 혼란스러울 것입니다. 프로그램은 count가 11인지 여부를 확인하여 실행을 멈출지 결정하려고 합니다. 우리의 가상 머신이 상당히 원시적이기 때문에, 숫자가 0인지 여부만 테스트하고 그 값을 기반으로 결정할 수 있습니다. 따라서 프로그램은 count - 11의 값을 계산하고 그 값에 따라 결정하기 위해 compare로 레이블된 메모리 위치를 사용합니다. 다음 두 줄은 프로그램이 count가 아직 11이 아니라고 판단할 때마다 결과에 count 값을 추가하고 count를 1씩 증가시킵니다.

Here is the same program in JavaScript:   
다음은 JavaScript로 작성된 동일한 프로그램입니다:

```
let total = 0, count = 1;
while (count <= 10) {
  total += count;
  count += 1;
}
console.log(total);
// → 55
```

{{index "while loop", loop, [braces, block]}}

This version gives us a few more improvements. Most importantly, there is no need to specify the way we want the program to jump back and forth anymore—the `while` construct takes care of that. It continues executing the block (wrapped in braces) below it as long as the condition it was given holds. That condition is `count <= 10`, which means “the count is less than or equal to 10”. We no longer have to create a temporary value and compare that to zero, which was just an uninteresting detail. Part of the power of programming languages is that they can take care of uninteresting details for us.   
이 버전은 몇 가지 개선을 제공합니다. 가장 중요한 것은 이제 프로그램이 앞뒤로 뛰어다니는 방법을 명시할 필요가 없다는 것입니다 - while 구조가 처리를 도와줍니다. 주어진 조건이 유지되는 한 아래에 있는 블록(중괄호로 둘러싸인)을 계속 실행합니다. 그 조건은 count <= 10이며, 이는 "카운트가 10보다 작거나 같다"는 뜻입니다. 이제 더 이상 우리는 임시값을 만들고 그것을 0과 비교할 필요가 없으며, 그것은 그저 흥미로운 세부 사항이었습니다. 프로그래밍 언어의 일부인 흥미로운 세부 사항을 대신 처리할 수 있다는 것이 프로그래밍 언어의 힘 중 하나입니다.

{{index "console.log"}}

At the end of the program, after the `while` construct has finished, the `console.log` operation is used to write out the result.   
프로그램의 끝에서 while 구조가 끝난 후 console.log 작업이 사용되어 결과를 출력합니다.

{{index "sum function", "range function", abstraction, function}}

Finally, here is what the program could look like if we happened to have the convenient operations `range` and `sum` available, which respectively create a ((collection)) of numbers within a range and compute the sum of a collection of numbers:   
마지막으로, 우연히 range 및 sum이라는 편리한 작업이 있는 경우 프로그램은 다음과 같이 보일 수 있습니다. range는 범위 내의 숫자 집합을 생성하고, sum은 숫자 집합의 합을 계산합니다.

```{startCode: true}
console.log(sum(range(1, 10)));
// → 55
```

{{index readability}}

The moral of this story is that the same program can be expressed in both long and short, unreadable and readable ways. The first version of the program was extremely obscure, whereas this last one is almost English: `log` the `sum` of the `range` of numbers from 1 to 10. (We will see in [later chapters](data) how to define operations like `sum` and `range`.)   
이 이야기의 교훈은 동일한 프로그램이 긴 방법과 짧은 방법, 가독성이 낮은 방법과 가독성이 높은 방법으로 표현될 수 있다는 것입니다. 첫 번째 버전의 프로그램은 매우 난해했지만, 이 마지막 버전은 거의 영어와 같습니다: 1부터 10까지의 숫자 범위(range)의 합(sum)을 기록(log)합니다. (나중 장에서 sum 및 range와 같은 작업을 정의하는 방법을 살펴보겠습니다.)

{{index ["programming language", "power of"], composability}}

A good programming language helps the programmer by allowing them to talk about the actions that the computer has to perform on a higher level. It helps omit details, provides convenient building blocks (such as `while` and `console.log`), allows you to define your own building blocks (such as `sum` and `range`), and makes those blocks easy to compose.   
좋은 프로그래밍 언어는 프로그래머가 컴퓨터가 수행해야 하는 작업에 대해 더 높은 수준에서 이야기할 수 있도록 돕습니다. 세부 사항을 생략하도록 도와주며, while 및 console.log와 같은 편리한 구성 요소를 제공하고, 사용자 정의 구성 요소 (예: sum 및 range)를 정의하고 해당 블록을 쉽게 조합할 수 있도록 만듭니다.

## What is JavaScript?
## 자바스크립트란 무엇인가?

{{index history, Netscape, browser, "web application", JavaScript, [JavaScript, "history of"], "World Wide Web"}}

{{indexsee WWW, "World Wide Web"}}

{{indexsee Web, "World Wide Web"}}

JavaScript was introduced in 1995 as a way to add programs to web pages in the Netscape Navigator browser. The language has since been adopted by all other major graphical web browsers. It has made modern web applications possible—that is, applications with which you can interact directly without doing a page reload for every action. JavaScript is also used in more traditional websites to provide various forms of interactivity and cleverness.   
JavaScript는 1995년에 넷스케이프 네비게이터 브라우저에 프로그램을 웹 페이지에 추가하는 방법으로 소개되었습니다. 그 이후로 이 언어는 모든 주요 그래픽 웹 브라우저에서 채택되었습니다. 이를 통해 현대의 웹 애플리케이션, 즉 페이지를 다시로드하지 않고도 직접 상호 작용할 수 있는 애플리케이션을 만들 수 있게 되었습니다. JavaScript는 더 전통적인 웹 사이트에서도 다양한 상호 작용과 기능을 제공하는 데 사용됩니다.

{{index Java, naming}}

It is important to note that JavaScript has almost nothing to do with the programming language named Java. The similar name was inspired by marketing considerations rather than good judgment. When JavaScript was being introduced, the Java language was being heavily marketed and was gaining popularity. Someone thought it was a good idea to try to ride along on this success. Now we are stuck with the name.  
JavaScript가 거의 아무런 관련이 없는 Java라는 프로그래밍 언어와 혼동되지 않도록 주의해야 합니다. 비슷한 이름은 좋은 판단이 아니라 마케팅 고려 사항에서 영감을 받았습니다. JavaScript가 소개될 때 Java 언어가 강력하게 마케팅되고 인기를 얻고 있었습니다. 누군가는 이 성공에 끼어드는 것이 좋은 생각이라고 생각했습니다. 이제 우리는 그 이름으로 곤란해지고 있습니다.

{{index ECMAScript, compatibility}}

After its adoption outside of Netscape, a ((standard)) document was written to describe the way the JavaScript language should work so that the various pieces of software that claimed to support JavaScript could make sure they actually provided the same language. This is called the ECMAScript standard, after the Ecma International organization that conducted the standardization. In practice, the terms ECMAScript and JavaScript can be used interchangeably—they are two names for the same language.   
넷스케이프 밖에서 사용되기 시작한 후, JavaScript를 지원한다고 주장하는 다양한 소프트웨어가 실제로 동일한 언어를 제공하는지 확인할 수 있도록 JavaScript 언어가 작동하는 방식을 설명하는 표준 문서가 작성되었습니다. 이것은 Ecma International 조직이 표준화를 수행한 후에 ECMAScript 표준이라고 합니다. 실제로 ECMAScript와 JavaScript 용어는 서로 교환하여 사용할 수 있습니다 - 이것들은 동일한 언어에 대한 두 가지 이름입니다.

{{index [JavaScript, "weaknesses of"], debugging}}

There are those who will say _terrible_ things about JavaScript. Many of these things are true. When I was required to write something in JavaScript for the first time, I quickly came to despise it. It would accept almost anything I typed but interpret it in a way that was completely different from what I meant. This had a lot to do with the fact that I did not have a clue what I was doing, of course, but there is a real issue here: JavaScript is ridiculously liberal in what it allows. The idea behind this design was that it would make programming in JavaScript easier for beginners. In actuality, it mostly makes finding problems in your programs harder because the system will not point them out to you.   
JavaScript에 대해 끔찍한 이야기를 할 것이라고 말하는 사람들이 있습니다. 이 이야기들 중 많은 것이 사실입니다. 처음으로 JavaScript로 무언가를 작성해야 할 때, 나는 빨리 그것을 혐오하기 시작했습니다. 거의 내가 입력한 모든 것을 받아들이지만, 내 의도와는 전혀 다른 방식으로 해석했습니다. 이것은 물론 내가 무엇을 하는지 전혀 모르는 상태에서 일했기 때문에 많이 영향을 미쳤지만, 여기에는 실제 문제가 있습니다: JavaScript는 허용 범위가 너무 넓습니다. 이 디자인의 아이디어는 JavaScript로 프로그래밍을 쉽게 만들 것이라는 것이었습니다. 실제로는, 이것은 주로 프로그램에서 문제를 찾는 것을 더 어렵게 만들었습니다. 왜냐하면 시스템이 그것들을 지적해 주지 않기 때문입니다.

{{index [JavaScript, "flexibility of"], flexibility}}

This flexibility also has its advantages, though. It leaves room for techniques that are impossible in more rigid languages and makes for a pleasant, informal style of programming. After ((learning)) the language properly and working with it for a while, I have come to actually _like_ JavaScript.   
그러나 이 유연성은 장점도 가지고 있습니다. 더 엄격한 언어에서는 불가능한 기술들에 대한 여유를 제공하며, 즐거운 비공식적인 프로그래밍 스타일을 만듭니다. 언어를 제대로 배우고 일정 기간동안 작업한 후에, 실제로 JavaScript를 좋아하게 되었습니다.

{{index future, [JavaScript, "versions of"], ECMAScript, "ECMAScript 6"}}

There have been several versions of JavaScript. ECMAScript version 3 was the widely supported version during JavaScript's ascent to dominance, roughly between 2000 and 2010. During this time, work was underway on an ambitious version 4, which planned a number of radical improvements and extensions to the language. Changing a living, widely used language in such a radical way turned out to be politically difficult, and work on the version 4 was abandoned in 2008. A much less ambitious version 5, which made only some uncontroversial improvements, came out in 2009. In 2015, version 6 came out, a major update that included some of the ideas planned for version 4. Since then we've had new, small updates every year.   
JavaScript에는 여러 버전이 있었습니다. ECMAScript 버전 3은 JavaScript가 지배적으로 사용되는 시기, 대략 2000년부터 2010년까지 널리 지원되는 버전이었습니다. 이 기간 동안 혁신적인 개선과 언어 확장을 계획한 대규모 버전 4의 작업이 진행되었습니다. 그러나 널리 사용되는 언어를 이렇게 급진적으로 변경하는 것은 정치적으로 어려운 일이었고, 버전 4에 대한 작업은 2008년에 중단되었습니다. 2009년에는 일부 논란되지 않는 개선만을 수행한 훨씬 덜 야심찬 버전 5가 출시되었습니다. 2015년에는 버전 6이 출시되었는데, 이는 버전 4에서 계획된 아이디어 중 일부를 포함한 중요한 업데이트였습니다. 그 이후로 매년 새로운 작은 업데이트가 있었습니다.

The fact that JavaScript is evolving means that browsers have to constantly keep up. If you're using an older browser, it may not support every feature. The language designers are careful to not make any changes that could break existing programs, so new browsers can still run old programs. In this book, I'm using the 2023 version of JavaScript.   
JavaScript가 계속 발전하고 있다는 사실은 브라우저가 계속해서 따라가야 함을 의미합니다. 오래된 브라우저를 사용하고 있다면 모든 기능을 지원하지 않을 수 있습니다. 언어 설계자들은 기존 프로그램을 깨뜨릴 수 있는 변경 사항을 조심스럽게 피하고 있으므로 새로운 브라우저에서도 이전 프로그램을 실행할 수 있습니다. 이 책에서는 2023년 버전의 JavaScript를 사용하고 있습니다.

{{index [JavaScript, "uses of"]}}

Web browsers are not the only platforms on which JavaScript is used. Some databases, such as MongoDB and CouchDB, use JavaScript as their scripting and query language. Several platforms for desktop and server programming, most notably the ((Node.js)) project (the subject of [Chapter ?](node)), provide an environment for programming JavaScript outside of the browser.   
웹 브라우저는 JavaScript가 사용되는 유일한 플랫폼이 아닙니다. MongoDB 및 CouchDB와 같은 일부 데이터베이스는 자신의 스크립팅 및 쿼리 언어로 JavaScript를 사용합니다. 노드.js 프로젝트(제20장의 주제)와 같은 여러 데스크톱 및 서버 프로그래밍 플랫폼은 브라우저 외부에서 JavaScript 프로그래밍 환경을 제공합니다.

## Code, and what to do with it / 코드와 그 처리 방법

{{index "reading code", "writing code"}}

_Code_ is the text that makes up programs. Most chapters in this book contain quite a lot of code. I believe reading code and writing ((code)) are indispensable parts of ((learning)) to program. Try to not just glance over the examples—read them attentively and understand them. This may be slow and confusing at first, but I promise that you'll quickly get the hang of it. The same goes for the ((exercises)). Don't assume you understand them until you've actually written a working solution.   
코드는 프로그램을 구성하는 텍스트입니다. 이 책의 대부분의 장에는 상당한 양의 코드가 포함되어 있습니다. 코드를 읽고 쓰는 것은 프로그래밍을 배우는 데 필수적인 부분이라고 생각합니다. 예제를 흘겨보지 말고 주의 깊게 읽고 이해하십시오. 처음에는 느리고 혼란스러울 수 있지만, 빠르게 적응할 것을 약속합니다. 연습 문제도 마찬가지입니다. 실제로 작동하는 해결책을 작성할 때까지 이해했다고 가정하지 마십시오.

{{index interpretation}}

I recommend you try your solutions to exercises in an actual JavaScript interpreter. That way, you'll get immediate feedback on whether what you are doing is working, and, I hope, you'll be tempted to ((experiment)) and go beyond the exercises.   
연습 문제의 해결책을 실제 JavaScript 인터프리터에서 시도하는 것을 권장합니다. 이렇게 하면 작업 중인 것이 작동하는지 즉시 확인할 수 있으며, 희망컨대 실험을 해보고 연습을 넘어서기를 동기부여 받을 것입니다.

{{if interactive

When reading this book in your browser, you can edit (and run) all example programs by clicking them.   
이 책을 브라우저에서 읽을 때, 모든 예제 프로그램을 클릭하여 편집하고(실행할) 수 있습니다.

if}}

{{if book

{{index download, sandbox, "running code"}}

The easiest way to run the example code in the book—and to experiment with it—is to look it up in the online version of the book at [_https://eloquentjavascript.net_](https://eloquentjavascript.net/). There, you can click any code example to edit and run it and to see the output it produces. To work on the exercises, go to [_https://eloquentjavascript.net/code_](https://eloquentjavascript.net/code), which provides starting code for each coding exercise and allows you to look at the solutions.

if}}

{{index "developer tools", "JavaScript console"}}

Running the programs defined in this book outside of the book's website requires some care. Many examples stand on their own and should work in any JavaScript environment. But code in later chapters is often written for a specific environment (the browser or Node.js) and can run only there. In addition, many chapters define bigger programs, and the pieces of code that appear in them depend on each other or on external files. The [sandbox](https://eloquentjavascript.net/code) on the website provides links to ZIP files containing all the scripts and data files necessary to run the code for a given chapter.   
이 책에서 정의된 프로그램을 책의 웹사이트 외부에서 실행하려면 몇 가지 주의가 필요합니다. 많은 예제는 독립적으로 실행될 수 있으며 어떤 JavaScript 환경에서든 작동해야 합니다. 그러나 후반 장의 코드는 종종 특정 환경(브라우저 또는 노드.js)을 위해 작성되었으며 해당 환경에서만 실행될 수 있습니다. 또한 많은 장에서는 큰 프로그램을 정의하고 있으며, 해당 프로그램에 나타나는 코드 조각은 서로 또는 외부 파일에 종속될 수 있습니다. 웹사이트의 샌드박스는 특정 장의 코드를 실행하기 위해 필요한 모든 스크립트 및 데이터 파일이 포함된 ZIP 파일 링크를 제공합니다.

## Overview of this book / 이 책 개요

This book contains roughly three parts. The first 12 chapters discuss the JavaScript language. The next seven chapters are about web ((browsers)) and the way JavaScript is used to program them. Finally, two chapters are devoted to ((Node.js)), another environment to program JavaScript in. There are five _project chapters_ in the book that describe larger example programs to give you a taste of actual programming.   
이 책에는 대략 세 부분이 있습니다. 처음 12장은 JavaScript 언어에 대해 다룹니다. 그 다음 일곱 장은 웹 브라우저와 JavaScript가 프로그래밍되는 방식에 대해 다룹니다. 마지막으로, 노드.js에서 JavaScript를 프로그래밍하는 또 다른 환경에 대해 두 장이 할애되어 있습니다. 책에는 실제 프로그래밍을 경험해 볼 수 있는 큰 예제 프로그램을 설명하는 다섯 개의 프로젝트 장이 있습니다.

The language part of the book starts with four chapters that introduce the basic structure of the JavaScript language. They discuss [control structures](program_structure) (such as the `while` word you saw in this introduction), [functions](functions) (writing your own building blocks), and [data structures](data). After these, you will be able to write basic programs. Next, Chapters [?](higher_order) and [?](object) introduce techniques to use functions and objects to write more _abstract_ code and keep complexity under control.

After a [first project chapter](robot) that builds a crude delivery robot, the language part of the book continues with chapters on [error handling and bug fixing](error), [regular expressions](regexp) (an important tool for working with text), [modularity](modules) (another defense against complexity), and [asynchronous programming](async) (dealing with events that take time). The [second project chapter](language), where we implement a programming language, concludes the first part of the book.

The second part of the book, Chapters [?](browser) to [?](paint), describes the tools that browser JavaScript has access to. You'll learn to display things on the screen (Chapters [?](dom) and [?](canvas)), respond to user input ([Chapter ?](event)), and communicate over the network ([Chapter ?](http)). There are again two project chapters in this part, building a [platform game](game) and a [pixel paint program](paint).

[Chapter ?](node) describes Node.js, and [Chapter ?](skillsharing) builds a small website using that tool.

{{if commercial

Finally, [Chapter ?](fast) describes some of the considerations that come up when optimizing JavaScript programs for speed.

if}}

## Typographic conventions

{{index "factorial function"}}

In this book, text written in a `monospaced` font will represent elements of programs. Sometimes these are self-sufficient fragments, and sometimes they just refer to part of a nearby program. Programs (of which you have already seen a few) are written as follows:

```
function factorial(n) {
  if (n == 0) {
    return 1;
  } else {
    return factorial(n - 1) * n;
  }
}
```

{{index "console.log"}}

Sometimes, to show the output that a program produces, the expected output is written after it, with two slashes and an arrow in front.

```
console.log(factorial(8));
// → 40320
```

Good luck!
