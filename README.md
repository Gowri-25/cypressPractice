# cypressPractice
Cypress practice project 
# Cypress practice :

### 1. To run a single test :

   npx cypress run --spec "test.feature"
    

### 2. To run the whole test suite  :

      npx cypress run (headless mode)
      
       npx cypress run --headed (headed mode)

### 3. To run the test on a specific browser  :

   npx cypress run --headed --browser firefox

### 4. To run tests with tags :

    nnpx cypress run --headed -e TAGS="@smoke" --headed
    
### 5. To open the cypress test runner :
    
     node_modules/.bin/cypress open  

Reporting : 

### 6. To generate a mocawesome report: 

    node_modules/.bin/cypress run --reporter mochawesome
