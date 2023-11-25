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

:mag: **git diff** : 커밋 / 워킹 디렉토리 / 스테이지 변경사항 비교
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
diff --git a/A.txt b/B.txt
index 52d1d5a..f2c8147 107056
--- a/A.txt
+++ b/B.txt
@@ -3,4 +3,5 @@ A
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

