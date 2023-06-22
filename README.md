# Pharmacy Management System

The Pharmacy Management System is a C++ project that allows users to manage and track medicine orders in a pharmacy. It provides functionalities such as adding new orders, deleting orders, modifying existing orders, generating receipts, and maintaining a daily summary of total sales.

## Features

- **Take New Medicine Order**: Users can enter details for a new medicine order, including the receipt number, customer name, date, and the medicines they want to order. The system calculates the total amount to be paid for the order.

- **Delete Latest Medicine Order**: Users can delete the latest medicine order by providing the receipt number. The system removes the order from the records.

- **Modify Order List**: Users can modify an existing order by entering the receipt number. They can change the order details such as the receipt number, customer name, date, and the medicines they want to order. The system recalculates the total amount for the modified order.

- **Print Receipt and Make Payment**: Users can print the receipt for a specific order by entering the receipt number. The receipt includes the order details, such as the medicine type, medicine name, quantity, and total price. Users can enter the exact amount they want to pay.

- **Daily Summary of Total Sales**: Users can view a daily summary of all orders. The summary includes the receipt number, customer name, order date, order details, and the total bill for each order.

- **Exit**: Users can choose to exit the pharmacy management system.

## Usage

1. Compile and run the C++ project using an appropriate compiler.

2. Choose an option from the main menu based on the desired operation:
   - Option 1: Take a new medicine order.
   - Option 2: Delete the latest medicine order.
   - Option 3: Modify an existing order.
   - Option 4: Print the receipt and make payment.
   - Option 5: View the daily summary of total sales.
   - Option 6: Exit the program.

3. Follow the instructions provided by the system to perform the selected operation.

## Dependencies

The project uses the following libraries:
- iostream
- stdlib.h
- string
- cctype
- cmath
- cstdio
- fstream
- iomanip

## License

This project is licensed under the [MIT LICENSE](https://github.com/harishngt/Pharmacy-Management-System/blob/main/LICENSE).

## Contributors

The Pharmacy Management System project was developed by HARISH G. Feel free to contribute to the project by submitting bug reports, feature requests, or pull requests.

## Contact Information

For any inquiries or support, please contact hk21062004@gmail.com.
