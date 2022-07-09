# 🥅 골키퍼 를 소개합니다
목표 달성 자극 서비스입니다. 목표와 함께 보증금을 등록하고 서로간의 검증을 통해 목표달성에 성공하면 보증금과 추가로 축하금을 줍니다. 반면, 달성에 실패하면 보증금을 가져갑니다. 

***

# 🙋‍♂️ Member

<table align="center">
  <tr>
    <td align="center">
      <a href="https://github.com/sancy1003">
        <img src="https://avatars.githubusercontent.com/u/55091812?v=4" width="100px;" alt=""/><br />
        <sub>
          <b>박찬영</b>
        </sub>
      </a><br />
    </td>
    <td align="center">
      <a href="https://github.com/jeongye01">
        <img src="https://avatars.githubusercontent.com/u/74299317?v=4" width="100px;" alt=""/><br />
        <sub>
          <b>정예원</b>
        </sub>
      </a><br />
    </td>
    <td align="center">
      <a href="https://github.com/ahn0min">
        <img src="https://avatars.githubusercontent.com/u/89904226?v=4" width="100px;" alt=""/>
        <br />
        <sub>
          <b>안영민</b>
        </sub>
      </a><br />
    </td>
    <td align="center">
      <a href="https://github.com/robinjoon">
        <img src="https://avatars.githubusercontent.com/u/45223837?v=4" width="100px;" alt=""/><br />
        <sub>
          <b>임수빈</b>
        </sub>
      </a><br />
    </td>
    <td align="center">
      <a href="https://github.com/suyeon39">
        <img src="https://avatars.githubusercontent.com/u/102038895?v=4" width="100px;" alt=""/><br />
        <sub>
          <b>수연</b>
        </sub>
      </a><br />
    </td>
  </tr>
  <tr>
    <td rowspan="1" align="center">
        <b>FRONT-END</b>
    </td>
    <td rowspan="1" align="center">
        <b>FRONT-END</b>
    </td>
    <td rowspan="1" align="center">
        <b>FRONT-END</b>
    </td>
    <td rowspan="1" align="center">
        <b>BACK-END</b>
    </td>
    <td rowspan="1" align="center">
        <b>Design</b>
    </td>
  </tr>
</table>

***

# 🖥 프로젝트 미리보기

<table align="center">
  <tr>
    <td width="230px">
        <img src="./profile/public/image/readme/main.gif" style="width: 100%; height: auto;" alt="통계 기능"/>
    </td>
    <td width="230px">
        <img src="./profile/public/image/readme/goalRegist.gif" style="width: 100%; height: auto;" alt=""/>
    </td>
    <td width="230px">
        <img src="./profile/public/image/readme/certRegist.gif" style="width: 100%; height: auto;" alt=""/>
    </td>
  </tr>
  <tr>
    <td rowspan="1" align="center">
        <b>통계 기능</b>
    </td>
    <td rowspan="1" align="center">
        <b>목표 등록</b>
    </td>
    <td rowspan="1" align="center">
        <b>목표 인증 등록</b>
    </td>
  </tr>
  <tr>
    <td width="230px">
        <img src="./profile/public/image/readme/certDetail.gif" style="width: 100%; height: auto;" alt=""/>
    </td>
    <td width="230px">
        <img src="./profile/public/image/readme/chargeMoney.gif" style="width: 100%; height: auto;" alt=""/>
    </td>
    <td width="230px">
    </td>
  </tr>
  <tr>
    <td rowspan="1" align="center">
        <b>목표 인증</b>
    </td>
    <td rowspan="1" align="center">
        <b>목표머니 충전 </b>
    </td>
    <td rowspan="1" align="center">
    </td>
  </tr>
</table>

***

# 프론트엔드 

## 🤙 코딩 컨벤션

- 페이지 명, 컴포넌트 명, 라우트 경로 작명 시 pascal case 방식으로 작명하며 그 외의 모든 함수, 변수 등의 작명은 camel case 방식으로 작명하기로 했어요.
- page 구현 시 Container Presenter Pattern을 사용하여 구현하기로 했어요.
- Prettier, ESLint를 사용하여 코드 작성 규칙과 코딩 스타일을 맞추기로 했어요.

