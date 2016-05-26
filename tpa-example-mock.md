FORMAT: 1A

# Spending categories

Display the categories and the amount spent in them

[API Blueprint Example](https://help.apiary.io/api_101/api_blueprint_tutorial/)

## Spending categories Collection [/api/spending-categories]

### List categories and the amount spent in them [GET]

+ Response 200 (application/json)

        {
            "labels": [
                "Hypotheek",
                "Energie",
                "Verzekeringen",
                "Vervoer",
                "Ovirge"
            ]
            "data": [
                40, 
                15, 
                15, 
                15, 
                15
            ]
        }
