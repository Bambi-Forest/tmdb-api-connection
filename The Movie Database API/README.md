<div align="center" id="top"> 
 <!-- <img src="" alt="The Movie Database API Analysis" /> -->

  &#xa0;


</div>

<h1 align="center">The Movie Database API Analysis</h1>


<h4 align="center">Status</h4>

<h4 align="center"> 
	🚧  The Movie Database API Analysis 🚀 Under construction...  🚧
</h4> 

<hr> 

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
</p>

<br>

## About ##

The Movie Database API – 
Objective: Use this API to analyze the top 5 movies, by genre, starring any of the top 10 paid actresses or the top 10 paid actors in the US.​

## Key Features ##

- Programming Language: Python
- Masking API Key with environment variables
- Establishing connection with The Movie Database API
- Importing CSV file
- Unnesting JSON columns
- Converting Json file to Dataframe using Pandas package
- Export Dataframe to CSV file
- Export CSV File to Azure Storage
- List Blobs in container

## Technologies ##

The following tools were used in this project:

- [Python](https://www.python.org/)
- [The Movie Database API](https://www.themoviedb.org/)
- [Azure Storage](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction)
- [Top Paid US Actors Info](https://www.statista.com/statistics/655480/all-time-top-grossing-actors-box-office/#:~:text=As%20of%20February%202023%2C%20Samuel,5.72%20billion%20U.S.%20dollars%20domestically.)
- [How to Use Environment Variables](https://www.youtube.com/watch?v=YdgIWTYQ69A)


## Requirements ##

Before starting, you need to have [Git](https://git-scm.com) installed.

## Getting Started ##

```bash
# Clone this project
$ git clone https://github.com/Bambi-Forest/tmdb-api-connection

# Access
$ cd tmdb-api-connection

# Install dependencies
$ pip install python-dotenv
$ pip install azure-storage-blob azure.identity azure.keyvault sqlalchemy pyodbc

# Run the project
$ yarn start

# The server will initialize in the <http://localhost:3000>
```

&#xa0;

<a href="#top">Back to top</a>
