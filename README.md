## git 우당탕탕 시나리오

### (conflict 및 에러가 발생하도록 만든 시나리오)

1. github에서 organization을 생성해보세요.
2. organization에서 repository를 생성해보세요. _(add a README file 체크)_
3. organization에 있는 repository를 fork해보세요.
4. local computer로 clone해보세요.
5. local computer에 repository의 main branch에서 `resume.txt` 파일을 만들고 commit해보세요. _(commit 메시지 자유)_
6. main branch에서 `personal_statement.txt` 파일을 만들고 commit해보세요.
7. `sub1`이라는 이름의 branch를 만드시고 `sub1` branch에서 `resume.txt`에 `기본사항(경력, 학력, 이름, 나이 등)`을 작성하고 commit해보세요.
8. main branch로 이동하세요.
9. main branch에서 `sub2`라는 branch로 checkout 후 `personal_statement.txt`에 `자기 소개`를 쓰고 commit 해보세요.
10. main branch에서 `resume.txt` 파일에 `자격증, 대외활동, 사용기술`을 작성하고 commit해보세요.
11. main branch에서 `personal_statement.txt` 파일에 `개발자로서 포부`를 작성하고 commit해보세요.
12. main branch에서 `sub1` branch를 merge해보세요.
13. main branch에서 `sub2` branch를 merge해보세요.
14. local computer에서 origin으로 push해보세요.
15. github origin에서 organization으로 PR 요청을 해보세요.
16. merge를 해보세요.
17. upstream의 main branch를 local main branch로 pull 해보세요.
