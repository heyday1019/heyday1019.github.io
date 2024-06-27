## Scalar data type and iterable data type의 주요 차이점

Scalar data type and iterable data type의 주요 차이점은 다음과 같습니다:

1. **Scalar data type**:

   - **정의**: 단일 값으로 구성된 데이터 타입입니다. 이 값은 원자적이고 더 이상 분해할 수 없습니다.

   - **예시**: 정수(int), 부동 소수점(float), 문자열(string), 불(boolean) 등이 포함됩니다.

   - **특징**: 단일 값을 표현하므로 반복할 수 없습니다.

   - 사용 예

     :

     ```
     pythonCopy codescalar_int = 42
     scalar_float = 3.14
     scalar_string = "Hello, world!"
     scalar_bool = True
     ```

2. **Iterable data type**:

   - **정의**: 여러 값을 포함할 수 있으며, 각 값에 반복적으로 접근할 수 있는 데이터 타입입니다.

   - **예시**: 리스트(list), 튜플(tuple), 딕셔너리(dict), 집합(set) 등이 포함됩니다.

   - **특징**: 내부에 여러 요소를 포함할 수 있으며, 반복문을 사용하여 각 요소에 접근할 수 있습니다.

   - 사용 예

     :

     ```
     pythonCopy codeiterable_list = [1, 2, 3, 4, 5]
     iterable_tuple = (1, 2, 3)
     iterable_dict = {'a': 1, 'b': 2, 'c': 3}
     iterable_set = {1, 2, 3, 4, 5}
     
     for item in iterable_list:
         print(item)
     ```

### 요약

- **Scalar**: 단일 값을 가지며 반복 불가능 (예: `int`, `float`, `str`, `bool`)
- **Iterable**: 여러 값을 포함하며 반복 가능 (예: `list`, `tuple`, `dict`, `set`)

이 두 데이터 타입의 차이는 값의 개수와 반복 가능 여부에 있습니다. Scalar는 단일 값이고, iterable은 여러 값을 포함하여 반복할 수 있습니다.