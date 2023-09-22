### Python 에러 리스트 목차 (확장)

#### 1. Syntax Errors (구문 에러)
  - `SyntaxError`: 코드의 구문이 잘못되었을 때 발생합니다.
  - `IndentationError`: 들여쓰기가 잘못되었을 때 발생합니다.

#### 2. Runtime Errors (런타임 에러)
  - `NameError`: 정의되지 않은 변수를 호출할 때 발생합니다.
  - `TypeError`: 데이터 타입이 잘못되었을 때 발생합니다.
  - `ValueError`: 데이터 값이 잘못되었을 때 발생합니다.
  - `IndexError`: 리스트의 인덱스 범위를 벗어났을 때 발생합니다.
  - `KeyError`: 딕셔너리에서 존재하지 않는 키를 호출할 때 발생합니다.
  - `AttributeError`: 객체가 해당 속성이나 메서드를 가지고 있지 않을 때 발생합니다.

#### 3. Logical Errors (논리 에러)
  - `ZeroDivisionError`: 0으로 나눌 때 발생합니다.
  - `FileNotFoundError`: 존재하지 않는 파일을 열려고 할 때 발생합니다.
  - `ArithmeticError`: 산술 연산에서 발생하는 기본 클래스로, `OverflowError`, `ZeroDivisionError` 등이 여기에 속합니다.

#### 4. Import Errors (임포트 에러)
  - `ImportError`: 모듈을 찾을 수 없을 때 발생합니다.
  - `ModuleNotFoundError`: 특정 모듈 내의 함수나 클래스를 찾을 수 없을 때 발생합니다.

#### 5. Warning Errors (경고 에러)
  - `DeprecationWarning`: 더 이상 사용되지 않는 기능을 사용할 때 발생합니다.
  - `SyntaxWarning`: 문법적으로 문제는 없지만, 의심스러운 구문을 사용할 때 발생합니다.

#### 6. Custom Errors (사용자 정의 에러)
  - 사용자가 직접 정의한 에러입니다.

#### 7. Exception Handling (예외 처리)
  - `try`, `except`, `finally` 등을 사용한 예외 처리 방법

#### 8. Others (기타)
  - `OverflowError`: 수치 연산 결과가 너무 클 때 발생합니다.
  - `MemoryError`: 메모리가 부족할 때 발생합니다.

#### 9. OS Errors (운영체제 에러)
  - `OSError`: 운영체제 레벨에서 발생하는 에러, 파일을 열거나 닫을 때 등에 발생할 수 있습니다.
  - `PermissionError`: 파일이나 디렉토리에 대한 권한이 없을 때 발생합니다.

#### 10. Network Errors (네트워크 에러)
  - `ConnectionError`: 네트워크 연결 관련 에러입니다.
  - `TimeoutError`: 연산을 완료하기 위한 시간이 초과되었을 때 발생합니다.