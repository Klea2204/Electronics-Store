ElectronicStore

An inventory and billing management application for an electronic store. This project handles products, suppliers, users, billing, and reporting functionalities. Built with Java and Maven, it provides a structured and extendable base for managing store operations efficiently.

🚀 Features

Manage product inventory and categories

Add/edit/remove suppliers and users

Generate sales and inventory reports

Bill generation and management

Persisted data storage using .dat files

📁 Project Structure

ElectronicStore/
├── store_data/              # Stores persistent data (items, users, suppliers, etc.)
│   ├── bills/               # Individual bill files
│   ├── items.dat            # Product data
│   ├── users.dat            # User data
│   ├── suppliers.dat        # Supplier data
│   ├── categories.dat       # Categories
│   └── sales_report_*.txt   # Sales reports
├── pom.xml                  # Maven project file
├── .gitignore               # Git ignore file
├── *.iml, *.xml             # IntelliJ and build files

⚙ How to Run

Requirements:

Java JDK 11 or higher

Maven 3+

Clone the Repository:

git clone https://github.com/yourusername/ElectronicStore.git
cd ElectronicStore

Build and Run:

mvn clean install
java -jar target/ElectronicStore.jar

📦 Dependencies

Defined in pom.xml, key dependencies include:

maven-compiler-plugin: for compiling Java code

(Add others if specific libraries are used)

📊 Data Files

All data is saved in store_data/ using serialized .dat files

Bills and reports are auto-generated and timestamped

