instrucions is simple you should upload your golang code into String code = """here  """ and then runn it

 our code is a golang interpreter which takes string as input where there are multiple functions which it needs to "translate" and write output of. 

When you run it interpret method splits string into meaningful parts based on keywords but that method isn't anything high end . It simply looks for func and splits functions based on that then it looks for if for := and things like that and then calls below functions one by one 

First interpret function method kicks in . It splits the function body into lines and works on them one by one if it sees a for loop handle for loop happens if it sees a if statement guess what handleifstatement is called for arithmetic operations processline works on them  for Fmt.print handle print. for conditions (if for ... ) evaluate condition which splits conditions by parts seeing each side and then comparing them with the right comparison operator . 

Handleif works like that it checks first condition after if keyword with evaluate condition then chooses which {} to pick first one after if or the next one it also skips else if there is one

Handlefor works like this it again checks if a condition next to for is true with the help of another function : evaluate condition and then runs what's inside first {}  after  keyword till the condition is false



So about how we handled workload. On the first 2 days we spent most of our time learning. After that we tried a lot of things which didn't work we argued a lot and we didn't come to an agreement on which plan was better out of us. Finally we went with mine to simply do what we do when analysing code with a naked eye look for specific parts and work based on that. Were were happy when it could run without error even though it didn't work anything like what we intended . Later we started watching YouTube explanations on how compiler worked and learned quite a few. In the end our code didn't properly handle a function which should output if the number is prime or not and simply gives zero. Workload was kinda like this. We were arguing a lot with each other looking at the code surprised when it worked and once one got tired of coding we were switching. 2 was usually thinking of ways and looking for answers while one was implementing them . It was very stressful. I learned that I lack abilities to work with a team .
