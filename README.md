# EDA - housing-market
Analysis of Seattle housing market and recommendations for buying a house for 'Thomas Hansen'

## Requirements

- pyenv
- python==3.11.3

## Setup

* setting the python version locally to 3.11.3
* creating a virtual environment using the `venv` module
* activate the newly created environment 
* upgrading `pip` (optionally)
* install the required packages via using the requirements.txt


    ```
### **`WindowsOS`** type the following commands :

    For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
  
    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```



#  Project  

##  Data

- King County Housing Data
- You will find the data in the eda schema of our database. You can access it via DBeaver. Please save the csv file in the data folder where it will not be uploaded to github.
- Please explore the dataset in DBeaver and come up with a Join for the 2 tables.
- The description of the column names can be found in the `column_names.md` file.
- The column names may NOT be clear at times:


## Task  


EDA/statistical analysis 

Recommend three options for Client X


## The clients


_Note:  these clients are made up (any resemblance to present people is absolutely random), make assumptions about answers they would give to your questions. (i.e. How do you define a rich neighborhood? Take the zipcodes with most houses in upper 10% percentile..). Whatever assumptions you make, please write them explicitly in your presentation and notebook._

| Name                | Client | Characteristics                                                                                                                                                                 |
| ------------------- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Thomas Hansen       | Buyer       | 5 kids, no money, wants nice (social) neighborhood, Timing?, Location?                                                                                                          |
| Charles Christensen | Seller      | Invest with big returns, wondering about renovation?, which Neighborhood? Timing?                                                                                               |
| Bonnie Brown        | Seller      | Has house and wants to move soon (timing?), but wants high profit in middle class NH (neighborhood)                                                                             |
| Larry Sanders       | Buyer       | Waterfront , limited budget, nice & isolated but central neighborhood without kids (but got some of his own, just doesn't want his kids to play with other kids .. because of germs) |
| Nicole Johnson      | Buyer       | Lively, central neighborhood, middle price range, right timing (within a year)                                                                                                  |
| Jennifer Montgomery | Buyer       | High budget, wants to show off, timing within a month, waterfront, renovated, high grades, resell within 1 year                                                                                  |
| Bonnie Williams     | Seller      | Has several houses, some in bad neighborhoods, willing to evict people, timing?, big returns, open for renovations                                                              |
| William Rodriguez   | Buyer       | 2 people, country (best timing & non-renovated) & city house (fast & central location), wants two houses                                                                        |
| Erin Robinson       | Buyer       | Invest in poor neighborhood, buying & selling, costs back + little profit, socially responsible                                                                                 |
| Jacob Phillips      | Buyer       | Unlimited Budget, 4+ bathrooms or smaller house nearby, big lot (tennis court & pool), golf, historic, no waterfront                                                            |
| Zachary Brooks      | Seller      | Invests in historical houses, best neighborhoods, high profits, best timing within a year, should renovate?                                                                     |
| Timothy Stevens     | Seller      | Owns expensive houses in the center, needs to get rid, best timing within a year, open for renovation when profits rise                                                         |
| Amy Williams        | Seller      | Mafiosi, sells several central houses(top10%) over time, needs average outskirt houses over time to hide from the FBI                                                   |

 
