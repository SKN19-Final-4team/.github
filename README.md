# Git Convention Guide

GitHub Organizations 내 모든 프로젝트에서
Issue 및 Pull Request 작성 시 동일한 컨벤션과 템플릿을 적용

## 생성된 이슈 기반 개발 및 PR 요청 절차
### step 1. 이슈 생성하기
### step 2. 이슈 번호를 이용하여 브랜치 생성
    
```bash
# 브랜치별 역할
main                            → 최종 배포 버전
develop							→ 배포 전 통합 테스트
feature_merge					→ 기능 통합 중간 브랜치
feature/이슈번호-[name]          → 개별 기능 개발 브랜치

# 기능별 브랜치명 예시
feature/이슈번호-data-crawling
feature/이슈번호-rag-pipeline
feature/이슈번호-setting-page
```
        
### step 3. 기능 개발
### step 4. commit and push
        
```bash
# 커밋 Header Type
1. feat: 새로운 기능
2. fix: 버그 수정
3. build: 빌드 관련 파일 수정 / 모듈 설치 또는 삭제
4. chore: 그 외 자잘한 수정
5. ci: ci 관련 설정 수정
6. docs: 문서 수정
7. style: 코드 스타일 혹은 포맷 등
8. refactor: 코드 리팩토링
9. test: 테스트 코드 추가 및 수정
10. perf: 성능 개선
```
        
### step 5. pull request(PR 생성)
        
    이슈 하나 당 PR 하나 생성
        
### step 6. merge 이후 코멘트에서 이슈 추적
        
    최소 N명 이상의 리뷰 승인 후 merge
        
### step 7. 완료된 이슈 close 처리 하기