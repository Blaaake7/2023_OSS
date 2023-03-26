## Week3
   
### 이미지   
![항공대 로고](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTUKdDatfvvzf1oXosMhPDBiXY_kaBUhV6UCw&usqp=CAU)
   
### 링크
   
[LMS](https://lms.kau.ac.kr/login.php)
   
### Progit 링크
   
[ProGit](https://git-scm.com/book/en/v2)
   
### 주요 git 명령어
* add: 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용
   
* commit
   
* branch
   
* merge
   
* status
   
* log
   
### 2주차 숙제
   
```
#!/bin/bash

# 이름, 학번
name="이영진"
student_id="2018127041"

# 파일 경로, 줄 수, 마지막 줄
file_path=$(find /home/kau2 -name "w2_homework.txt" 2> /dev/null)
line_number=$(wc -l < "$file_path")
last_line=$(tail -n 1 "$file_path")

# 결과 출력
echo "----------"
echo "name :"
echo "$name"
echo -e "\n"
echo "----------"
echo "student id :"
echo "$student_id"
echo "----------"
echo -e "\n"
echo "file path :"
echo "$file_path"
echo -e "\n"
echo "----------"
echo "line number :"
echo "$line_number"
echo -e "\n"
echo "----------"
echo "last line :"
echo "$last_line"
```
   
### 마크다운
   
#### 목록
   
##### 번호있는 목록
   
1. 첫번째
2. 세번째
3. 두번째
   
##### 번호없는 목록:*,-,+
* 첫번째
   
* 세번째
   
* 두번째
<hr/>
   
* 빨강   
- 녹색   
+ 파랑
   
#### 강조
   
*single asterisks*   
_single underscores_   
**double asterisks**   
__double underscores__   
~~cancelline~~
