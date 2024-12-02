# **Magento 2 Order Tracking Extension**

Tracking orders efficiently is a critical aspect of any eCommerce business. The **Magento 2 Order Tracking** extension simplifies the process by enabling customers to track their orders effortlessly without logging in, improving user experience and building trust.

## **How It Works**

The Magento 2 Order Tracking extension allows customers to check their order status using only their email address and order ID. It eliminates the need for customers to log into their accounts, making order tracking quick and hassle-free. Once customers enter their details, the extension fetches real-time order information from the Magento backend, ensuring accurate and up-to-date data.

## **Key Features**

* Customers can track orders without logging into an account.  
* Only verified email addresses and order IDs can access tracking details.  
* Displays the latest status updates for customer orders.

## **Easy-to-Use Interface**

The extension is designed with simplicity in mind, offering an intuitive interface where users can effortlessly input their email and order ID to track their orders. It is easily accessible directly from the storefront and is fully compatible with both desktop and mobile devices, ensuring a seamless experience across all platforms.

## **Order Status Details**

Customers receive detailed information about their orders, including the current status (e.g., processing, shipped, delivered), the shipping method with tracking numbers (if available) and the estimated delivery date, ensuring complete transparency and convenience.

## **Integration with Shipping Providers**

The extension seamlessly integrates with popular shipping carriers, automatically fetching tracking information from providers and supporting multiple carriers to offer customers flexible and direct shipment tracking from the Magento store.

## **Customizable Design**

Admins have the flexibility to customize the order tracking page to align with their website's branding, including editing text, colors, layout and adding the company logo for a professional, cohesive look.

## **Enhanced Security**

Data privacy is a priority. The extension ensures sensitive order information is protected by verifying user credentials before displaying details.

## **Extension Installation**

To install the **Magento 2 Order Tracking** extension:

### **Step 1:** 

Unzip the folder and upload the extension to the root directory of your Magento 2 installation using FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure Magento 2 Order Tracking**

### **Step 1: Manage Tracking Carriers**

![manage tracking carrier](https://github.com/user-attachments/assets/dd6b60b8-0b5f-419a-8c5a-ca51f81a7d62)

Before configuring the extension, add tracking carriers via the **Reports \> Manage Tracking Carriers** grid. Here, you'll find a list of all the carriers that have been added and saved.

### **Step 2: Add New Tracker**

By clicking the "Add New Tracker" button in the Manage Tracking Carriers grid, the admin can add a new carrier tracker.

![add_new_tracker](https://github.com/user-attachments/assets/9605023b-ecd4-45f3-928d-c721bb351014)

* **Tracker Title**: Enter a custom title for the tracker being added.  
* **Tracking URL**: Provide the tracking URL and use custom variables to create the URL.  
* **Status**: Enable the custom carrier tracker to make it visible in the "Select Tracker" dropdown.

### **Step 3: Configure Settings**

To configure the extension, log in to Magento 2, navigate to **Stores \> Configuration \> Meetanshi \> Order Tracking**, where you can find various settings to enable the extension.

![configuration](https://github.com/user-attachments/assets/67bf320b-3854-449b-b1ef-d05d6a87450a)

* **Order Tracking**: Enable the order tracking extension here.  
* **Add Order Tracking Link in Top Link**: Set to “YES” to display the order tracking link in the Top Link section.  
* **Add Order Tracking Link in Top Menu**: Set to “YES” to show the order tracking link in the Top Menu.  
* **Send Order Tracking Link in Email**: Set to “YES” to include the order tracking link in the order confirmation email.  
* **Custom Validation Message**: Set a custom validation message for unavailable order tracking information.

### **Step 4: Manage Custom Carrier Trackers**

The extension allows you to add up to 10 custom carrier trackers during shipment generation, enabling customers to track orders from the frontend.

![custome_carrier_tracker](https://github.com/user-attachments/assets/7837c0d6-c7c1-4f1c-82c9-2e1686ee8e51)

**Custom Carrier Tracker 1**: The extension supports the addition of up to 10 custom carrier trackers.

* **Enable**: Set to "YES" to activate the custom carrier tracker.  
* **Tracker Title**: Enter a title for the tracker.  
* **Select Tracker**: Choose from the custom carrier trackers you’ve added in the **Manage**  
  **Tracking Carriers** grid. Select the appropriate tracker and save the configuration. You can add up to 10 custom carrier trackers.

### **Step 5: Check Shipment Generation from Backend**

![new shipment](https://github.com/user-attachments/assets/ceded4ab-f655-48fc-85c6-2a0dc93ffe37)

To enable customers to track shipments and view order status from the frontend, the admin selects the shipping carrier, enters a title and adds the tracking number during shipment generation.

### **Step 6: Order Tracking from Frontend**

![order tracking](https://github.com/user-attachments/assets/c58c6919-4fe2-440f-bcf8-9ca598be9a6d)

After successfully configuring the extension, the "Track Your Order" link will appear in both the top link and top menu sections. Customers can enter their order ID and registered email in the Order Tracking section and click the "Track Order" button to view order and shipment details, including the tracking number and shipping method. Customers can also click the tracking number to access detailed order tracking information.

* **Custom Validation Message**

![order_tracking](https://github.com/user-attachments/assets/90e6c43f-0796-42bb-b9d6-f326287c4df2)

If a customer enters an invalid order ID or email, a message indicating order unavailability will be displayed, as specified in the custom validation message settings in the extension configuration.

### **Step 7: Order Tracking Link in Email**

![order tracking link in email](https://github.com/user-attachments/assets/687e024a-300e-4bbe-aed3-197482cb45dd)

If enabled in the configuration, the extension includes an order tracking link in the order confirmation email sent to customers. Customers can click the link to track their order.

## Download our [Magento 2 Order Tracking](https://meetanshi.com/magento-2-order-tracking.html) Extension
