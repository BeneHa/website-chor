# Chor webpage for blue vocals 

Webpage of the choire blue vocals which can be found  [here](https://www.blue-vocals.de).

**Starting container:**
docker build . -t chor
docker run -p 4000:4000 -v $(pwd):/site chor