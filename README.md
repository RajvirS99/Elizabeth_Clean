### STEPS TO USE THE BOILERPLATE

1. Use the command  in the your desired repository
```shopify theme init --clone-url GIT_REPO ```

2. After entering the command, define the project name `cd` into the project folder.
``` cd PROJECT_FOLDER ```

3. Login into the shopify store using the below command
``` shopify login --store STORE_LINK ```<br/>
**Accepted store links are -**
``` 
Store-prefix - johns-apparel
The myshopify.com url - johns-apparel.myshopify.com, https://johns-apparel.myshopify.com
The Store Admin URL - https://johns-apparel.myshopify.com/admin
The custom domain or custom domain admin - https://johnsapparel.com, https://johnsapparel.com/admin
```

4. Run the theme in the local server using 
``` shopify theme serve ```