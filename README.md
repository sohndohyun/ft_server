# ft_server

docker를 통해 워드프레스 홈페이지를 간단하게 구축해보는 프로젝트입니다.

### 테스트 방법

```bash
docker build . -t ft_server
docker run -it -p80:80 -p443:443 ft_server
```

### sample image
![wordpress](./wordpress.png)
![phpmyadmin](./phpmyadmin.png)
