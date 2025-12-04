# AquaSentinel

AquaSentinel is an IoT-based web application designed to monitor and analyze water quality in real-time. By collecting data on various water parameters, it provides users with insights into overall water health, aiding in proactive water resource management.

## Features
- 🔍 **Data Filtering**: Customize data views based on specific time frames and locations.
- 🔐 **User Authentication**: Secure login system ensuring personalized access and data security.
- 📊 **Interactive Dashboards**: Visualize real-time and historical water quality data through dynamic charts and graphs.
- ⚠️ **Alerts System**: Receive automated notifications when critical changes in water quality are detected.

## Tech Stack
​AquaSentinel employs advanced machine learning algorithms to enhance its water quality monitoring and predictive capabilities:​
- **Random Forest Classifier**: Utilized for predicting water quality based on parameters such as pH, hardness, and turbidity. This ensemble learning method improves accuracy by constructing multiple decision trees during training and outputting the mode of their predictions. ​
Academia
- **Support Vector Machine (SVM)**: Applied to classify water quality data by finding the optimal hyperplane that separates different classes, ensuring robust performance even in high-dimensional spaces. ​
Academia
- **K-Nearest Neighbors (KNN)**: Implemented for classifying water samples by analyzing the 'k' closest data points, allowing for straightforward and effective predictions based on similarity measures. ​

## Installation & Setup

### Prerequisites
Before setting up AquaSentinel, ensure you have the following installed:
- **Node.js**: JavaScript runtime environment.
- **npm**: Node package manager.
- **MongoDB**: NoSQL database for data management.

### Clone the Repository
Open your terminal and execute:
```bash
git clone https://github.com/Aadvik1011/AquaSentinel.git
cd AquaSentinel
```

### Configure Environment Variables
Create a `.env` file in the project directory with the following content:
```env
DB_URI="your_mongodb_database_url"
dataCount=1000
FILE_PATH=your_dataset.csv
COLUMN_NAMES=ph,Organic_carbon,Turbidity,Solids,Trihalomethanes
```
Replace `your_mongodb_database_url` and `your_dataset.csv` with your actual MongoDB connection string and dataset file path, respectively.

### Install Dependencies
Install the required Node.js packages:
```bash
npm install
```

### Run the Application
Start the application with:
```bash
npm start
```
Access the application in your web browser and register as a new user to begin monitoring water quality.

## Usage Guide
2. **Dashboard Access**: After logging in, explore interactive dashboards displaying water quality metrics.
3. **Data Filtering**: Apply filters to focus on specific time periods or locations.
4. **Alerts**: Set up notifications to stay informed about significant changes in water quality.

## Future Enhancements
AquaSentinel aims to incorporate additional features, including:
- 📱 **Web Application**: Developing a mobile app for on-the-go monitoring.
- 📊 **Advanced Analytics**: Implementing predictive analytics for proactive water quality management.
- 🔗 **Third-Party Integrations**: Integrating with external systems for broader data analysis.

## Contributing
Contributions to AquaSentinel are welcome! To contribute:
1. **Fork the repository** on GitHub.
2. **Create a new feature branch**: (`git checkout -b feature-branch`).
3. **Implement your changes** and commit them with descriptive messages.
4. **Push your changes** to your forked repository.
5. **Submit a pull request** with a detailed description of your modifications.

## License
AquaSentinel is open-source and licensed under the **MIT License**. For more details, see the [LICENSE](LICENSE) file.

## Contact & Support
For inquiries, suggestions, or issues, feel free to reach out via:
- 📧 Email: aadvik1011@gmail.com
- 💬 GitHub Issues: [GitHub Issues Page]
- 🌐 LinkedIn: Aadvik Bharadwaj

*Note: This README is based on the information available from the AquaSentinel repository and related sources.*

