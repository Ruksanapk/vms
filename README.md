# Vendor-Management-System
Vendor Management System is a web application developed using Django and Django REST Framework. It provides functionality for managing vendor profiles, tracking purchase orders, and calculating vendor performance metrics.
The following are the API endpoints:-
Vendor Profile Management:

● POST /api/vendors/: Create a new vendor.
● GET /api/vendors/: List all vendors.
● GET /api/vendors/{vendor_id}/: Retrieve a specific vendor's details.
● PUT /api/vendors/{vendor_id}/: Update a vendor's details.
● DELETE /api/vendors/{vendor_id}/: Delete a vendor.

Purchase Order Tracking:

● POST /api/purchase_orders/: Create a purchase order.
● GET /api/purchase_orders/: List all purchase orders with an option to filter by
vendor.
● GET /api/purchase_orders/{po_id}/: Retrieve details of a specific purchase order.
● PUT /api/purchase_orders/{po_id}/: Update a purchase order.
● DELETE /api/purchase_orders/{po_id}/: Delete a purchase order.

3. Vendor Performance Evaluation:

● GET /api/vendors/{vendor_id}/performance: Retrieve a vendor's performance
metrics.


To clone the repository "git clone https://github.com/your-username/vendor-management-system.git"
Apply migrations
Open your web browser and go to http://127.0.0.1:8000/ to access the API.
