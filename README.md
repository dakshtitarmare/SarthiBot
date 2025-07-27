# SarthiBot
Sarthi Bot 🤖

A dual-interface chatbot system that connects vendors with suppliers for efficient procurement of raw materials. VendorBot helps small food vendors find and negotiate with local suppliers, while SupplierBot enables suppliers to list their products and manage pricing.

Key Features : VendorBot Features 🛒 Product Search: Find suppliers for common food items (onion, tomato, paneer) 📍 Location-Based Matching: Uses pincode to find local suppliers 💰 AI-Powered Bargaining: Simulates price negotiation with suppliers 📱 Mobile-Friendly Interface: Works on all devices

SupplierBot Features : 📝 Easy Registration: Simple onboarding for new suppliers 🏷 Product Listing: Add products with pricing details 📊 Price Management: Set standard, minimum, and maximum prices 🌐 Local Visibility: Products appear to vendors in your area 🔄 Multi-Product Support: List multiple products easily

Why This Project? Problem Being Solved : Small food vendors in India face: Difficulty finding reliable local suppliers Time-consuming manual price negotiation Lack of price transparency No digital procurement tools

Suppliers struggle with: Limited reach to potential customers Inefficient price communication No standardized way to list products

Our Solution : Digital Marketplace: Connects vendors and suppliers directly Price Transparency: Clear pricing ranges upfront Negotiation Tools: Built-in bargaining simulation Local Focus: Pincode-based matching Simple UI: Accessible to non-technical users

Future Enhancements : Email Confirmations: Sends deal details to both parties Dynamic Bulk Pricing Engine 📈🤝 Real-Time Order Tracking 🚚📍

Tech Stack : Frontend: HTML5, CSS3, JavaScript AI: Gemini 1.5

Components : Dual chat interfaces (Vendor/Supplier) Interactive message system with quick replies Form-like data collection flows API Integration - Pincode lookup via postalpincode.in API State Management - Chat state machines for both bots AI Features - Bargaining simulation with price calculation logic Natural language responses in Hinglish (Hindi+English)

Installation & Setup Download the files: git clone https://https://github.com/dakshtitarmare/SarthiBot.git cd SarthiBot Open in browser: Simply open index.html in any modern browser (No server required – works with file:// protocol)

Configuration (for production): Add real API keys for services Implement server-side persistence

Usage Guide For Vendors: Select "VendorBot" interface Choose desired product Enter your pincode Specify quantity needed Set price range Browse available suppliers Negotiate price

For Suppliers: Select "SupplierBot" interface Register your business Add product categories List products with pricing Set bargaining ranges Receive vendor inquiries

Key JavaScript Components vendorChatState – Tracks vendor conversation state supplierChatState – Tracks supplier conversation state suppliersDatabase – Local storage of supplier/product data addBotMessage() – UI message rendering function handleVendorResponse() – Vendor conversation logic handleSupplierResponse() – Supplier conversation logic
