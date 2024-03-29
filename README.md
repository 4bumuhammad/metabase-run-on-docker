# Running Metabase on Docker



#### Reference : 

    https://www.metabase.com/

---

#### Open Source quick start

Use this quick start to run the Open Source version of Metabase locally. See below for instructions on running Metabase in production.


    ❯ docker pull metabase/metabase:latest


    ❯ docker run -d -p 3000:3000 --name metabase metabase/metabase


    ❯ docker images

        REPOSITORY          TAG       IMAGE ID       CREATED      SIZE
        metabase/metabase   latest    bdeac1f0574b   4 days ago   637MB

    ❯ docker ps -a

        CONTAINER ID   IMAGE               COMMAND                  CREATED         STATUS         PORTS                    NAMES
        103b81d86cc9   metabase/metabase   "/app/run_metabase.sh"   4 seconds ago   Up 4 seconds   0.0.0.0:3000->3000/tcp   metabase



### Open Browser

    http://localhost:3000/setup



### Application

<p align="center">
    <img src="./ss_001_metabase.png" alt="ss_metabase" style="display: block; margin: 0 auto;">
</p>

<p align="center">
    <img src="./ss_002_metabase.png" alt="ss_metabase" style="display: block; margin: 0 auto;">
</p>

<p align="center">
    <img src="./ss_003_metabase.png" alt="ss_metabase" style="display: block; margin: 0 auto;">
</p>

<p align="center">
    <img src="./ss_004_metabase.png" alt="ss_metabase" style="display: block; margin: 0 auto;">
</p>

<p align="center">
    <img src="./ss_005_metabase.png" alt="ss_metabase" style="display: block; margin: 0 auto;">
</p>

<p align="center">
    <img src="./ss_006_metabase.png" alt="ss_metabase" style="display: block; margin: 0 auto;">
</p>

<p align="center">
    <img src="./ss_007_metabase.png" alt="ss_metabase" style="display: block; margin: 0 auto;">
</p>

<p align="center">
    <img src="./ss_008_metabase.png" alt="ss_metabase" style="display: block; margin: 0 auto;">
</p>




---

exposure and application by Dhony Abu Muhammad
