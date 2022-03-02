# Minou's first NGINX

- Docker build: 
    - replace `<tag>` with the correct tag, example test_amine:1
    - command: `docker build -t test_amine:<tag> .`

- Docker run: 
    - replace `<tag>` with the correct tag, example test_amine:1
    - replace `<test_number>` with the test_number - example testAmine1
    - command: `docker run --name testAmine<test_number> -p 8080:443 test_amine:<tag>`

- Check on the URL: <http://localhost:8080/>
