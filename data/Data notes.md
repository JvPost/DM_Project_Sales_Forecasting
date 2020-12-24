## Features sales_train
### Additional description
- date_block_num = months since start measuring => m_1 = January 2013, m_2 = Febuari 2013, etc
    - Meaning m_1 % 12 = the month of the year


### Potential new features
- day: d_0: sunday, d_1: monday , .. , d_6: saturday


### Useless features
- item_price: since item_price is simply property of item which is represented by item_id
    - Debatable: because prices may vary per date_block, store etc.


### Ideas
- Can cluster shops based on the items they sell.