<br/>

## ⌨️ 협업 방식

- `Figma`, `Zeplin`에 디자인된 화면을 기반으로 UI / UX를 구현했어요.
- `Notion` 을 통해 진행 사항, 제안 사항, 참고 자료들을 기록했어요.
- `Discord` 의 음성 대화, 화면 공유를 활용하여 비대면으로 협업을 진행했어요.
- `Storybook`을 사용하여 공통 컴포넌트를 미리 확인하고 사용할 수 있도록 했어요.

<br/>

## ✍️ 깃 사용 방법

- **브랜치 종류**
    - **main** : main 브랜치를 기준으로 배포를 진행해요.
    - **develop** : 개발을 진행하는 중심 브랜치에요.
    - **feature** : 새로운 기능을 개발하는 브랜치에요.
    
<br />

- **Feature 브랜치 네이밍 규칙**
    - `{브랜치 종류}/{{기능이름}}`
    - ex) `feature/login`

<br/>

## ⚡ 기술 스택

- `Typescript` : 코드의 안정성을 높이고 협업의 효율을 높이기 위해 Typescript를 사용했어요.
- `React` : component 단위의 개발, 사용자의 사용성을 고려한 SPA 개발을 하기 위해 React를 사용했어요.
- `Redux` : 프로젝트의 확장성과 유지 보수를 고려하고 action을 통해 상태를 추적하여 구조적으로 상태를 관리하기 위해 Redux를 사용했어요.
- `Redux-Saga` : Redux와 함께 사용하여 효율적인 API 로직을 작성하기 위해 Redux-Saga를 사용했어요.
- `Storybook` : 자신이 작업하지 않은 컴포넌트 또한 직관적으로 파악하기 위해 Storybook을 사용하여 공통 컴포넌트를 미리 확인하고 사용해 볼 수 있도록 했어요.
- `TailwindCSS` : Utility-First 컨셉으로 인해 쉽고 빠른 ui 작성이 가능, 클래스명 작성 고민을 덜며  모바일 버전 ui 작성의 용이하다는 점에서 선택했어요.
- `netlify` : Github 와 연동, https를 기본적으로 지원, 복잡한 구축 과정을 Netilfy에게 위임하여 배포했어요.

<br/>

## 🌠 이슈

- 번들 파일 사이즈, 초기 로딩시간 감소를 위해  `React.lazy` 를 통해 필요할 때만 분리한 정크 파일을 로드하도록 했어요.
- 비동기 데이터 처리를 효과적으로 다루기 위해 `Redux-Saga` 와 `React` 의 CustomHooks를 이용하여 action에 따른 로딩, 결과, 에러 상태를 관리하도록 했어요.

<br/>

# 백엔드

## 🤙 코딩 컨벤션

패키지명, 클래스명은 일반적인 관례대로 작성했어요.

일반적인 변수는 camelCase 방식으로 작성했고, Enum이나 정적상수는 SNAKE_CASE 방식으로 작성했어요.

API 구현시 최대한 RESTfull 하게 하려고 노력했어요.

## 🖥 서버환경

OS : AWS EC2 - Amazon Linux 2

DB : MariaDB 10.5.16 for Linux

Language : Java - openjdk 11.0.13 2021-10-19 LTS

Frameworks : Spring core 5.3.16, Spring Boot 2.6.4

## ⌨️ 협업 방식

깃허브를 통해 API 문서를 제공했어요.

Notion, Discord 를 통해 비대면으로 협업을 진행했어요.

## ⚡ 기술 스택

Spring Framework : 객체지향 프로그래밍으로 주어진 비즈니스 로직 구현에 집중할 수 있도록 Spring Framework를 사용했어요.

Spring Boot : Spring Framework의 단점인 복잡한 의존성 설정을 자동으로 해줌으로써 생산성을 높여주는 Spring Boot를 사용했어요.

## 🛠 이슈

