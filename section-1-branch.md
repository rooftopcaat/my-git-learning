# Branch :laughing:

**＃2020년 이후 default branch명은 master에서 main을 쓰는게 관례가 되었다**
<br>
**＃commit은 해시값으로 변경되어 전달된다**

<br>
<br>

## Head :bookmark:
<details>
<summary>click</summary>
<div markdown="1">       
  
<br>
Head는 현재 작업중인 branch의 포인터로,
<br>
A라는 새로운 branch를 만들고 Head가 A에 위치하면 모든 작업은 그 branch에만 영향을 미친다

</div>
</details>

<br>

## Branch Command :bookmark:

<details>
<summary>click</summary>
<div markdown="1">       

<br>

:mag: **git branch** : 저장소에 현재 존재하는 branch 목록을 보여준다
<br>

:mag: **git branch branch-name** : branch-name의 새 branch가 생성된다
<br>

:mag: **git switch branch-name** : branch-name으로 Head가 전환된다 -c를 추가하면 생성후 그 branch로 이동한다
<br>

:mag: **git log** : 해당 저장소의 커밋 기록을 가장 최근부터 보여준다
<br>

:mag: **git commit -a -m "message"** : 모든 변경사항에 메시지를 추가해 커밋한다
<br>

:mag: **git stash** : 변경사항 임시 저장
<br>

:mag: **git stash pop** : 다른 branch로 변경을 한 후에, 임시저장된 변경사항을 다시 적용하기 (변경사항은 손실되지 않고 새 branch에서도 계속 보존됨)
<br>

:mag: **git branch -d branch-name** : branch-name branch 삭제 branch가 merge되지 않았어도 강제삭제하려면 -D
<br>

:mag: **git push github-repo-name --delete branch-name** : github의 원격 저장소에 있는 branch를 삭제 (origin도 사용가능) 
<br>

:mag: **git branch -m branch-name change-branch-name** : branch-name을 change-branch-name으로 바꿈 branch 관련의 -m은 message가 아닌 move이다
<br>

:mag: **git push github-repo-name change-branch-name** : 이름 변경된 branch를 원격 저장소에 푸시
<br>

:mag: **git push github-repo-name --delete branch-name** : 원격 저장소의 기존 branch 삭제
<br>

</div>
</details>

<br>





