
# 프로필

<table>
    <tr>
        <td rowspan="6"><img src="/Images/image.jpeg" title="강인찬" style="width:100px;""/></td>
        <td style="width:200px;height:25px;">강인찬</td><td>1986</td>
    </tr>
    <tr><td>+82 10-7***-3***</td><td><a href="mailto:kangsazang@gmail.com"> kangsazang@gmail.com </a></td></tr>
    <tr><td><b>학력사항</td><td>2004.03 ~ 한국IT학교 휴학<br>2001.03 ~ 2004.02 덕수정보산업고등학교
</td></tr>
    <tr><td><b>자격사항</td><td>2003.11 한국산업인력공단 정보처리기능사</td></tr>
    <tr><td><b>병역사항</td><td>2005.09 ~ 2007.09 육군 병장 만기제대</td></tr>
</table>

## :mega: Introduce


## :cyclone: Skill Stack

| Category | Contents |
|---|---|
| Language | ![Swift](https://img.shields.io/badge/Swift-%20-FFFFFF?style=plastic&logo=Swift) ![Objective C](https://img.shields.io/badge/Objective%20C-%20-FFFFFF?style=plastic) ![Kotlin](https://img.shields.io/badge/Kotlin-%20-FFFFFF?style=plastic&logo=kotlin) ![ANDROID](https://img.shields.io/badge/Android(Java)-%20-FFFFFF?style=plastic&logo=android) ![TypeScript](https://img.shields.io/badge/TypeScript-%20-FFFFFF?style=plastic&logo=typescript) ![Javascript](https://img.shields.io/badge/Javascript-%20-FFFFFF?style=plastic&logo=Javascript) ![RUBY](https://img.shields.io/badge/Ruby-%20-FFFFFF?style=plastic&logo=Ruby) ![SH](https://img.shields.io/badge/ShellScript-%20-FFFFFF?style=plastic) |
| Architecture | [![MVC(apple)](https://img.shields.io/static/v1?label=&message=MVC(apple)&logo=MVC(apple))]() [![MVP](https://img.shields.io/static/v1?label=&message=MVP&logo=MVP)]() [![MVVM](https://img.shields.io/static/v1?label=&message=MVVM&logo=MVVM)]() [![FSD](https://img.shields.io/static/v1?label=&message=FSD&logo=FSD)]() |
| Framework / UI | ![React](https://img.shields.io/badge/React%2019-%20-FFFFFF?style=plastic&logo=react) ![TanStack Start](https://img.shields.io/badge/TanStack%20Start-%20-FFFFFF?style=plastic) ![TanStack Query](https://img.shields.io/badge/TanStack%20Query-%20-FFFFFF?style=plastic) ![TanStack Router](https://img.shields.io/badge/TanStack%20Router-%20-FFFFFF?style=plastic) ![Tailwind](https://img.shields.io/badge/Tailwind-%20-FFFFFF?style=plastic&logo=tailwindcss) ![shadcn/ui](https://img.shields.io/badge/shadcn/ui-%20-FFFFFF?style=plastic) |
| Build / Tooling | ![Turbo](https://img.shields.io/badge/Turbo-%20-FFFFFF?style=plastic&logo=turborepo) ![pnpm](https://img.shields.io/badge/pnpm-%20-FFFFFF?style=plastic&logo=pnpm) ![Vite](https://img.shields.io/badge/Vite-%20-FFFFFF?style=plastic&logo=vite) ![Biome](https://img.shields.io/badge/Biome-%20-FFFFFF?style=plastic&logo=biome) |
| Test | ![Vitest](https://img.shields.io/badge/Vitest-%20-FFFFFF?style=plastic&logo=vitest) ![Playwright](https://img.shields.io/badge/Playwright-%20-FFFFFF?style=plastic&logo=playwright) |
| Infra / Monitoring | ![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-%20-FFFFFF?style=plastic&logo=awslambda) ![Pulumi](https://img.shields.io/badge/Pulumi-%20-FFFFFF?style=plastic&logo=pulumi) ![Sentry](https://img.shields.io/badge/Sentry-%20-FFFFFF?style=plastic&logo=sentry) |
| Communication | ![WebSocket](https://img.shields.io/badge/WebSocket-%20-FFFFFF?style=plastic) ![Push](https://img.shields.io/badge/Push-%20-FFFFFF?style=plastic) |
| Experience | [![GitLab](https://img.shields.io/static/v1?label=&message=GitLab&logo=GitLab)]() [![Carthage](https://img.shields.io/static/v1?label=&message=Carthage&logo=Carthage)]() [![Fastlane](https://img.shields.io/static/v1?label=&message=Fastlane&logo=Fastlane)]() [![Jenkins](https://img.shields.io/static/v1?label=&message=Jenkins&logo=Jenkins)]() [![Travis CI](https://img.shields.io/static/v1?label=&message=Travis%20CI&logo=Travis%20CI)]() [![GraphQL](https://img.shields.io/static/v1?label=&message=GraphQL&logo=graphql)]() |


 ## :surfer: Interest

 [![TDD](https://img.shields.io/static/v1?label=&message=TDD&logo=TDD)]() [![TensorFlow](https://img.shields.io/static/v1?label=&message=TensorFlow&logo=TensorFlow)]() [![VIPER](https://img.shields.io/static/v1?label=&message=VIPER&logo=VIPER)]() [![Flutter](https://img.shields.io/static/v1?label=&message=Flutter&logo=Flutter)]() 
 [![Surfing](https://img.shields.io/static/v1?label=&message=Surfing&logo=Surfing)]() [![Synology](https://img.shields.io/static/v1?label=&message=Synology&logo=Synology)]() 




<br>

# 경력사항

## VIBE Coding (사용하고 있는 워크플로우 일부를 예시화)

* 이슈기반 자동화 워크플로우 
1. sentry, jira 에서 이슈 발생 
2. loop로 이슈 조회 후 서브 이슈로 분해
3. 서브 이슈별로 워크트리 생성 -> 
4. 서브 이슈별로 탐색 -> 분석 -> 평가(난이도, 복잡도, 재현여부 등등) -> 구현 -> 리뷰 -> 테스트(lint, typecheck, unit) -> 검증(E2E) -> PR 
   - 평가 단계에서 재현여부
   - 리뷰/테스트에서 실패시 재귀 
   - 검증에서 실패시 1회 재시도(구현을 되돌리고 실패 경험만 가지고 프롬프트를 제작성하도록 유도)
   - 검증에서 2회 실패시 사용자애게 보고  
5. PR 기준으로 사용자 검증 및 평가 

* TUI기반 Multi Agent 워크플로우 
1. Ghostty 터미널에서 메인 챗에서 사용자 요구사항 입력
2. 이슈 -> 분해 -> 서브이슈 2개 생성 
3. 현재 터미널 기준 오른쪽으로 화면 분할 3개 
   - |[메인챗][대시보드][서브이슈1][서브이슈2]|
4. 대시보드는 서브이슈별로 에이전트 이슈식별/시간/토큰샤용량/진행율 추적용도
5. 서브이슈별로 워크트리 생성 -> 클로드 실행 -> 서브이슈 진행. 

<br>

## NextIntelligence.ai (구 9folders)  
2021.03 ~   
에이전트팀 / FE 개발자 / 차장 

* **Office Agent (Web)** ([officeagent-fe](https://github.com/nextintelligence-ai/ai-agent-fe))  
AI Agent 프론트엔드 모노레포  
문서 검색(RAG), 웹, 이메일, 챗 검색, 전용 에이전트 생성/관리 등을 독립된 웹 서비스로 제공  

    **FE 서비스 구성**  
    `quick-agent` : 메일 화면 옆에 붙어 현재 보고 있는 메일에 대해 즉시 AI에게 질문할 수 있는 사이드 패널 서비스 
    `office-agent` : 사내 정보(문서, 챗, 쪽지, 메일, 일정, 연락처, 조직도) rag 검색과 맞춤형 AI 에이전트 생성·관리를 한곳에서 제공하는 직장인용 AI 비서 웹 서비스  
    `widget-agent` : 외부 사이트에 코드 한 줄로 붙여 가입 없이 AI와 대화할 수 있는 임베디드 챗봇 위젯
    `office-agent-admin` 
    `office-agent-backoffice`  

    **업무**  
    모노레포(Turbo + pnpm workspace) 설계 및 운영  
    TanStack Start, Query 기반 SSR 앱 구조 설계  
    FSD 6-layer 아키텍처 도입 및 규칙 정착  
    디자인 시스템(shadcn/ui + Tailwind) 구축 및 패키지화  + Google labs의 DESIGN.md 기반 디자인 시스템 반영
    채팅/스트리밍 코어 로직(`chat-core`, `chat-ui`) 설계  
    유닛 / 통합 / E2E 테스트 및 Sentry 기반 관측성 체계 구성  

<br>

[OfficeMail_Web]: https://app.officemail.io
[OfficeMail_Desktop]: https://officemail.app/desktop/download.html

* **Office Mail ([Web][OfficeMail_Web] / [Desktop][OfficeMail_Desktop] / iOS) - Chat 담당**  
Office Mail 제품군의 메신저/채팅 영역을 담당  
iOS 네이티브, Web(app.officemail.io), Desktop(Kotlin) 전 플랫폼에서 일관된 채팅 경험을 제공하도록 설계/운영  

    **업무**  
    iOS Chat 모듈 개발 및 유지보수 (1:1, 그룹 채팅, 파일/이미지 첨부, 읽음 처리)  
    Desktop(Kotlin) Chat 모듈 개발 및 유지보수  
    메시지 프로토콜 및 Push/Notification 연동  
    Native ↔ Web 브릿지 설계 (웹뷰 내 채팅 모듈 재사용)  
    성능 개선 (메시지 렌더링, 스크롤, 대용량 스레드 처리)  

<br>


[Re:Work]: https://apps.apple.com/app/id1528303399
[Re:Work Enterprise]: https://apps.apple.com/app/id1528303033
[Re:Work MobileIron]: https://apps.apple.com/app/id1606857955
  
* **Re:Work ([iOS][Re:Work], Android)**

Mail, Calendar, Contact, Task, Notes의 다양한 기능을 제공하는 업무 생산성을 높이는 앱 
Microsoft Exchange 및 Google workspace, Naver, Daum, Yahoo, IMAP 등등의 많은 메일 서비스를 지원 


    **업무**  
    mail protocol engine (EWS, EAS, Google, IMAP 등등)  
    B2C Re:Work  
        - 유지보수  
        - 신규 기능 및 UI Components 개발  
        - Widget 및 Extensions (Notification, Share, 등등)
        - 앱 구매, workspace, multi account 등등    
    B2B Customize mail app 개발 (K사, Rubus 등등)  
    빌드/배포 자동화 구축 및 운영  
    Re:Work Enterpirse의 MDM 또는 AppConfig를 Control 할 수 있는 내부 직원용 편의성 app 개발   

`#Objecitve-C #GraphGL #Jenkins #Fastlane #Zeplin #Notion` 

<br>

## Enliple 
2020.03 ~ 2021.03  
캠프사업부 / 과장

[CampTalk_AppStore]: https://apps.apple.com/kr/app/%EC%BA%A0%ED%94%84-%ED%86%A1/id1479500065

* **캠프 톡 ([iOS][CampTalk_AppStore], Android, Window)**   
카카오톡, 인스타그램, 네이버밴드를 종합한 연락처 기반 1:1채팅, 그룹채팅, 소식, 커뮤니티, 스토어 기능이 있는 SNS.  

    **업무**  
    iOS 신규 추가기능 개발  
    iOS 성능 개선 및 버그, 오류 수정  
    
    **주요성과**  
    빌드/배포 자동화(CI/CD) 환경 구축 (Git Push -> Jenkins -> Fastlane -> Testflight)  
    프로젝트 빌드 시간 개선 (CocoaPods -> Carthage 으로 변경, 10분에서 5분으로 개선)  

 * **퇴사사유**  
 예전에 함께 일했던 분께서 신규사업부 이사님으로 입사하시면서 저를 호출하게 되어 합류 하였지만 이사님은 3~4개월 만에 퇴사 함
 캠프톡 팀은 서비스 런칭 후 대표님의 단순 변심으로 인한 통보 없이 2월 말에 팀 해체 및 팀 전원이 대기발령
 특별한 보직이 없어 1개월 후 퇴사 


`#Objecitve-C #XMPP #Realm #AWS #Jenkins #Fastlane #Zeplin #Redmine` 

<br>

## NCNL 
2018.06 ~  2020.02  
개발팀 / 팀장

[Funtest_AppStore]: https://apps.apple.com/us/app/id1445647825  
[Funtest_Referance]: https://www.nextunicorn.kr/company/%EC%A3%BC%EC%8B%9D%ED%9A%8C%EC%82%AC%20%EC%97%94%EC%94%A8%EC%97%94%EC%97%98-ddcef73a65b13cf7/service/Funtest%20%ED%8E%80%ED%85%8C%EC%8A%A4%ED%8A%B8-9a3d845cf85a4a43

* **Funtest (~~[iOS][Funtest_AppStore]~~, [참고][Funtest_Referance])**   
정기적으로 주어지는 미션에 맞게 재미있는 콘텐츠를 업로드 하면 콘텐츠 우승자와, 콘텐츠 투표자가 *상금*을 나누어 받는 SNS.  

    **업무**
    전체적인 기획, 설계 참여   
    이슈/일정 관리
    iOS Funtest App 신규 개발 (Swift, MVVM, Rx, POP, HLS, 동영상편집)  
    iOS 관리자 App 신규 개발 (미션관리, 콘텐츠 모니터링, 상금관리, 유저관리)  
        
    **특이사항**    
    애자일 방법론 - 2주 단위의 주기로 스프린트를 수행 [계획/이슈공유 - 개발 - 배포 - 회고]  
    [https://www.draw.io] 를 이용하여 주요 프로세스를 다이어그램으로 생성  

 * **퇴사사유**  
 기술보증기금에서 실적미비로 대출 연장이 이뤄지지 않았고, 코로나로 인해 대표님들의 개인 사업건에 타격이 오면서 
 급작스럽게 폐업을 하게 됨  
    
`#스타트업 #Swift(MVVM, Rx, POP) #HLS #이미지/동영상편집 #AWS(S3, Cloudfront, Lamda, ElasticTranscoder) #GitLab #Fastlane #Jira #Confluence` 

<br>

## Gtrix 
2016.12 ~  2018.05  
신규서비스팀 / 과장

[Besty_AppStore]: https://itunes.apple.com/kr/app/besty/id1192060960

* **Besty  (~~[iOS][Besty_AppStore]~~)**   
자신만의 퀴즈(다지선다(단어, 이미지, 동영상), 서술형)를 생성하고, 다른사람의 퀴즈를 풀며 친밀도를 높이는 퀴즈 SNS  

    **업무**  
    iOS Besty App 신규 개발 (Swift, MVP)    
    App to Web 및 공통 Protocol 정의 (Scheme, Push Message, DeepLink)   
        
    **특이사항**    
    애자일 방법론 - 2주 단위의 주기로 스프린트를 수행 [계획/이슈공유 - 개발 - 배포 - 회고]  
    특정 사이트에서 이미지를 검색하여 보여주는 SlackBot 개발 (운영팀 요청사항)  

 * **퇴사사유**  
 판타지베이스볼(야구 카드배틀) 게임으로 중국에서 80억의 투자를 받았지만
 사드보복 사태로 인한 투자금 회수로 신규서비스팀이 없어짐   
 
 
 `#스타트업 #Swift(MPV) #고화질이미지 #에자일_개발론 #Slack #Jira #Confluence` 

<br>


## 프리랜서  

* **KT 고객센터**  (*2015.07 ~ 2016.12*)  
    iOS v4.0.0 서비스 고도화 (Widget 신규개발 포함)  
    iOS v4.x.x 서비스 운영   
    iOS v5.0.0 서비스 리뉴얼  

* **현대캐피탈**  (*2014.02 ~ 2015.06*)  
    현대캐피탈 iOS 운영 (Able Hybrid Framework)  
    현대캐피탈 Android 운영 (Able Hybrid Framework)  
    스마트페이앱 iOS 운영 (사내 서비스)  
    할부금계산기 iOS 운영 (사내 서비스)  
    카쉐어링 iOS 신규프로젝트 기술지원   

* **Woundary**  (*2013.08 ~ 2014.01*)        
    iOS 파트 리딩 (일정관리 및 이슈관리)  
    iOS Architecture 설계  
    iOS 개발  
    *대표의 단순변심으로 프로젝트 소멸    

* **우리파이넨셜 (현 KB캐피탈)**  (*2013.04 ~ 2013.08*)    
    iOS 신규 개발 (Alopex Hybird Platform 사용)  
    화면 개발 (js, html, jquery, javascript) 

* **시너벨리**  (*2012.03 ~ 2013.03*)  
     * IRKorea (iPad) iOS 신규개발 
     * 오스템 D-Talk iOS 신규개발
     * 안철수의 해피스 iOS 신규개발
     * 법륜스님의 희망편지 iOS 신규개발
     * 과외샘 찾기 iOS 신규개발
     * HiteMax iOS 신규개발 
     
* **한국무엽협회 사내 Mail App**  (*2011.07 ~ 2012.02*)  
    프로젝트 매니징 (Android, Server)   
    *턴키프로젝트   
    iOS 신규 개발     

* **골프날씨 (케이웨더)**  (*2011.04 ~ 2011.06*)  
    메모리 이슈 및 버그 수정   
    iOS 서비스 고도화  

* **농협 사내 Twitter**  (*2010.12 ~ 2011.04*)  
    중간에 개발자가 도망간 프로젝트 완성
    
* **올레스쿨(KT)**  (*2010.09 ~ 2010.12*)  
    iOS 신규 개발 


<!--

| 기간 | 프로젝트 | 내용 |
|---|---|---|
| 15.07 ~ 16.12 | KT 고객센터 | iOS v4.0.0 서비스 고도화 (Widget 신규개발 포함) <br> iOS v4.x.x 서비스 운영 <br> iOS v5.0.0 서비스 리뉴얼 <br> |
| 14.02 ~ 15.06 | 현대캐피탈 |     현대캐피탈 iOS / Android 운영 (Able Framework)  <br> 스마트페이앱 iOS 운영 (사내 서비스)  <br> 할부금계산기 iOS 운영 (사내 서비스)  <br> 카쉐어링 iOS 신규프로젝트 기술지원  <br> |
| 13.08 ~ 14.01 | Woundary | Woundary SNS iOS 개발 <br> iOS 파트 리딩 (아키텍쳐 설계, 개발 주도 및 팀원 관리) <br> *대표의 단순변심으로 프로젝트 소멸 |
| 13.04 ~ 13.08 | 우리파이넨셜<br>(현 KB캐피탈) | iOS 신규 개발 (Alopex Hybird Platform 사용) <br> 화면 개발 (js, html, jquery, javascript) |
| 12.03 ~ 13.03 | 시너벨리 |  IRKorea (iPad) iOS 신규개발 <br>오스템 D-Talk iOS 신규개발<br>안철수의 해피스 iOS 신규개발<br>법륜스님의 희망편지 iOS 신규개발<br>과외샘 찾기 iOS 신규개발<br>HiteMax iOS 신규개발 <br>
 |
| 11.07 ~ 12.02 | 한국무엽협회<br>사내 메일 App<br>(턴키 프로젝트) | 서비스 신규 개발 |
| 11.04 ~ 11.06 | 골프날씨 (케이웨더) | iOS 고도화 |
| 10.12 ~ 11.04 | 농협 사내 Twitter | 중간에 개발자가 도망간 프로젝트 완성 |
| 10.09 ~ 10.12 | 올레스쿨(KT) | iOS 신규개발 |

-->
