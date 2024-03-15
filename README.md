# **Card Offer Tracker**

The Card Offer Tracker is a simple web application that helps bank cardholders discover exclusive discounts and offers from various lifestyle brands. It is built using HTML, Tailwind CSS, and JavaScript, and integrates with MongoDB Realm for data storage and retrieval. There are plans to make this application a Progressive Web App (PWA) in the future.

## **Features**

- **Merchant Search**: Users can search for offers by entering the merchant name in the search input field.
- **Merchant Dropdown**: If users are unsure of the merchant name, they can select it from a dropdown list populated with all available merchants.
- **Offer Display**: Matching offers are displayed in a list format, showing the merchant name, category, and offer details.
- **Responsive Design**: The application is designed to be responsive and accessible on various devices and screen sizes.

## **Installation**

To run the Card Offer Tracker locally, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/card-offer-tracker.git`
2. Navigate to the project directory: `cd card-offer-tracker`
3. Open the `index.html` file in a web browser.

Note: This application requires an active internet connection to fetch data from MongoDB Realm.

## **Usage**

1. Open the `index.html` file in a web browser.
2. To search for offers, enter the merchant name in the search input field and click the "Search" button.
3. If you're unsure of the merchant name, select it from the dropdown list labeled "If you are not sure select Merchant from here."
4. The matching offers will be displayed in the list below, showing the merchant name, category, and offer details.

## **Test Data**

A sample JSON file (`test-data.json`) is included in the repository for testing purposes. You can import this file into your MongoDB Realm database to populate it with sample offer data. Follow these steps:

1. Create a new MongoDB Realm app and a cluster.
2. In the Realm UI, go to the "Data" section and create a new database.
3. Create a new collection named "data" within the database.
4. Click on the "Collection" tab and then "Import File."
5. Select the `test-data.json` file from the project directory and click "Import."

After importing the test data, you should be able to see the offers in the application.

## **Dependencies**

This project utilizes the following third-party libraries and resources:

- [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework for rapid UI development.
- [Realm Web SDK](https://www.mongodb.com/docs/realm/web/): The MongoDB Realm Web SDK for integrating with MongoDB Realm databases.

## **Contributing**

Contributions to the Card Offer Tracker project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the [GitHub repository](https://github.com/your-username/card-offer-tracker).

## **License**

This project is licensed under the [MIT License](LICENSE).

## **Contact**

For any questions, suggestions, or inquiries, please contact the project maintainer at [Kaif21](https://www.linkedin.com/in/kaif-hossain/).