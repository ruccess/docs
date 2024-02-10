1. **헤더와 제목:**
   ```markdown
   # 제목 1
   ## 제목 2
   ### 제목 3
   ```
   **예시:**
   # 제목 1
   ## 제목 2
   ### 제목 3

2. **강조:**
   ```markdown
   *이탤릭체* 또는 _이탤릭체_
   **굵은체** 또는 __굵은체__
   ```
   **예시:**
   *이탤릭체* 또는 _이탤릭체_
   **굵은체** 또는 __굵은체__

3. **코드 블록:**
   ```markdown
   ```python
   def hello_world():
       print("Hello, World!")
   ```
   ```
   **예시:**
   ```python
   def hello_world():
       print("Hello, World!")
   ```

4. **리스트와 체크리스트:**
   ```markdown
   순서 없는 리스트:
   - 항목 1
   - 항목 2
     - 하위 항목

   순서 있는 리스트:
   1. 항목 1
   2. 항목 2

   체크리스트:
   - [x] 완료된 작업
   - [ ] 미완료 작업
   ```
   **예시:**
   - 항목 1
   - 항목 2
     - 하위 항목

   1. 항목 1
   2. 항목 2

   - [x] 완료된 작업
   - [ ] 미완료 작업

5. **인용문:**
   ```markdown
   > 인용문을 작성하세요.
   ```
   **예시:**
   > 인용문을 작성하세요.

6. **링크와 이미지:**
   ```markdown
   [링크 텍스트](http://example.com)
   ![이미지 대체 텍스트](http://example.com/image.jpg)
   ```
   **예시:**
   [링크 텍스트](http://example.com)
   ![이미지 대체 텍스트](http://example.com/image.jpg)

7. **수평선:**
   ```markdown
   ---
   ```
   **예시:**
   ---

8. **표 (Table):**
   ```markdown
   | 헤더1 | 헤더2 |
   |------|------|
   | 셀1   | 셀2   |
   ```
   **예시:**
   | 헤더1 | 헤더2 |
   |------|------|
   | 셀1   | 셀2   |

9. **숨겨진 텍스트 (Details):**
   ```markdown
   <details>
   <summary>클릭하여 내용 보기</summary>

   여기에 숨겨진 내용을 작성하세요.

   </details>
   ```
   **예시:**
   <details>
   <summary>클릭하여 내용 보기</summary>

   여기에 숨겨진 내용을 작성하세요.

   </details>

10. **배지 (Badge):**
    ```markdown
    [![Build Status](https://travis-ci.org/username/repo.svg?branch=master)](https://travis-ci.org/username/repo)
    ```
    **예시:**
    [![Build Status](https://travis-ci.org/username/repo.svg?branch=master)](https://travis-ci.org/username/repo)

11. **이모지 활용:**
    ```markdown
    :rocket: :computer: :books:
    ```
    **예시:**
    :rocket: :computer: :books:

12. **수필 형식의 텍스트:**
    ```markdown
    > 이렇게 작성하면 수플 형식의 텍스트를 만들 수 있습니다.
    ```
    **예시:**
    > 이렇게 작성하면 수플 형식의 텍스트를 만들 수 있습니다.

13. **라인 하이라이팅:**
    ```markdown
    `라인 하이라이팅`을 활용하면 특정 부분을 강조할 수 있습니다.
    ```
    **예시:**
    `라인 하이라이팅`을 활용하면 특정 부분을 강조할 수 있습니다.

14. **수학식 표현:**
    ```markdown
    수학식을 표현할 수 있습니다: $E=mc^2$
    ```
    **예시:**
    수학식을 표현할 수 있습니다: $E=mc^2$

15. **취소선:**
    ```markdown
    이것은 ~~취소선~~ 입니다.
    ```
    **예시:**
    이것은 ~~취소선~~ 입니다.

16. **각주:**
    ```markdown
    문장[^1]에 각주를 추가할 수 있습니다.

    [^1]: 각주의 설명입니다.
    ```
    **예시:**
    문장[^1]에 각주를 추가할 수 있습니다.

    [^1]: 각주의 설명입니다.

17. **페이지 내부 링크:**
    ```markdown
    [페이지 내부 링크](#section-heading)
    ```
    **예시:**
    [페이지 내부 링크](#section-heading)

19. **색상 표현:**
    ```markdown
    이 문장은 <span style="color:red">빨간색</span>으로 표시됩니다.
    ```
    **예시:**
    이 문장은 <span style="color:red">빨간색

20. **YouTube 동영상 삽입:**
    ```markdown
    [![동영상 썸네일](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID)
    ```
    **예시:**
    [![동영상 썸네일](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID)

21. **텍스트 정렬:**
    ```markdown
    왼쪽 정렬: <p align="left">내용</p>
    가운데 정렬: <p align="center">내용</p>
    오른쪽 정렬: <p align="right">내용</p>
    ```
    **예시:**
    왼쪽 정렬: <p align="left">내용</p>
    가운데 정렬: <p align="center">내용</p>
    오른쪽 정렬: <p align="right">내용</p>

22. **윗첨자와 아래첨자:**
    ```markdown
    이것은 H<sub>2</sub>O와 같은 아래첨자입니다.
    X<sup>2</sup>는 윗첨자입니다.
    ```
    **예시:**
    이것은 H<sub>2</sub>O와 같은 아래첨자입니다.
    X<sup>2</sup>는 윗첨자입니다.

23. **이미지 링크:**
    ```markdown
    [![대체 텍스트](이미지URL)](링크URL)
    ```
    **예시:**
    [![대체 텍스트](이미지URL)](링크URL)

24. **HTML 직접 사용:**
    ```markdown
    직접 <kbd>HTML</kbd>을 사용할 수 있습니다.
    ```
    **예시:**
    직접 <kbd>HTML</kbd>을 사용할 수 있습니다.

25. **문자 수 세기:**
    ```markdown
    이 문단은 {% include count.html %} 문자로 이루어져 있습니다.
    ```
    **예시:**
    이 문단은 {% include count.html %} 문자로 이루어져 있습니다.

26. **플로팅 이미지:**
    ```markdown
    <img src="이미지URL" align="right" width="300px">
    ```
    **예시:**
    <img src="이미지URL" align="right" width="300px">

27. **줄 바꿈:**
    ```markdown
    문장이 끝나면 스페이스 두 번  
    다음 줄로 넘어갑니다.
    ```
    **예시:**
    문장이 끝나면 스페이스 두 번  
    다음 줄로 넘어갑니다.

28. **줄 간격 조절:**
    ```markdown
    문장1

    문장2
    ```
    **예시:**
    문장1

    문장2
