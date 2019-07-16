# flask-sqlalchemy-rest
This is my first basic flask rest api app.

### Documentation
1. Get All Products
   Link: https://rico-basic-flask-rest.herokuapp.com/product
   
2. Get Single Product
   Link: https://rico-basic-flask-rest.herokuapp.com/product/<id>
   
3. Create Product
   - Link: https://rico-basic-flask-rest.herokuapp.com/product
   - Headers:
      - Key: Content-Type
      - Value: application/json
   - Body:
      - name (string, unique, max 100)
      - description (string, max 200)
      - price (float)
      - qty (integer)
      

      
