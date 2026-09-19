# github-artifact-pilot
DEV UAT PROD Artifact Promotion Pilot
github 테스트 flow
환경 우선 
1. local에서 프로그램 작성
2. commit&Push
3. Pipeline-p1,p2,p3,p4 수행
4. P1 : artifact 생성,
5. p2 : Artifact 수행 run-id를 받는다
6. P3 : approval gate의 승인을 통하여 p4를 보낸다
7. 자동/ 수동 
