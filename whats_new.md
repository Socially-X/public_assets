# 🚀 Release Notes: Version 2.4.4 (Build 77)

## ✨ New Features & Enhancements
* **Image Management:** Completed integration for **Post Image Object Storage**, improving performance and scalability (merged via PR #65).
* **UI/UX:** Applied **Image Clamping** and fixed aspect ratios for product images, ensuring consistent display.

## 🐛 Fixes & Improvements
* Minor UI adjustments and improvements.
* Fixed a null error that occurred on the **Preview screen**.
* Resolved an issue where images were scrolling unintentionally upon post like updates.
* Ensured the product completion checkmark (`isDoneVisible`) updates in real-time in the Add Products flow.

---

# 🚀 Release Notes: Version 2.4.3 (Build 76)

## ✨ New Features & Enhancements
* **Post/Product Interaction:** Fixed and enhanced the post and product **like animation** to work correctly even when liking by tapping on white spaces.

---

# 🚀 Release Notes: Version 2.4.2 (Build 75)

## ✨ New Features & Enhancements
* **Interactions:** Implemented an **animated like appearance** for products.
* **Interactions:** Enabled **double-tap to like** functionality on posts.
* **Image Display:** Made post and product images **flexible on width** to ensure full images are shown without cropping issues.

## 🐛 Fixes & Improvements
* Applied minor dark mode compatibility updates.

---

# 🚀 Release Notes: Version 2.4.1 (Build 74)

## ✨ New Features & Enhancements
* **Seller Product Flow (Major Overhaul):**
    * **Modular Design:** Introduced a new modular design for **Add Products** with **Check Marks** to guide sellers based on field completion status.
    * **Image Section:** The **Image Upload Screen** is now available in the Add Products flow.
    * **Product Editing:** Refactored product text fields into a unified screen (`ProductTextFieldsScreen`) and introduced separate sections for **Basic Details** and other details for a clearer editing experience.
    * **Navigation:** The bottom navigation bar is now automatically hidden when adding or editing a product.
* **Image Management:** Implemented the new **Reorderable Add Images horizontal list** with delete functionality.
* **UI/UX:** Updated the price card UI for products without variants.

## 🐛 Fixes & Improvements
* Resolved minor padding and alignment issues with the navigation profile icon.

---

# 🚀 Release Notes: Version 2.4.0 (Build 73)

## ✨ New Features & Enhancements
* **Image Management:**
    * Implemented the full image management flow: added **reordering capability** for product images.
    * Added a **preview UI** and **"Discard Changes" confirmation dialog** for image edits, allowing users to restore original images.
    * Implemented deferred image reorder and upload with persistent state management for a safer save process.
* **Seller Tools:** Added **confirmation dialogs** before saving default store settings (Delivery/Warranty).
* **Notifications:** Introduced **automatic refresh for notifications** every 10 seconds.
* **Discovery:** Added a **private discovery bottom sheet** to explain visibility and growth status to store owners.

## 🐛 Fixes & Improvements
* Fixed a bug where the **edit product image** would retain old images.
* Resolved an issue where the **bottom navigation bar** was incorrectly visible on the preview screen.

---

# 🚀 Release Notes: Version 2.3.9 (Build 72)

## ✨ New Features & Enhancements
* **Product Details:** Added a **Variant List View Toggle** in the variant selection bottom sheet, offering users a new way to select product variants.
* **Notifications:** Implemented logic to **automatically switch to the store account** before navigating to store-related notifications when the user is in buyer view.

## 🐛 Fixes & Improvements
* Refactored variant selection and price display logic for improved clarity and reliability.
* Enhanced stock update flow with better error handling.
* Improved navigation stability by adding context checks and fallback handling to reduce crashes on notification deep-links.

---

# 🚀 Release Notes: Version 2.3.8 (Build 71)

## 🐛 Fixes & Improvements
* Enhanced the **account context switching logic** (User $\rightleftharpoons$ Store) on notifications for a smoother transition.
* Fixed an issue that prevented **swipe down to refresh** on the orders and notifications screens.

---

# 🚀 Release Notes: Version 2.3.7 (Build 70)

## ✨ New Features & Enhancements
* **UI/UX:** Switched scroll physics in all major lists (orders, notifications) to **BouncingScrollPhysics** for a smoother scrolling experience.
* **Product Validation:** Added validation to ensure the **selling price is not zero** and does not exceed the MRP.

## 🐛 Fixes & Improvements
* Improved keyboard handling by ensuring the keyboard closes on gender selection and before navigating away from search screens.
* Fixed various UI responsiveness issues.

---

# 🚀 Release Notes: Version 2.3.6 (Build 69)

## ✨ New Features & Enhancements
* **Seller FAQ:** Enhanced the **Store FAQ Screen** with detailed owner disclaimers and introduced a dedicated **Reordering Mode** UI.

## 🐛 Fixes & Improvements
* **UI/Style:** Major update to standardize text alignment, padding, and spacing across the application for a cleaner look.
* **Navigation:** Improved **bottom navigation safe area handling** to prevent UI clipping on devices with screen notches.
* Fixed the logic for **post save status** toggling.

---

# 🚀 Release Notes: Version 2.3.5 (Build 68)

## ✨ New Features & Enhancements
* **Messaging:** Added support for **`chat_owner_reference`** in the `ChatInfo` model, improving context for chat ownership.

---

# 🚀 Release Notes: Version 2.3.4 (Build 67)

## ✨ New Features & Enhancements
* **Seller Account:** The **expected amount** is now highlighted (bolded) in the "Total Amount to be Received" list.
* **Buy Flow:** Implemented a new **Update Pin Code Dialog** in the Buy Button flow, allowing users to update their delivery postal code if delivery is unavailable.

## 🐛 Fixes & Improvements
* Refactored the single post view to show a custom "+" menu button for product comments.
* Corrected the condition for bolding the expected amount in the total amount received widget.

---

# 🚀 Release Notes: Version 2.3.3 (Build 66)

## ✨ New Features & Enhancements
* **KYC:** Replaced the plain text field for PAN Date of Birth with a user-friendly, selectable **Calendar Widget**.
* **Messaging:** Added detailed **timestamp formatting** and the **sender's name** to message bubbles.
* **Onboarding:** On first-time store activation, the user is now automatically navigated to the **Share Store Screen** with a relevant toast message.
* **Seller Accounts:** Store names on creation are now appended with `(Preview)`.

## 🐛 Fixes & Improvements
* Fixed an issue with in-app **messaging sharing**.
* Removed unnecessary snack bar errors from the messaging screen.
* Increased the chat preview text limit to 30 characters.

---

# 🚀 Release Notes: Version 2.3.2 (Build 65)

## ✨ New Features & Enhancements
* **Messaging:** Added **`chatOwnerReference`** to data models and components, making the chat header tappable to navigate to the respective store or user profile.
* **App Config:** Integrated app help links via remote configuration.

---

# 🚀 Release Notes: Version 2.3.1 (Build 64)

## 🐛 Fixes & Improvements
* Fixed the **Content Navigation Issue** by ensuring tab context updates in Buyer and Seller navigation for correct deep link handling.
* Removed the auto-withdraw option in "Send to Bank."

---

# 🚀 Release Notes: Version 2.3.0 (Build 63)

## ✨ New Features & Enhancements
* **KYC:** Completed the **PAN date of birth integration** using the new calendar widget.
* **UI:** Implemented Dark mode updates (intermediary).

## 🐛 Fixes & Improvements
* **Inventory:** Added **validation for pricing inputs** (MRP/Selling Price) before saving the product.
* **UI/Style:** Standardized button sizes and text overflow handling across store UI to prevent text clipping.
* Fixed an issue while editing inventory options of a product.

---

# 🚀 Release Notes: Version 2.2.9 / 2.2.8 (Build 62 / 61)

## 🐛 Fixes & Improvements
* **Navigation:** Refactored navigation logic to open linked content (Post, Product, Store) **directly in the current tab** for immediate visibility, eliminating unnecessary tab switching.
* Made the **clear cache messaging button** appear only in the dev environment for safer production use.
* Fixed color contrast for toast messages.

---

## App Version 2.2.4 Release Notes:

### 🐞 **Bug Fixes & Performance Improvements**

* Fixed an issue where the static user profile would still appear after a user logged in.  
* Resolved a bug with static user accounts being unable to add a post.  
* Corrected app URL redirection.  

---

## App Version 2.2.3 Release Notes:

### 🐞 **Bug Fixes & Performance Improvements**

* Home indicator now syncs with the app's theme color.  
* Fixed several minor UI issues.  
* Resolved cross-account notification redirection issues, allowing seamless switching between user and store.  
* Self-notifications are now properly displayed in the notifications tab.  

---

## App Version 2.2.2 Release Notes:

### ✨ **New Features**

* Added long-press gestures for product and post cards.  
* Implemented proper loading animations in the "For You" tab.  
* Enabled blog redirection from the user and store option menus.  
* Integrated saved content and tagged posts for stores.  
* Added a new compact app bar and navigation bar icons.  

### 🐞 **Bug Fixes & Performance Improvements**

* Redirect static users to login if they attempt to add a post.  
* Fixed pixel overflow issues in the store tagged content screen.  
* Resolved repost and saved tab issues.  
* Corrected navigation keypad issues.  
* Fixed app bar and tab bugs.  
* Corrected the save API issue in product cards.  
* Replaced repost GQL API with REST API for better performance.  
* Numerous UI corrections and refactorings.  

---

## App Version 2.2.0 Release Notes:

### ✨ **New Features**

* Refactored store management with improved UI/UX for activation and deactivation.  
* Stores now start on the profile tab and users start on the home tab for intuitive navigation.  
* Added a modular store dashboard.  

### 🐞 **Bug Fixes & Performance Improvements**

* Fixed product link redirection bug.  
* Resolved `is_discoverable` filter issue in the "For You" tab.  
* Updated store deactivation and deletion processes.  
* Status and home indicator bars now match the app theme color.  
* Multiple UI improvements to status cards.  

---

## App Version 2.1.9 Release Notes:

### ✨ **New Features**

* Added new discovery content with enhanced bottom sheets.  
* Added hold-to-copy functionality for pickup locations.  
* Implemented "Suggest a Feature" for stores.  

### 🐞 **Bug Fixes & Performance Improvements**

* Fixed "Buy" button issue for delivery-only options.  
* Corrected SVG color inversion in home screen icons.  
* Small UI fixes and enhancements.  

---

## App Version 2.1.8 Release Notes:

### ✨ **New Features**

* Added `is_discoverable` field to user/store models.  
* Streamlined dark mode with updated navigation and icons.  
* Implemented bouncing scroll physics for refreshing screens.  
* Enabled auto-hide navigation bar on feed screen.  
* Introduced Twitter-style comment/reply page.  
* Added common referral page for static and logged-in users.  
* Implemented app suggestions with feedback submission.  
* Added App Startup Message feature with remote config.  

### 🐞 **Bug Fixes & Performance Improvements**

* Fixed "Mark as Read" issue in messaging.  
* Completed messaging notification redirection.  
* Numerous UI refactorings and styling improvements.  
* Fixed repost count and comment display issues.  
* Corrected typos and updated comment bottom sheet logic.  
* Fixed resend OTP issue on login screen.  

---

## App Version 2.1.7 Release Notes:

### 🐞 **Bug Fixes & Performance Improvements**

* Handles null rating values gracefully in product details.  
* Removed refresh indicator from inventory options screen.  
* Fixed messaging screen bugs and group messaging mix-ups.  
* Fixed "Buy" button issues.  
* Resolved static review removal problems.  
* Corrected API issues and improved code readability.  

---

## App Version 2.1.6 Release Notes:

### 🐞 **Bug Fixes & Performance Improvements**

* Fixed messaging screen bugs.  
* Resolved group messaging mix-ups.  

---

## App Version 2.1.5 Release Notes:

### ✨ **New Features**

* Enhanced feedback functionality with target reference support.  
* Implemented Store FAQ with CRUD operations and caching.  
* Added product option rename feature during creation/edit.  

---

## App Version 2.1.4 Release Notes:

### 🐞 **Bug Fixes & Performance Improvements**

* Fixed "Buy" button issues.  

---

## App Version 2.1.3 Release Notes:

### 🐞 **Bug Fixes & Performance Improvements**

* Redirect users to store screen after editing/adding a product.  

---

## App Version 2.1.2 Release Notes:

### ✨ **New Features**

* Updated product loading messages for better UX.  
* Added product ratings and rating counts.  
* Updated save status logic.  

---

## App Version 2.1.1 Release Notes:

### ✨ **New Features**

* Enhanced store updates access control.  
* Improved messaging UI with consistent loading indicators.  
* Added repost confirmation dialog.  
* Added Preview Store icon and related components in creation flow.  
* Implemented pagination for seller orders.  
* Added Tagged Posts feature with navigation and API integration.  
* Implemented modal bottom sheet for Store Menu.  

---

## App Version 2.1.0 Release Notes:

### ✨ **New Features**

* Added repost confirmation dialog.  
* Added Preview Store icon and functionality in store creation.  
* Implemented seller order pagination.  
* Enhanced Store Creation Announcement with preview button.  
* Added Tagged Posts with navigation and API.  
* Implemented modal bottom sheet for Store Menu.  
* Added navigation to Buyer View Store from Seller Accounts.  

### 🐞 **Bug Fixes & Performance Improvements**

* Corrected method name from `opeAppWebView` to `openAppWebView`.  
* Improved store reviews and product detail display.  
* Added orders icon to seller home page.  

---

## App Version 2.0.9 Release Notes:

### ✨ **New Features**

* Enhanced buyer image preview and store menu.  
* Added orders icon to seller home page.  

### 🐞 **Bug Fixes & Performance Improvements**

* Refactored UI padding/icons on home screens.  
* Improved store review display.  
* Corrected product slug link preview.  
* Fixed swipe-to-refresh issue when no products in store.  
* Refactored product display and variant selection logic.  
* Fixed product grid pagination.  
* Various small UI changes and fixes.  

---

## App Version 2.0.8 Release Notes:

### ✨ **New Features**

* Added suborder references to shipping history.  
* Variant stock update/delete API integration.  
* Added out-of-stock indicators and improved search visibility.  
* Added product code display.  
* Implemented inventory options navigation and caching for variants.  
* Enhanced cart for product variants.  
* Added product options/variants.  
* Added new SVG icons.  
* Added product rating and sales display.  
* Added store review count and average rating.  
* Multi-image uploads for external review requests.  
* Reporting for store reviews.  
* External Store Review with QR code generation.  
* Instagram-like mention system.  

### 🐞 **Bug Fixes & Performance Improvements**

* Fixed edit product slug preview bug.  
* Fixed swipe-to-refresh with no products.  
* Increased product fetch limit from 5 to 10.  
* Corrected "grid" spelling.  
* Refactored UI/code for performance.  
* Fixed tagging issues.  
* Refactored URL handling for slug links.  

---

## App Version 2.0.6 Release Notes:

### ✨ **New Features**

* External store review functionality.  
* Full preview option for tagged items in add/edit post.  
* Added product slug and code fields to forms.  

### 🐞 **Bug Fixes & Performance Improvements**

* Fixed tagging issues with deactivated ancestors.  
* Improved tagging bottom sheet UI.  
* Enhanced post editing with tagged references.  
* Refactored URL handling for product slug links.  
* Increased font size for better readability.  
* Improved UI elements/layout.  
---

## App Version 2.0.5 Release Notes:


### ⚡ **Faster App Experience**

* Experience blazingly fast feed, search screens and app experience 

### 💬 **Better Messaging**

* Real-time chat with emojis, file/image sharing, and link previews
* Search chats, mark messages as read, and ask sellers questions easily

### 🔁 **Easier Returns & Cancellations**

* Clear return timelines, refund status, and package tracking
* Smoother cancellation process with updated status info

### 🏪 **Improved Profiles**

* New Store Valuation, Support Score & Level Badges
* Add cover images, share store via QR code, and manage warranties/returns

### 🚚 **Smarter Shipping**

* Track updates, manage balances, and download labels directly
* Shiprocket integration for better delivery flow

### 🔐 **Faster Login & Onboarding**

* Easy email verification with OTP and improved Google sign-in

### ⚡ **Cleaner Look & Smoother Performance**

* Refreshed UI, better layouts, faster load times
* Bug fixes for chat, feeds, and login

---

## App Version 1.4.8 Release Notes:

1. **Location update to unsigned user:** Now unsigned in user can update his pincode!

## App Version 1.4.7 Release Notes:

1. **Repost Feature:** Amplify content for your favorite stores & people with ease!  
2. **Save for Later:** Save posts and products to revisit anytime.  
3. **Upgraded Messaging:** Faster, more secure chats with online status indicators.  
4. **Optimized Feed:** Enjoy a smoother & engaging experience.  
5. **Product Search:** Search products directly from the store page.  
6. **Bug Fixes:** Sharing products, user profiles, and store profiles made easy.

## App Version 1.4.3 Release Notes:

1. **Affiliate Program:** Earn a 20% lifetime revenue share for every store you refer to Swadesic! 🎉  
2. **Premium Subscriptions:** Unlock exclusive services for buyers and stores with Swadesic Premium, plus enjoy a share in revenue.  
3. **Real-time Messaging:** Connect effortlessly! Chat with users, stores, and the community in real-time.  

## App Version 1.4.0 Release Notes:

1. **Onboarding Redesign:** Enjoy a fresh, improved sign-up and sign-in experience.
2. **Faster Sign-Up:** Automatically fetch your profile picture when using Google sign-in for a quicker setup.
3. **Enhanced Product UI:** A cleaner, more intuitive interface for smoother browsing and better usability.
4. **Welcome Guide:** New users are greeted with a guide to help them get started with Swadesic easily.
5. **Order Alerts:** Stores now receive instant notifications as soon as they open the app, keeping them updated on orders.
6. **Simplified Withdrawals:** Setting up your bank account is now easier, with automatic withdrawals enabled for balances over ₹500.

## App Version 1.3.7 Release Notes:

1. Made Mandatory improvements to product availability statuses.
3. Bug fixes and improvements.

## App Version 1.3.6 Release Notes:

1. Improved error handling with custom messages for each product.

## App Version 1.3.5 Release Notes:

1. Improved error handling with custom messages for each product

## App Version 1.3.4 Release Notes:

1. Bug fixes and minor improvements.

## App Version 1.3.3 Release Notes:

1. **Bug Fixe:** Resolved an issue with the delivery settings where the standard fee was not saving correctly.

## App Version 1.3.0, 1.3.1 and 1.3.2 Release Notes:

🛍️ **For Consumers:**
1. **Order Products Securely:** Easily order from your favorite stores and pay using Razorpay.
2. **Product Feed:** View products from supported stores in your feed for a personalized shopping experience.
3. **Rate Products:** Leave ratings in product comments to help others make informed decisions.
4. **Referral Program:** Invite friends and stores to earn Infinity points up to ₹251 each, which you can use for your orders.
5. **Refund Policies:** Enjoy clearer and more transparent refund policies.

🏪 **For Stores:**
1. **Nationwide Orders:** Receive orders across India as a business or state-wide as an individual.
2. **Enhanced Mini Dashboard:** Track sales and metrics with an improved interface.
3. **ID Verification:** Streamlined ID verification process for store owners.

**General:**
1. **Bug Fixes & Performance Enhancements:** Enjoy a smoother and more reliable app experience with various fixes and optimizations.


## App Version 1.2.2 Release Notes:

1. **Google Authentication:** Easily sign in with Google for quicker access.
2. **Like Visibility:** See who liked your posts and products.
3. **Product Recommendations:** View product recommendations across different stores.

## App Version 1.2.0 Release Notes:

**Security & User Experience Improvements:**
1. **Enhanced Onboarding:** Easier username creation, profile picture upload, and role selection.
2. **Better Security:** Encrypted APIs for safer data.
3. **Maintenance Mode:** Clear notifications during maintenance.
4. **Smoother Navigation:** Improved banner interaction and error messages.
5. **Visual Tweaks:** Easier-to-see post likes and comment counts.
6. **Comments & Replies:** Better visibility.
7. **Store Interaction:** Clearer messages for store metrics.

## App Version 1.1.0 Release Notes:

1. **Quick Access for Sellers:** Add posts and product additions right from the navigation bar.
2. **Public Access to Visitors:** Discover and share products (sellers) without the need to sign up.
3. **Better Commenting:** Enhanced commenting features for improved engagement.
4. **Email Sign-In Added:** Secure your account with an additional sign-in option.
5. **Restricted Access for Guests:** Enjoy a safer app environment with restricted features for non-registered users.
6. **Forced Updates:** Ensure your app runs smoothly and stays secure with prompt updates.

## App Version 1.0.2 Release Notes:

1. Easy navigation to the parent content and seamless app update notification.

## App Version 1.0.1 Release Notes:

1. **Comment Replies Viewing:** Improved viewing of comment replies on post pages.
2. **Character Limits:** Increased character limits for various fields.
3. **Streamlined Transition:** Streamlined transition after hitting 'Go live now.'
4. **Store Bio Display:** Ensured proper display of store bio and usability of links.
5. **Banner Image Optimization:** Optimized banner image fit.
6. **Share Card Feature:** Introduced a "share card" feature for encouraging platform sharing.
7. **Share Card Update:** Updated share card text and removed reported items from support list.
8. **Animation Enhancement:** Enhanced transition animation and resolved duplication of post content.

## App Version 1.0.0 Release Notes:

1. Introducing a compelling Market Network for Swadeshi products.
