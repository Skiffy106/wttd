# Instagram Influencer Account Manager

## 📸 Project Overview

The **Instagram Influencer Account Manager** is a Python-based tool designed to help manage, monitor, and analyze Instagram influencer accounts using the Instagram Graph API. This project allows you to:

- Track influencer account performance
- Retrieve follower and engagement data
- Manage posts and content insights
- Streamline influencer collaboration processes

## 🚀 Features

- ✅ Connect to Instagram accounts via the Instagram Graph API
- ✅ Retrieve follower counts, engagement rates, and post metrics
- ✅ Track influencer growth over time
- ✅ Manage and categorize influencer accounts
- ✅ Export influencer data for reporting

## 🛠️ Technologies Used

- **Python 3.8+**
- **Instagram Graph API**
- **Requests Library** for API calls
- **Pandas** for data management
- **SQLite3** (or any supported database) for storing influencer profiles

## 📂 Project Structure

```
instagram-influencer-manager/
├── main.py
├── api/
│   ├── instagram_api.py
├── database/
│   ├── influencer_db.py
├── utils/
│   ├── helpers.py
├── requirements.txt
└── README.md
```

## ⚙️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/instagram-influencer-manager.git
   cd instagram-influencer-manager
   ```

2. **Create Virtual Environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Environment Variables**
   Create a `.env` file with your Instagram API credentials:

   ```
   IG_ACCESS_TOKEN=your_instagram_access_token
   IG_ACCOUNT_ID=your_instagram_account_id
   ```

5. **Run the Application**

   ```bash
   python main.py
   ```

## 📈 Usage Example

Example: Retrieve follower count and engagement metrics for an influencer:

```python
from api.instagram_api import InstagramAPI

api = InstagramAPI()
influencer_data = api.get_account_metrics('influencer_username')
print(influencer_data)
```

## ✅ Requirements

- Instagram Graph API Access
- Instagram Business or Creator Account
- Facebook App with Instagram Basic Display or Graph API permissions

## 📚 Documentation

- [Instagram Graph API Documentation](https://developers.facebook.com/docs/instagram-api/)
- [Authentication Guide](https://developers.facebook.com/docs/instagram-basic-display-api/getting-started)

## 🔒 Disclaimer

This project is for educational and personal use only. In compliance with Instagram’s [Platform Policy](https://developers.facebook.com/policy/).

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## 📧 Contact

For questions or support, please reach out to \[mason.tuttle21@gmail.com] or open an issue on GitHub.
