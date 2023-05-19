"# sist2_compose" 
sist2: https://github.com/simon987/sist2

demo of sist2: [https://sist2.simon987.net/](https://sist2.simon987.net/)

additional conf of sist2: https://github.com/simon987/sist2/blob/master/docs/USAGE.md

```
1. Clone start.bat and docker-compose.yml to any folder e.g. ~\sist2
2. Install Docker on Windows, make sure Docker is running and ready
3. Run start.bat to make folders and launch Docker Composer
4. Place files in folder sist2\documents, which you want to index
5. Sist2 from Docker will index files, store intex at sist2\my_index, sends idx to elasticsearch
6. Sist2 will run web interface at http:\\localhost:8888 serving UI and your files
7. If someting fails (indexing or sending the index) just restart the indivdual container in Docker to repeat a step
8. or just run start.bat again until it works :)

Tip: In UI go settings -> Highlight context size in characters - to increase lenght of text preview
```