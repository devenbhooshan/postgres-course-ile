# Postgres Course ILE
Interactive Learning Environment(ILE) for the PostgreSQL course. Sign-up [here](https://devenbhooshan.ck.page/e41b961998)

## Steps to setup the ILE

- clone this repo `git clone git@github.com:devenbhooshan/postgres-course-ile.git`
- run `cd postgres-course-ile`
- run `docker-compose down`
- run `docker-compose up`
- open `http://localhost:7681/`
- enjoy  :)

### Note
if you are facing `ride_hailing_week_2 does not exist` issue, do the following 
- run `docker rmi devenbhooshan/postgres-course-db:week-2 --force` to remove the image with the bug
- run `docker-compose up` again


![](ile.png)
