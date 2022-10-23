
### 1. Add item to cart

#### Preconditions

- Web page https://us.louisvuitton.com/eng-us/products/{someItem} is opened.

#### Test Steps

| ID                 | Test Step Description                            | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Click the _Place in Cart_                        | _Quality near cart +=1 and add to cart popup is appear_       |                                                                                                                                                                         

### 2. Delete item from cart

- Web page https://us.louisvuitton.com/eng-us/cart is opened (With selected item)

#### Test Steps

| ID                 | Test Step Description                            | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Click _Remove_                                   | _Popup with clarifying deliting item from cart_ is appeared                                                                                                                                                                                       
| 2                  | Click _Remove_                                   |  _Quality near cart -=1_ |                                                                                                                                                                                                    

### 3. Find t-shirt from searching line

- Web page https://us.louisvuitton.com/eng-us/homepage is opened

#### Test Steps

| ID                 | Test Step Description                            | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Write _T-shirt_ in searching line                | _Popup with all t-shirt_ is appeared      |                                                                                                                                                                             

### 4. Add item to wishlist

- Web page https://us.louisvuitton.com/eng-us/{someItem} is opened 

#### Test Steps

| ID                 | Test Step Description                            | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Click _White Hart with black border_                | _Orange circle near Wishlist_ is appeared _Popup with message "The item {item} has been added to your wishlist Access your wishlist"_  is appeared      | 

### 5. Delete item from wishlist

- Web page https://us.louisvuitton.com/eng-us/mylv/wishlist is opened 

#### Test Steps

| ID                 | Test Step Description                            | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Click _X_                | _Popup with clarifying deliting item from wishList_ is appeared     |   
| 2                  | Click _Remove_                | _Orange circle near wishList is_ desappeared   |   


### 6. Filter items with colors

- Web page https://us.louisvuitton.com/eng-us/homepage (with selected some category of items) is opened

#### Test Steps

| ID                 | Test Step Description                            | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  | Click on _Color_ in color palette                 | Displated all items with selected _Color_      |     

### 7. Searching with invalid text

- Web page https://us.louisvuitton.com/eng-us/homepage  is opened

#### Test Steps

| ID                 | Test Step Description                            | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  |   Fill searching line with text "ASDGASDGAS"      | _Message_: "NO RESULTS WERE FOUND FOR THE KEYWORD "ASDGASDGAS"
To improve your results, check your spelling or use a more general keyword".     |     

### 8. Calculating sum in cart

- Web page https://us.louisvuitton.com/eng-us/cart (with selected item)  is opened

#### Test Steps

| ID                 | Test Step Description                            | Expected Result                                                                                                                                                                                                                        |
| ------------------ | ------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1                  |   Change one itme to two items      | Total sum  is x2     |    