1. 트랜젝션 설정 적용 안됨
    - 몇몇 기능의 경우 보다 작은 기능의 조합으로 이루어지는데, 각각의 작은 기능에서 어떤 오류가 발생한 경우 모든 작은 기능들이 실행되기 이전으로 상태를 되돌려야 합니다. 이를 위해 스프링에선 @`Transactional` 어노테이션을 제공합니다. 그러나, 이 설정이 제대로 적용되지 않는 현상이 있었습니다.
    - 해당 어노테이션이 적용된 메서드 내부에서 try-catch문이 동작하는 경우 트랜젝션 어노테이션이 제대로 동작하지 않는 경우가 있다는 정보를 찾았고, 이를 적용해 해결했습니다.
2. CORS 예외처리 설정 적용 안됨
    - 보안의 이유로 브라우저에서는 주 요청을 보내기 전에 예비 요청을 통해 CORS 검사를 하게 됩니다. 따라서, 프론트 어플리케이션이 동작하는 오리진과 서버(aws ec2)의 오리진이 달라 브라우저에서 아예 api 요청을 보내지 않고 에러를 발생시킵니다. 이를 해결하기 위해서는 백엔드에서 별도의 처리를 해주어야 하고, Spring 에선 `WebMvcConfigurer.addCorsMappings(CorsRegistry registry)` 메서드를 이요해 이 처리를 하게 됩니다. 그러나, 이 설정이 전혀 동작하지 않는 문제가 있었습니다.
    - 이 프로젝트에서 사용자의 인증,인가 작업을 처리하기 위해 Spring에서 제공하는 `Interceptor` 를 이용했습니다. 인터셉터를 통해 요청의 헤더에 포함되어 있는 인증 토큰을 추출하여 이를 이용해 사용자를 인증 하는 구조입니다. 
    - 그러나, 브라우저에서 CORS 검사를 위해 보내는 예비요청(Preflight Request)에는 당연히 인증토큰이 포함되지 않고, 인터셉터 내부에서 NPE(NullPointerException)이 발생하게됩니다.
    - 인터셉터에서의 예외발생의 경우 별도로 처리를 하지 않았으므로 스프링이 자체적으로 처리(아마도 500 에러)를 하게되고 이 과정에서 Preflight 요청에 제대로 응답이 넘어가지 않았다고 볼 수 있었습니다.
    - 따라서 이를 해결하기 위해 인터셉터에서 Preflight 요청이 OPTIONS 메서드로 온다는 점을 이용해 별도로 인증 처리를 하지 않도록 하여 문제를 해결했습니다.
3. 복잡하고 반복된 코드가 많이 보이는 컨트롤러
    1. 개발 초기 진행 중의 컨트롤러 코드의 일부를 보면 
    
        ```java
        @PostMapping("/cert/{goalId:[0-9]+}")
        public ResponseEntity<Certification> addCertificationByGoalId(@PathVariable long goalId, @RequestBody Certification certification, @RequestHeader("Authorization") String token){
            String goalOwnerEmail = JwtBuilder.getEmailFromJwt(token);
            try {
                certService.addCert(certification, goalOwnerEmail);
                return ResponseEntity.ok(certService.getCertificationByGoalId(goalId).orElseThrow());
            }catch (PermissionException e){
                e.printStackTrace();
                return ResponseEntity.status(HttpStatus.UNAUTHORIZED).build();
            }catch (DuplicateCertificationException e){
                e.printStackTrace();
                return ResponseEntity.status(HttpStatus.CONFLICT).build();
            }catch (DataAccessException e){
                e.printStackTrace();
                return ResponseEntity.status(HttpStatus.CREATED).build();
            }
        }
        
        @PutMapping("/cert/success/{goalId:[0-9]+}")
        public ResponseEntity<?> successVerification(@PathVariable long goalId,@RequestHeader("Authorization") String token){
            String requestEmail = JwtBuilder.getEmailFromJwt(token);
            try{
                verfiService.success(goalId,requestEmail);
                return ResponseEntity.ok().build();
            }catch (DataAccessException e){
                return ResponseEntity.status(HttpStatus.INTERNAL_SERVER_ERROR).build();
            }catch (PermissionException e){
                return ResponseEntity.status(HttpStatus.UNAUTHORIZED).body(e.getMessage());
            }
        }
        ```
        
        중복된 예외 처리 코드가 많이 보입니다. 이를 해결하기 위해 스프링에서 제공하는 `ExceptionHandler` 를 이용했습니다. 아래는 이를 이용해 예외처리를 `SpringHandleExceptionHandler` 라는 클래스로 이관한 모습입니다.
    
        `SpringHandleExceptionHandler`
        
        ```java
        @RestControllerAdvice
        public class SpringHandleExceptionHandler {
        
            @ExceptionHandler(SpringHandledException.class)
            public ResponseEntity<?> handle(SpringHandledException exception){
                exception.printStackTrace();
                return exception.parseResponseEntity();
            }
        }
        ```
        
        GoalController 일부
        
        ```java
        @PostMapping("/cert/{goalId:[0-9]+}")
        public ResponseEntity<Certification> addCertificationByGoalId(@PathVariable long goalId, @RequestBody Certification certification, @RequestHeader("Authorization") String token){
            String goalOwnerEmail = JwtBuilder.getEmailFromJwt(token);
            try {
                certService.addCert(certification, goalOwnerEmail);
                return ResponseEntity.ok(certService.getCertificationByGoalId(goalId));
            }catch (DataAccessException e){
                e.printStackTrace();
                return ResponseEntity.status(HttpStatus.CREATED).build();
            }
        }
        
        @PutMapping("/cert/success/{goalId:[0-9]+}")
        public ResponseEntity<?> successVerification(@PathVariable long goalId,@RequestHeader("Authorization") String token){
            String requestEmail = JwtBuilder.getEmailFromJwt(token);
            try{
                verfiService.success(goalId,requestEmail);
                return ResponseEntity.ok().build();
            }catch (DataAccessException e){
                return ResponseEntity.status(HttpStatus.INTERNAL_SERVER_ERROR).build();
            }
        }
        ```
    

