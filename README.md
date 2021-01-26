This first example just shows the basic configuration of a single job with three steps.

You will need a database to run the application:

`
docker build -t mysqldb . && docker run -d -p 3306:3306 mysqldb
`