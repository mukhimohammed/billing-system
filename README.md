
## Usage

1. Access the application at `http://localhost:8000`

2. Navigate through the main sections:
   - Customers: `/customers`
   - Products: `/products`
   - Bills: `/bills`

3. Creating a Bill:
   - Click "Create Bill"
   - Select a customer
   - Add products and quantities
   - Submit to create the bill

4. Managing Bills:
   - View all bills on the bills index page
   - Click "View" to see bill details
   - Mark bills as paid
   - Delete unpaid bills

## Database Structure

1. Customers
   - id
   - name
   - email
   - phone
   - address
   - timestamps

2. Products
   - id
   - name
   - description
   - price
   - stock
   - timestamps

3. Bills
   - id
   - customer_id
   - total_amount
   - status
   - timestamps

4. Bill Items
   - id
   - bill_id
   - product_id
   - quantity
   - price
   - subtotal
   - timestamps
