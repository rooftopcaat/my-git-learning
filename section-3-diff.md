# Diff :laughing:

**＃2장에서 merge를 통해 branch를 합칠 때 일어나는 일들을 알아보았다**
<br>
**＃diff는 깃에서의 변경 사항들을 보여주는 명령어이다 주어진 저장소 안에서 상황에 따라 변경된 사항들을 파악할 수 있다**
<br>
<br>

## Diff Command :bookmark:
<details>
<summary>click</summary>
<div markdown="1">  
  
<br>

:mag: **git diff** : 스테이징되지 않은 워킹 디렉토리 안에 있는 변경사항 목록 조회
<br>
:mag: **git diff HEAD** : HEAD 포인터가 가리키는 최신 커밋과 워킹 디렉토리 간의 차이를 조회 
<br>

</div>
</details>

## Diff Reading :bookmark:
<details>
<summary>click</summary>
<div markdown="1">  
  
<br>

:mag:
```
diff --git a/A.txt b/B.txt (이전 버전과 새 버전) (설정에 따라 다른 파일이 될 수도 있다)
index 52d1d5a..f2c8147 107056
--- a/A.txt (파일 A가 변경되어)
+++ b/B.txt (파일 B가 되었음)
@@ -3,4 +3,5 @@ A (chunks : 변경된 부분과 앞뒤 컨텍스트만을 보여줌) (-, + 숫자는 덩어리에서 -줄에서 4만큼 추출, +줄에서 5만큼 첨가) (A는 preview 이다)
즉 파일 A의 3번줄부터 +4줄이 3번줄부터 +5까지 바뀌었다는 뜻
  B
  C
  D
  -E
  +F
  +G
```
<br>

</div>
</details>

