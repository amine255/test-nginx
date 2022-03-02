# Minou's first NGINX

- Docker build: 
    - replace `<tag>` with the correct tag, example test_amine:1
    - command: `docker build -t test_nginx:<tag> .`

- Docker run: 
    - replace `<tag>` with the correct tag, example test_amine:1
    - replace `<test_number>` with the test_number - example testAmine1
    - command: `docker run --name testnginx<test_number> -p 8080:443 test_nginx:<tag>`

- Check on the URL: <http://localhost:8080/>
