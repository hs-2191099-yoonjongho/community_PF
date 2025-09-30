# API 동작 캡처 및 예시

이 문서는 실제 API 동작 화면(캡처)과 주요 요청/응답 예시를 정리한 자료입니다. Swagger UI, Postman 테스트 결과, 주요 엔드포인트별 JSON 예시를 포함합니다.

---

## 1. Swagger UI 캡처

![Swagger UI](API/swagger.PNG)
- 전체 API 명세 및 테스트 가능
- JWT 인증, 게시글/댓글/회원 등 모든 엔드포인트 확인 가능

---

## 2. 회원가입/로그인/로그아웃

### 회원가입 성공
![회원가입 성공](API/signup_success.PNG)

### 회원가입 실패(중복)
![회원가입 실패](API/signup_fail.PNG)

### 로그인 성공
![로그인 성공](API/login_success.PNG)

### 로그인 실패
![로그인 실패](API/login_fail.PNG)

### 로그아웃 성공
![로그아웃 성공](API/logout_success.PNG)

---

## 3. 게시글/댓글

### 게시글 작성 (이미지 포함)
![게시글 작성 (이미지 포함)](API/post_create_with_image.PNG)

### 게시글 검색
![게시글 검색(최소 추천수, 검색어)](API/post_search_min_likes_keyword.PNG)

### 게시글 상세 조회
![게시글 상세 조회](API/view_post_details.PNG)

### 게시글 수정 (성공/실패)
게시글 수정 성공: ![게시글 수정 성공](API/post_update_success.PNG)
게시글 수정 실패(권한): ![게시글 수정 실패](API/post_update_fail_permission.PNG)

### 댓글 작성
![댓글 작성](API/comment_create.PNG)

---

## 4. 파일 업로드/보안

### 이미지 업로드 성공
![이미지 업로드 성공](API/image_upload_success.PNG)

### 이미지 업로드 실패
![이미지 업로드 실패](API/image_upload_fail.PNG)

---

## 5. 좋아요/추천

### 게시글 좋아요
![게시글 좋아요](API/like.PNG)

---

## 6. 토큰/인증

### 토큰 재발급 성공
![토큰 재발급 성공](API/token_refresh_success.PNG)

### 토큰 재발급 실패(로그아웃)
![토큰 재발급 실패](API/token_refresh_fail.PNG)

---

## 7. AWS

### 회원가입 성공
![AWS 회원가입](API/signup_aws.PNG)

### 로그인 성공
![AWS 로그인](API/login_aws.PNG)

### 게시글 작성
![AWS 게시글 작성](API/post_create_aws.PNG)


---

