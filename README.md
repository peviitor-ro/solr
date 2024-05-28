# solr LOCAL environment (DEV environment)

## Windows OS

1. deschide
[GitHUB Desktop](https://desktop.github.com/)
2. clonezi **peviitor-ro\solr** in folderul **c:\solrdata**

3. deschide
[Docker Desktop](https://www.docker.com/products/docker-desktop/)

`cmd`
```
 docker run -p 8983:8983 -v c:\solrdata\solr\core:/var/solr sebiboga/peviitor:1.0.0
```
4. deschide Chrome browser
5. [http://localhost:8983/](http://localhost:8983/)

   ![image](https://github.com/peviitor-ro/solr/assets/41440889/88af14d4-7906-4178-8f80-f601f8d44207)


# solr QA environment (QA environment)
[http://zimbor.go.ro:8985/](http://zimbor.go.ro:8985/)