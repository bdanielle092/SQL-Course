# Carnival Dealerships

1. Because Carnival is a single company, we want to ensure that there is consistency in the data provided to the user. Each dealership has it's own website but we want to make sure the website URL are consistent and easy to remember. Therefore, any time a new dealership is added or an existing dealership is updated, we want to ensure that the website URL has the following format: `http://www.carnivalcars.com/{name of the dealership with underscores separating words}`.

1. If a phone number is not provided for a new dealership, set the phone number to the default customer care number `777-111-0305`.

1. For accounting purposes, the name of the state needs to be part of the dealership's tax id. For example, if the tax id provided is `bv-832-2h-se8w` for a dealership in Virginia, then it needs to be put into the database as `bv-832-2h-se8w--virginia`.
