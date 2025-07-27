**Sarthi Bot** is a dual-interface chatbot system designed to connect **vendors** with **suppliers** for the efficient procurement of raw materials.

- **VendorBot** helps small food vendors find and negotiate with local suppliers.
- **SupplierBot** enables suppliers to list their products and manage pricing.

---

## 🔗 Live Demo

🌐 **Try it now**: [https://sarthibot.vercel.app/](https://sarthibot.vercel.app/)

---

## 🔑 Key Features

### 🛒 VendorBot Features

- **Product Search**: Find suppliers for common food items (onion, tomato, paneer)
- **📍 Location-Based Matching**: Uses pincode to find local suppliers
- **💰 AI-Powered Bargaining**: Simulates price negotiation with suppliers
- **📱 Mobile-Friendly Interface**: Works on all devices

### 🏷 SupplierBot Features

- **📝 Easy Registration**: Simple onboarding for new suppliers
- **Product Listing**: Add products with pricing details
- **📊 Price Management**: Set standard, minimum, and maximum prices
- **🌐 Local Visibility**: Products appear to vendors in your area
- **🔄 Multi-Product Support**: List multiple products easily

---

## ❓ Why This Project?

### Vendors in India Face:

- Difficulty finding reliable local suppliers
- Time-consuming manual price negotiation
- Lack of price transparency
- No digital procurement tools

### Suppliers Struggle With:

- Limited reach to potential customers
- Inefficient price communication
- No standardized way to list products

---

## 💡 Our Solution

- **Digital Marketplace**: Connects vendors and suppliers directly
- **Price Transparency**: Clear pricing ranges upfront
- **Negotiation Tools**: Built-in bargaining simulation
- **Local Focus**: Pincode-based matching
- **Simple UI**: Accessible to non-technical users

---

## 🌱 Future Enhancements

- 📧 Email Confirmations: Send deal details to both parties
- 📈 Dynamic Bulk Pricing Engine
- 🚚 Real-Time Order Tracking

---

## 🛠 Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **AI**: Gemini 1.5
- **Hosting**: [Vercel](https://vercel.com)

---

## 🧩 Components

- Dual Chat Interfaces: VendorBot & SupplierBot
- Interactive Message System: With quick replies
- Form-like Data Collection: Easy input from users
- API Integration: Pincode lookup via [postalpincode.in](https://postalpincode.in)
- State Management: Chat state machines for both bots
- AI Features: Bargaining simulation with logic
- Language: Hinglish (Hindi + English) responses

---

## 🚀 Installation & Setup

### 🔧 Local Setup

```bash
git clone https://github.com/dakshtitarmare/SarthiBot.git
cd SarthiBot

🖥 Open in Browser
Just open index.html in any modern browser.


✅ Works with file:// protocol — no server required!



🌐 Deployment on Vercel (Optional if already deployed)

Already Live: ✅ https://sarthibot.vercel.app/


Want to deploy yourself?

Go to https://vercel.com and sign in with GitHub.


Click "New Project" and import your SarthiBot repo.


Keep all default settings.


Click "Deploy".


Your project will be live instantly.



🧑‍💼 Usage Guide
👨‍🍳 For Vendors:

Select VendorBot interface


Choose a product


Enter your pincode


Specify quantity


Set your price range


Browse local suppliers


Negotiate with AI


🏭 For Suppliers:

Select SupplierBot interface


Register your business


Add product categories


List products with pricing


Set bargaining ranges


Respond to vendor requests



📦 Key JavaScript Components

vendorChatState – Tracks vendor conversation state


supplierChatState – Tracks supplier conversation state


suppliersDatabase – Local JSON database of supplier/product data


addBotMessage() – Renders bot responses in chat


handleVendorResponse() – Handles VendorBot input & flow


handleSupplierResponse() – Handles SupplierBot input & flow



##👨‍💻 Team SarthiBot


| Name                 | Role                              | LinkedIn      |
| -------------------- | --------------------------------- | ------------- |
| **Daksh Titarmare**  | Team Lead + Backend Developer     | [LinkedIn](#) |
| **Tejas Bankar**     | Frontend Developer + AI Lead      | [LinkedIn](#) |
| **Visvesh Paturkar** | Backend Developer                 | [LinkedIn](#) |
| **Pratik Lajewar**   | Backend Developer + Documentation | [LinkedIn](#) |





📄 License
This project is open-source and available under the MIT License.