## 앞으로 개선할만한 것들
### 개발 속도를 위해 타협한 더티코드 정리
이번 프로젝트에는 백엔드 개발자 1명, 프론트엔드 개발자 3명이 참여했습니다. 따라서 넘처나는 수정요청과 기능추가 요청을 혼자 처리하다보니, 지금 작성중인 코드가 나중에 문제가 될 수 있음을 알면서도 넘어간 부분이 더러 있습니다. 그런 부분을 하나씩 천천히 수정해나갈 예정입니다.
- 이미지 저장 코드의 메서드 분리
    ```java
    public Announcement addAnnouncement(Announcement announcement) {
            String image = announcement.getImage();
            try {
                byte[] imageData = java.util.Base64.getDecoder().decode(image.substring(image.indexOf(",") + 1));
                String filenameExtension  = image.split(",")[0].split("/")[1].split(";")[0];
                String fileName = "announcement"+File.separator+announcement.getAnnouncementId();
                File imageFile = new File(fileName);
                BufferedImage bufferedImage = ImageIO.read(new ByteArrayInputStream(imageData));
                ImageIO.write(bufferedImage,filenameExtension,imageFile);
                announcement.setImage(fileName);
                String banner = announcement.getBannerImage();
                announcement.setBannerImage("announcement"+File.separator+"banner"+announcement.getAnnouncementId());
                long announcementId = adminRepository.insertAnnouncement(announcement);
                announcement.setBannerImage(banner);
                announcement.setAnnouncementId(announcementId);
                announcement.setDate(Timestamp.valueOf(LocalDateTime.now()));
                fileName = "announcement"+File.separator+announcement.getAnnouncementId();
                imageFile.renameTo(new File(fileName));
                System.out.println(fileName);
                announcement.setImage("");
                saveBannerImage(announcement);
                return announcement;
            }catch (IllegalArgumentException e){
                throw new SpringHandledException(HttpStatus.BAD_REQUEST,ErrorCode.UNKNOWN,"POST /api/admin/announcement","DataURI 이미지가 아닙니다.");
            } catch (IOException e) {
                throw new SpringHandledException(HttpStatus.BAD_REQUEST,ErrorCode.UNKNOWN,"POST /api/admin/announcement","DataURI 를 파일로 바꿀 수 없습니다.");
            }
        }
    ```
    딱 봐도 읽기 어려운 코드입니다. 이런 코드들이 프로젝트 구석구석에 존재합니다. 이런 코드를 수정할 예정입니다.
