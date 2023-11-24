# Merge :laughing:

**＃1장에서 branch를 통해 독립된 컨텍스트에서 효율적으로 작업할 수 있음을 알았다**
<br>
**＃merge는 항상 목표의 Head branch로 이동해 실행한다 Head branch는 다른 branch에 merge되지 않는다**
<br>
<br>

## Merge Command :bookmark:
<details>
<summary>click</summary>
<div markdown="1">  
  
<br>

:mag: **git merge branch-name** : main Head에 branch-name을 merge한다 여기서 main Head는 merge되는 branch에 추가된 commit을 감아가며 포인터를 이동시킨다
<br>

</div>
</details>

<br>

## Merge Situation :bookmark:
<details>
<summary>click</summary>
<div markdown="1">  
  
<br>

:mag: **일반적 fast-forward merge** : main branch에 다른 팀원의 merge가 없고 내가 작업한 하나의 branch만이 존재할 경우엔 merge 커맨드를 통해 합칠 수 있다
<br>

:mag: **충돌이 없는 merge commit** : 내가 다른 branch에서 작업하는 동안 동료가 main branch에 다른 branch를 merge해 내 branch의 이전 내용과 다른 내용이 추가된 상태에서 merge할 경우, 두 branch가 충돌하지 않는다면 깃은 두개의 부모 커밋을 가진 병합 커밋을 생성한다
<br>

:mag: **충돌되는 merge commit** :
<br>


</div>
</details>
