2024-06-27-datetime 라이브러리 예제 코드 (python)

Python의 `datetime` 모듈은 날짜와 시간을 다룰 수 있는 여러 클래스를 제공합니다. 아래에 `datetime` 모듈의 다양한 사용 예제를 제시합니다.

1. **현재 날짜와 시간 가져오기**

   ```
   pythonCopy codefrom datetime import datetime
   
   now = datetime.now()
   print("현재 날짜와 시간:", now)
   설명
   ```

2. **특정 날짜와 시간 생성하기**

   ```
   pythonCopy codefrom datetime import datetime
   
   specific_date = datetime(2024, 6, 27, 14, 33, 0)
   print("특정 날짜와 시간:", specific_date)
   설명
   ```

3. **날짜와 시간 형식화**

   ```
   pythonCopy codefrom datetime import datetime
   
   now = datetime.now()
   formatted_date = now.strftime("%Y-%m-%d %H:%M:%S")
   print("형식화된 날짜와 시간:", formatted_date)
   설명
   ```

4. **날짜 계산**

   ```
   pythonCopy codefrom datetime import datetime, timedelta
   
   now = datetime.now()
   tomorrow = now + timedelta(days=1)
   print("내일 이 시간:", tomorrow)
   설명
   ```

5. **날짜와 시간 파싱**

   ```
   pythonCopy codefrom datetime import datetime
   
   date_string = "2024-06-27 14:33:00"
   parsed_date = datetime.strptime(date_string, "%Y-%m-%d %H:%M:%S")
   print("파싱된 날짜와 시간:", parsed_date)
   ```