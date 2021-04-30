# Конструкции языка, Optinal, Типы данных в Swift
## Категории типов данных в swift
- Named
- Compound

### Категории типов данных: Named
- protocol
- class 
- enum
- struct 
		- bool
		- Int, UInt
		- Decimal, Float, Double
		- String, Character
		- Array, Set, Dictionary

### Категории типов данных: Compound
- tuple
- function

## Value and Reference type Difference

![[ValueReferenceTypeDiff.png]]

## Virtual Address Space
![[VirtualAddressSpace.png]]

## Optional
- Зачемнужен Optional?
- Обеспечивает безопасную работу с переменными в момент компиляции программы. Вместопроверкина nil (null pointer), разработчик должен извлечь данные из Optional value, если он это несделает программа нескомпилируется, в отличие от Runtime exception

## Access Contorol
- Open
- Public
- Internal
- Fileprivate
- Private
