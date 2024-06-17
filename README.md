# solr LOCAL environment (DEV environment)

## Windows OS


# solr LOCAL  environment (DEV environment)
## run this command if not yet run previously
`cmd`
```
docker network create --subnet=172.18.0.0/16 mynetwork
```


1. deschide
[GitHUB Desktop](https://desktop.github.com/)
2. clonezi **peviitor-ro\solr** in folderul **c:\solrdata**

3. deschide
[Docker Desktop](https://www.docker.com/products/docker-desktop/)

`cmd`
```
docker run --name solr-container --network mynetwork --ip 172.18.0.10 -d -p 8983:8983 -v c:\solrdata\solr\core:/var/solr sebiboga/peviitor:1.0.0
```
4. deschide Chrome browser
5. [http://localhost:8983/](http://localhost:8983/)

   ![image](https://github.com/peviitor-ro/solr/assets/41440889/88af14d4-7906-4178-8f80-f601f8d44207)



## using _config
1. double click on run.bat from **_config** folder

# solr QA environment (QA environment)
[http://zimbor.go.ro:8985/](http://zimbor.go.ro:8985/)


