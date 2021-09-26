# 원격 서버 사용하기

## 서버 연결 관련

1. `vscode > remote ssh` 설치 후 `remote explorer` tab으로 이동

1. 새로운 ssh target 설정

1. ssh key 저장 (putty key generator 이용)

1. `.ssh/config` 파일 저장

    ```text
    host [ANY_NAME]
        HostName [IP_ADDRESS]
        User [SERVER_USERNAME]
        IdentityFile [SSH_KEY_FILE_PATH]
    ```

1. `connect to host in New window` 버튼 클릭

1. ssh key 비밀번호 입력

1. git setting (`clone`, `user_emil`, `user_name`) 하기

1. `tmux` 설정

1. `yarn` 세팅 및 실행

    ```terminal
    npm install -g yarn
    yarn install
    yarn start
    ```

1. map 컴포넌트 에러 시 kakao api ip 설정 체크하기