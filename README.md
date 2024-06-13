# Admin Dashboard
관리자 권한을 가진 관리자만 접근이 가능한 관리자 페이지를 구현한 회원 관리 프로젝트입니다.

# 프로젝트 시연 영상
[![Video Label](http://img.youtube.com/vi/Bs_LhABboCw/0.jpg)](https://youtu.be/Bs_LhABboCw)

# 관리자 기능
### 1. 회원 등록 화면
![image](https://github.com/dnslfkrh/portfolio-adminDashboard/assets/140808035/c26593bc-0e4e-42e5-acea-17cfe8a05e1f)

### 2. 회원 수정 화면
![image](https://github.com/dnslfkrh/portfolio-adminDashboard/assets/140808035/ea7c20b8-b1a5-4fca-9607-5efd08c23243)

### 3. 회원 삭제 화면
![image](https://github.com/dnslfkrh/portfolio-adminDashboard/assets/140808035/5fec69dc-d17b-42e4-b40e-de6f07bfa7b1)

# Directory Tree
```
portfolio-adminDashboard
├─ app.js
├─ public
│  ├─ css
│  │  ├─ admin.css
│  │  ├─ login.css
│  │  └─ myPage.css
│  ├─ html
│  │  ├─ admin.html
│  │  ├─ login.html
│  │  └─ myPage.html
│  └─ js
│     ├─ admin.js
│     ├─ login.js
│     └─ myPage.js
└─ server
   ├─ config
   │  └─ db.js
   ├─ controllers
   │  ├─ admin
   │  │  ├─ addUser.js
   │  │  ├─ deleteUser.js
   │  │  ├─ editUser.js
   │  │  └─ userList.js
   │  ├─ login
   │  │  ├─ authorize
   │  │  │  ├─ authLog.js
   │  │  │  └─ authNum.js
   │  │  ├─ db
   │  │  │  ├─ authLog.js
   │  │  │  └─ userCheck.js
   │  │  └─ jwt
   │  │     ├─ adminVerify.js
   │  │     └─ jwt.js
   │  └─ user
   │     ├─ findMe.js
   │     └─ myToken.js
   ├─ models
   │  ├─ authLogModel.js
   │  └─ userModel.js
   └─ routes
      ├─ admin.js
      ├─ login.js
      └─ user.js

```