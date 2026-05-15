# 1. git branch 전략 비교
## 1.1. git flow의 방식
다양한 가짓수의 branch를 사용함.

master(main): 제품 출시 버전을 관리하는 메인 브랜치
develop: 다음 출시 버전을 위해 개발하는 브랜치
feature: 새로운 기능을 개발하는 브랜치
release: 다음 출시 버전을 준비하는 브랜치
hotfix: 출시된 제품의 버그를 고치기 위한 브랜치

- 주요한 특징: 더 많은 제어와 복잡성 존재. 배포 안정성과 버전 관리 및 롤백 등의 체계적인 운영 면에서 강점을 가짐. 대규모 프로젝트에 더 적합

## 1.2. github flow의 방식
보다 간단한 구조로 사용함.
branch를 **하나의 base 브랜치 (master) + master 에 기능을 추가하기 위한 브랜치(feature)**

- 주요한 특징: 테스트와 검증 절차를 거치지 않고 바로 master 브랜치로 merge되므로 위험성 존재. 하지만 그만큼 단순하며 빠르게 기능을 테스트할 수 있음. 작은 규모의 프로젝트에 더 적합.



# 2. commit convension
기본적으로 아래의 형태를 가지고 해당 커밋이 무엇을 했는지를 요약함.

type 예시
p{
    feat: 새로운 기능 추가
    fix: 버그 수정
    docs: 문서 수정
    style: 코드 의미에 영향을 주지 않는 변경
    refactor: 코드 리팩토링 (기능은 그대로, 코드 구조 개선)
    test: 테스트 코드 추가 및 수정
}

참고자료
[git branch 전략비교](https://devocean.sk.com/blog/techBoardDetail.do?ID=165571&boardType=techBlog)