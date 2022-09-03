# Today I Learned

## 2022.08.22

### FastAPI (Tandanji)

- Static 폴더 설정
- Jinja2 template을 활용한 Page Rendering 설정
- Authentication 모듈화
- Pyrebase를 통한 Firebase Authentication 연결
- Pyrebase를 통한 Firebase RealTimeDatabase 연결
- Pyrebase1은 npm 설치를 제공하지 않는데 어떻게 할까?<br>
  `최신버전이 존재함: pip install pyrebase4`

## 2022.08.26

### Nestjs_Deploy

- Github Actions를 활용하여 자동 배포하는 과정 학습
- AWS ECS에서 컨테이너 포트를 3000으로 생성했는데 어떻게 80으로 진입할 수 있을까?<br>
  `로드밸런서에서 Listner 포트를 80으로 설정`
- AWS ECS에서 Service 기본설정을 Fargate로 진행시 로드밸런서를 생성할때 제약이있음<br>
  `Fargate가 동적으로 작동하기 때문에 IP Address Mode로 생성해야 인식함`
- AWS ECS에서 Service 기본설정을 Fargate로 진행시 Task-definition에서 Container Port와 Host Port는 동일해야함
- AWS ECR 설정시 IAM이 설정되어있으면 Private Repository도 접근할 수 있음

## 2022.08.27

### Publishing (IEUM)

- Figma 프로토타입을 바탕으로 HTML, CSS 제작
- Flex를 주로 사용하여 구조를 조정

```
position:absolute; top:50%; left:50%; transform: translate(-50%, -50%);
```

부모요소에 postion:relative를 적용하고 자식요소에 위 코드를 적용하면 요소가 가운데 중앙으로 정렬

```
position:absolute; top:50%; transform: translate(0%, -50%);
```

위 코드는 세로 중앙에 배치

## 2022.09.04

### Popool (Backble-한이음)

- Github Actions를 활용하여 멀티모듈로 설정되어있는 레포지토리를 한번에 각각의 서버로 배포를 시도함
- Github Actions WorkFlow에 작성된 코드를 바탕으로 AWS Elastic BeanStalk까지 배포를 완료하는 것이 목표
- 하지만, Gradle Build 과정에서 오류가 생겨서 해당 문제를 수정하는 과정에 있음

<hr>

### 계획
- Hadoop EcoSystem
- Kafka
- K8s
- Nest.js
- Spring boot
- Oauth 프로세스 분석
- CICD 분석 및 아키텍처 예시로직 제작
