# Docstring 이란

---

- Docstring은 모듈, 함수, 클래스 또는 메소드 정의의 첫 번째 명령문으로 발생하는 문자열 리터럴
- Docstring은 해당 객체의 doc 특수 속성으로 변환됨 - print(add.__doc__)
- [Docstring양식문서](https://peps.python.org/pep-0257/)



# Docstring 작성법

----

- 아래와 같은 함수를 만들었을 때,

  def add(a, b):
      return a + b

  add(1,2)

  ---

  - Module 첫번째 줄, 함수 선언 후 내부 바로 아랫줄 또는 클래스 선언 후 내부 바로 아랫줄에 큰따옴표 3개나 작은 따옴표 3개로 작성하면됩니다.

  

  #ChatGPT를 이용하여 Docstring 한 결과입니다.

  def add(a, b):
      """
      Adds two numbers and returns the result.

  ```python
  Parameters:
  a (int or float): The first number to add.
  b (int or float): The second number to add.
  
  Returns:
  int or float: The sum of the two numbers.
  
  Examples:
  >>> add(1, 2)
  3
  >>> add(3.5, 2.5)
  6.0
  """
  return a + b
  ```

