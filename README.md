<br/>
<p align="center">
  <a href="https://github.com/erkutkoral/Rule-Based_Classification">
    <img src="https://buildfire.com/wp-content/uploads/2017/10/ios-vs-android-users.jpg" alt="Logo" width="400" height="400">
  </a>

  <h3 align="center">Rule-Based Classification Project</h3>

  <p align="center">
    Calculating Potential Customer Return with Rule-Based Classification
    <br/>
    <br/>
    <a href="https://github.com/erkutkoral/Rule-Based_Classification"><strong>Explore the docs »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/erkutkoral/Rule-Based_Classification/issues">Report Bug</a>
    .
    <a href="https://github.com/erkutkoral/Rule-Based_Classification/issues">Request Feature</a>
  </p>
</p>

![Contributors](https://img.shields.io/github/contributors/erkutkoral/Rule-Based_Classification?color=dark-green) ![Issues](https://img.shields.io/github/issues/erkutkoral/Rule-Based_Classification) 

## Table Of Contents

* [About the Project](#about-the-project)
* [Technologies-Libraries-Frameworks](#technologies-libraries-frameworks)
* [Roadmap](#roadmap)
* [Authors](#authors)

## About The Project

- The aim is to create level-based customer definitions by using some features in the history of a game company and to create segments according to these new customer definitions and to estimate how much new development information can be brought to the company on acerage according to these segments.

For example:
It is desired to determine how much money a 25-year-old male user from Turkey can earn on average.

- Persona.csv data set contains the prices of the products sold by an international gaming company and some demographic information of the users who purchased these products. The data set consists of records created in each sales transaction. This means the table is not deduplicated. In other words, a user with certain demographic characteristics may have made more than one purchase.

- Dataset:
  - PRICE: customer's spending amount
  - SOURCE: customer's connected device
  - SEX: customer's gender
  - COUNTRY: customer's country
  - AGE: customer's age  
## Technologies-Libraries-Frameworks

Python Pandas Methods

## Roadmap

1. Dataset understanding
  - Revealed questions:
  - How many unique "Source"s are there? What are their frequencies?
  - How many unique "Price"s are there?
  - How many sales were made from which PRICE?
  - How many sales were made from which country?
  - How much was earned from sales in total by country?
  - What are the sales number by Source types?
  - What are the Price averages by country?
  - What are the averages of money spent according to sources?
  - What are the PRICE averages in the COUNTRY-SOURCE breakdown?
2. Separating the AGE variable into ranges by making it categorical
3. Creating new column called "CUSTOMER_LEVEL_BASED" with other variables.
4. Creating new segments in column called "SEGMENTS"
5. Trying new segments with new user personas.

## Authors

* **Erkut Koral** - *Industrial Engineer Student* - [LınkedIn](https://www.linkedin.com/in/erkutkoral/)
