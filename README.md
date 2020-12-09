# Compiler-Designing-Project
Introduction: - As we know Interpreter is a program, which executes instructions written in a 
particular format line by line. Therefore, we have made an interpreter written in python3 , which 
interprets a code written in a language similar to assembly language used in microprocessor 8085.The 
language description will be further discussed in the report .We can perform almost every function 
that is included in microprocessor 8085 but instead of hexadecimal code, it takes input in decimal 
numbers .this interpreter not only executes the instructions but also helps to find the error like 
incorrect number of argument, or incorrect arguments, etc.

registers={'01': 0, '02': 0, '03': 0, '04': 0, '05': 0, '06': 0}

commands={
	'101': 'print',
	'102': 'add', 
	'103': 'sub', 
	'104': 'mul', 
	'105': 'div', 
	'106': 'mod', 
	'107': 'inc',
	'108': 'dec',
	'109': 'band',
	'110': 'bor',
	'111': 'bxor',
	'201': 'and',
	'202': 'or',
	'205': 'equal',
	'206': 'gt',
	'207': 'lt',
	'208': 'gte',
	'209': 'lte',
	'210': 'cmp',
	'301': 'mov',
	'302': 'mvi',
	'304': 'sta',
	'401': 'jmp',
	'402': 'jt',
	'403': 'jf',
	'501': 'push',
	'502': 'pop',
	'100': 'hlt',
	'200': 'nop',
	'400': 'inp'
}
