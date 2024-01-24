# Restaurant-Management-Website
This website allows customers to make table reservations, view the menu, and Staff members to manage reservations, take orders, maintain menu and kitchen orders and view restaurant analysis. Payment by Cash or Card with Bill Receipt.
Customers can register and log in to the website, browse the restaurant's menu, and reserve a table based on real-time availability. Staff members can manage reservations, orders, and the restaurant's menu through an online portal with access control. 

**Using:** XAMPP and NetBeans

**Features:**
* **Customer Side (customerSide Folder):** Stores the website and allows customers to:
    * Make reservations
    * Register for accounts
    * View profile points
* **Staff Side (adminSide Folder):** Stores the panels and allows staff to:
    * Take orders
    * Send orders to the kitchen
    * Process payments
    * Print receipts
    * Manage CRUD operations
    * View user preferences
    * Download reports
    * View charts and graph


**Steps to run the project:**

1. Open XAMPP, start Apache and MySQL.
2. Create a new project named `RestaurantProject`.
3. Delete the `index.php` file.
4. Copy all the folders and files in `MiniProject` (adminSide, customerSide, index.php, and restaurantDB.txt) into the `Source Files` directory.
5. Make sure there is no database named `restaurantdb`.
6. Run the project.

## Example accounts

| Role | Email | Password |
|---|---|---|
| Customer | dadsvawvid@gmail.com | david4pass |
| Customer | zoe@gmail.com | passworddef |
| Customer | jackie@gmail.com | passwordstu |
| Staff | 1 | password123 |
| Staff | 10 | davidpa2ss |
| Staff | 7 | robertpass |
| Admin | 99999 | 12345 |

