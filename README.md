# MongoDB_Introduction
[link to the slides](https://docs.google.com/presentation/d/1zRyLCZAO7tDEYwlMTC7tU8O9K7Fws4GpwwNrG2lphQo/edit)
- Create your own branch
- Run the practice_mongodb.ipynb with jupyter-notebook or google colab or any software that read .ipynb file
- Create a project with some constraints listed in the python notebook file
- Connect your cloud database to mongodb compass and import the restaurants.json to your database
- Each of the exercises has 2 cells:
    + Write your query in pymongo and run in the FIRST cell
    + Don't run the SECOND cell because it contains the results for you to compare with your results
- Ask me any question if you have difficulties
- Good luck and use MongoDB

# MongoDB a little bit intermidiate
[link to the slides](https://docs.google.com/presentation/d/1H8vDbZGVxHH_kP9TYe-ZQDcl2RVftSQgeA8YPAbBnVs/edit?usp=sharing)
- Create a pagination function:
    - Input: db cursor, offset, size
    - Output:
` return {
    data: data,\\
    next_url: "?offset={offset}&size={size}",
    previous_url : "?offset={offset}&size={size}"}
`
