<h1 align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com/?lines=This+Project;Made+By+Athoillah+😊;Automated+Ingestion;Datawarehouse;Using+Python✨&center=true&size=30">
  </a>
</h1>

<hr>

<h2 align="center">Datawarehouse Automating</h2>

<p align="justify"> The purpose of this project is to answer <code><a href="https://github.com/Athoillah21/Project-3-Data-Warehouse-Automating/blob/main/questions/questions2a.txt">question 2a</a></code>. I answered the question using the python programming language.</p> 

## Step 1 : Unload .json file become a standard PostgreSQL DDL command

<p align="justify"> Define the database column of the given <code><a href="https://github.com/Athoillah21/Project-3-Data-Warehouse-Automating/blob/main/sql/schemas/user_address.json">json file</a></code>. Here I use the following workflow, the json data that has been given is loaded, then the format is converted into a list and then converted into a tuple so that it resembles a DDL command in general in PostgreSQL. </p>

## Step 2 : Establishing a connection with PostgreSQL

<p align="justify"> Using psycopg2 module to make connection with local postgreSQL. Before that, create a new database on localhost according to the name commanded.  </p>


## Step 3 : Load dataset to PandasDataframe before inserting into Database

<p align="justify"> Use the zipfile module to extract the <code><a href="https://github.com/Athoillah21/Project-3-Data-Warehouse-Automating/blob/main/temp/dataset-small.zip">dataset</a></code> and then convert it to pandas dataframe form. Perform commands in the problem, such as filtering data by date. </p>

## Step 4 : Create engine and insert dataframe into PostgreSQL Database

<p align="justify"> Using sqlalchemy module create engine that connect code written in python with defined postgresql connections. Along with what code will be executed. In this case, the code inserts data into the database. advantage of using python, i.e. code can be reused. </p>
