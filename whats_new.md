# 🚀 Release Notes: Version 3.1.3 (Build 106) 

## ✨ New Features & Enhancements
* **Onboarding:** First sign-in auto-fills your name and username from your account info.
* **Onboarding:** Username step skips re-validation when the pre-filled value is unchanged — no more false "unavailable" errors.
* **UI/UX:** Store Products title styling matched to Notifications; removed double top-spacing in feed detail views.
* **Places:** Sub-tab position fix.

## 🐛 Fixes & Improvements
* Can't go back to the OTP screen from post-verification onboarding — first back-press shows "Tap again to exit," second exits.
* Fixed "Cannot open chat: Invalid contact ID" for never-chatted contacts; recommendations no longer list contacts that can't receive chats.

---

# 🚀 Release Notes: Version 3.1.2 (Build 105)

*Play Store: Store Wallet is now Store Rewards. Glass headers scroll cleanly with no gaps, tagged posts load faster, and Invite & Help is one tap away.*

## ✨ New Features & Enhancements
* **Store Rewards:** Store Wallet → Store Rewards across buyer and store UI (My Store Rewards, Reward Balance, Store Reward Balance); Instant Order Links and Log Offline Orders added to store quick access.
* **Invite & Help:** Tapping the Swadesic icon on buyer home now opens the same Invite & Help page as seller home.
* **Performance:** Tagged-post photos now use presigned URLs (faster, no stale images).

## 🐛 Fixes & Improvements
* Glass-header scroll: removed invisible static headers behind the glass that caused gaps; profile/store/product grids now thread headers inside the scroll view so content slides correctly under the glass.
* Profile-tab back navigation animates back to the profile sub-tab before exiting.

---

# 🚀 Release Notes: Version 3.1.1 (Build 104)

*Play Store: Smoother feeds with pull-to-refresh, more reliable tag and mention taps, and faster, steadier cart totals.*

## ✨ New Features & Enhancements
* **Feeds:** Pull-to-refresh, smoother bounce scrolling, more reliable endless-scroll pagination.
* **Tags & Mentions:** Tapping store / product / user tags and mentions now resolves consistently.
* **Cart:** Faster cart totals and delivery-fee calculation (batched backend fetch).

## 🐛 Fixes & Improvements
* Comment box now reliably visible on post views; fixed spacing.
* Post views no longer show the stray bottom nav grid.

---

# 🚀 Release Notes: Version 3.1.0 (Build 103)

*Play Store: Fresh new look with liquid-glass navigation across home, search, cart and profile. Faster photos and checkout, shareable posts and FAQ links, and verified badges across the app.*

## ✨ New Features & Enhancements
* **Liquid-glass navigation:** New glass look across buyer home, seller home, search, notifications, messaging, cart, profile and store views — auto-hiding glass header, slide-away bottom bar.
* **Posts:** Dedicated post / comment / thread screen with shareable links.
* **FAQs:** Shareable FAQ links — auto-expands the right category/question, supports store-handle links.
* **Instant Cart:** Preview with real totals, deep-link support and fixed bottom-nav overlap.
* **Reviews:** External reviews on stores, with corrected review-request checks.
* **Performance:** Faster photos via stable cache keys, explore-icon prefetch and thumbnails; shimmer skeletons instead of spinners.
* **Cart & Checkout:** Faster cart / checkout / orders (batched backend fetches, leaner payloads).
* **Navigation:** Back stays inside the active tab, double-tap a tab to refresh, unread badges for messages/cart/notifications, quicker account switching.
* **Search:** Header search, history panel, Top Stores compact grid, `@handle` as first profile tab.
* **Seller Home:** Collapsible metrics, quick-access grid, support-score widget, repositioned onboarding checklist (Manual order → External order).

## 🐛 Fixes & Improvements
* Fixed seller-home header gap/content overlap, chrome insets and sub-tab positions.
* Fixed WhatsApp share text breaking FAQ question links; fixed store-chart tap and FAQ category limits.
* Guests tapping Notifications / Messages / Cart / Add-post / Profile are now sent to login.
* Cleaner offline handling with simpler no-internet screen.

---

# 🚀 Release Notes: Version 3.0.21 (Build 102)

*Play Store: Faster checkout with a new consolidated cart, revamped Subscriptions with plans and add-ons, and a cleaner Reviews experience with dedicated review cards. Plus smarter store analytics and shipping reliability fixes.*

## ✨ New Features & Enhancements
* **Cart:** Consolidated cart API + UI (fixes infinite price-section loading).
* **Subscriptions:** Revamp with plan management + add-on/passes tabs, user-plan screen and upgrade flow.
* **Reviews:** Review Cards feed renderer; legacy golden star removed; pending-reviews sorting.
* **Navigation:** Bottom nav auto-hides on settings sub-screens.
* **Analytics:** Store analytics with order counts + order/revenue metrics; analytics screen + home-section redirections.

## 🐛 Fixes & Improvements
* Story-from-pending-reviews wrongly marking products reviewed; pending-reviews screen issues; comment card + review bottom sheet fixes.
* Shipping label generate/download; Shiprocket webhook; shipping-history title fixes.
* Datetime conversion fix; onboarding checklist art hidden once complete.

---

# 🚀 Release Notes: Version 3.0.20 (Build 101)

*Play Store: All-new seller Home tab with order dashboard, Unanswered Questions inbox, and active orders front-and-center in your profile. Plus a unified fullscreen video player and premium-store visibility boost in search.*

## ✨ New Features & Enhancements
* **Seller Home:** All-new Home tab with live data, dashboard cards, wallet config, checklist and access grid.
* **Orders:** Order-status grid with all statuses and tap-to-filter orders.
* **Inbox:** Unanswered Questions inbox; Active / in-progress orders section in your own profile.
* **Inventory:** Manage Orderable Products section with bulk updates.
* **Discovery:** Premium-store visibility boost in search/feed.
* **Video:** Fullscreen player overhaul with shared player page, unified controls, seek bar and consistent back arrow.
* **Wallet:** Buyer-wallet UI refresh; buyer view-store products match preview style; fresher images/video via media-URL service migration.

## 🐛 Fixes & Improvements
* Store category showing "null" in search results; profile tab navigation fixes.
* Post-edit deleting images on remove; bottom-nav white flash on cold start in dark mode.

---

# 🚀 Release Notes: Version 3.0.19 (Build 100)

*Play Store: Introducing Store Wallets — balances, supporter benefits, and wallet savings at checkout. Orders now show exactly what you paid with full discount breakups. Plus verified badges, faster image/video loading, and messaging fixes.*

## ✨ New Features & Enhancements
* **Store Wallets:** New wallet system UI with tabs, metrics, supporter-detail screen, transactions with sticky filters and reward/config sheets.
* **Orders:** Stored discounts + amount-paid column; wallet/supporter breakups in buyer/seller totals.
* **Trust:** Verified badge on followers/supporters.
* **Collections:** Product lists match instant-cart UI.
* **Performance:** Faster loading with fresh-on-demand image/video URLs everywhere and a unified media-URL service (fewer stale images).
* **Messaging:** Chat list sorted by last message on the backend (faster open).

## 🐛 Fixes & Improvements
* Wallet redemption not applied to order; amount-paid calculation; refund-breakup crash fixes.
* Messaging icon missing after returning from user profile; delivery-fee null-check; review stars in user review list.

---

# 🚀 Release Notes: Version 3.0.18 (Build 99)

*Play Store: Stability and version housekeeping only — no visible changes in this release.*

## ✨ New Features & Enhancements
* No user-facing changes in this release (version housekeeping only).

## 🐛 Fixes & Improvements
* No user-facing changes in this release (version housekeeping only).

---

# 🚀 Release Notes: Version 3.0.17 (Build 98)

*Play Store: Rate your order right from the delivered-orders page, plus easier-to-read post text and smoother loading across cart, support, and verification. Fixes for chat search and repost buttons.*

## ✨ New Features & Enhancements
* **Reviews:** Leave a review for an order directly inside the order page.
* **Posts:** Larger text while composing and in comments.
* **Loading states:** Inline loading in Support recommendations, cart reset and verification Submit.

## 🐛 Fixes & Improvements
* Product-detail repost button updates instantly on tap.
* Own account no longer appears in chat search.

---

# 🚀 Release Notes: Version 3.0.16 (Build 97)

*Play Store: New Cart tab in bottom navigation, smarter share links with store referrals, and community/supporter pricing across store and product grids. Plus faster product videos and lots of cart, order, and navigation fixes.*
*Note: monorepo migration — Frontend imported into `frontend/flutter/` and backend into `backend/swadesic-main/` on 2026-05-19, between 3.0.15 and 3.0.16.*

## ✨ New Features & Enhancements
* **Cart:** Now a bottom-navigation tab.
* **Sharing:** Store share links with referral prefix; community pricing + supporter-price sheets; supporter price shown in product grid for followers.
* **Stores:** Preview-store create/edit flows; plan-based limits in Add Inventory; plan selection bottom sheet.
* **Verification:** Email OTP verification when adding a bank account; phone-number step on first store creation.
* **Product Detail:** Full Card with video-engine integration and preloading.
* **Analytics:** Store analytics graph UI; bottom-nav auto-hide in product lists and profile/store screens.
* **Reviews:** External review-request page UI refresh; supporter count on profile updates live.

## 🐛 Fixes & Improvements
* Find Your Friends screen; Places Stores tab; messaging search fixes.
* Cart-tab back-button white screen; cart respects available stock.
* Order share-link error handling; FAQ screen; calendar in Shipping-in-Progress; save/repost icons.

---

# 🚀 Release Notes: Version 3.0.15 (Build 96)

*Play Store: Big seller update — new Store Control center explains every store feature and shows Free/Premium needs, live plan buying with in-app payment, and supporter pricing on products. Shoppers get a new Competitions section with leaderboards, faster photo swiping, better instant-order links, map-based pickup locations, and smoother video and chat fixes.*

## ✨ New Features & Enhancements
* **Store Control:** Central feature management with ON/OFF + Coming Soon + Needs Premium badges and tap-to-open detail sheets.
* **Plans:** Live plan buying with Free / Premium / Premium+ selector, real slot availability, in-app payment and celebration screen after payment.
* **Pricing:** Supporter-only price sellers can set; buyers see it on product and cart.
* **Instant Order Links:** Overhaul with collapsible hero, compact cards, search, custom link names, previous-links history and per-plan limits.
* **Competitions:** New tab in Explore + profiles with live leaderboard tiers.
* **Pickup:** Locations with map preview; plan/limit guardrails (daily post limits, FAQ limits).
* **Photos:** Zero-delay swipe + preloading with position preserved during scroll — fixes white flash.
* **Video:** Feedback videos now play in-app; add-post/add-product previews open fullscreen on tap.

## 🐛 Fixes & Improvements
* Nav bar staying hidden after returning from add/edit product.
* Video sending failure + wrong thumbnail; web product video playback; profile Supported Stores list; manual-order and instant-cart bugs.

---

# 🚀 Release Notes: Version 3.0.14 (Build 95)

*Play Store: Small stability hotfix for chats and post/product headers. No more repeated "Failed to load contacts" popups, plus a tidier title bar.*

## ✨ New Features & Enhancements
* No new features — stability hotfix.

## 🐛 Fixes & Improvements
* Messaging home: silenced noisy "Failed to load contacts" popup.
* Post/product app bar: tightened title padding to stop jitter/clipping.

---

# 🚀 Release Notes: Version 3.0.13 (Build 94)

*Play Store: Smoother full-screen scrolling — the auto-hide navigation from 3.0.11 is now faster, less jumpy, and no longer flickers. Also fixes sideways photo swiping on products and posts.*

## ✨ New Features & Enhancements
* **Scrolling:** Dual-stream scroll approach to kill jank with improved responsiveness (polish for the 3.0.11 auto-hide feature).

## 🐛 Fixes & Improvements
* Nav bar reappearing unexpectedly on scroll pause; nav hiding during scroll bounce/overscroll.
* Product media horizontal swipe broken when auto-hide was active.

---

# 🚀 Release Notes: Version 3.0.12 (Build 93)

*Play Store: New Wave qualification section on stores shows your progress, benefits, and multi-wave support. New celebration screen when you create an instant store, plus fixes for review stars, messaging, and store pages.*

## ✨ New Features & Enhancements
* **Stores:** Wave qualification section with progress, benefits and multi-wave support.
* **Stores:** Celebration screen for instant store creation.
* **Performance:** Store data fetching optimized; account-section spacing cleaned up.

## 🐛 Fixes & Improvements
* Review star icon showing unfilled/incorrect state; messaging home screen issues.

---

# 🚀 Release Notes: Version 3.0.11 (Build 92)

*Play Store: More room for your feed — the top bar and tabs now auto-hide as you scroll for a full-screen browsing experience. Places now shows activity posts in the Posts tab, and signing in takes you straight to your profile.*
*Note: prod-push message says "version 32" — typo; binaries are `3.0.11+92`.*

## ✨ New Features & Enhancements
* **Navigation:** Auto-hide app bar + tab bar that hide on scroll down and return on scroll up, on buyer and seller home.
* **Places:** Posts tab now includes activity posts.

## 🐛 Fixes & Improvements
* Login with OTP now redirects to the user profile tab after sign-in.
* Auto-hide race during buyer/seller view switch.

---

# 🚀 Release Notes: Version 3.0.10 (Build 91)

*Play Store: Smoother everyday use in a bold new black theme. Chats switch tabs cleanly, order lists no longer flicker, notifications land on the right tab instantly, and Places activity now pages correctly.*

## ✨ New Features & Enhancements
* **Theme:** New black app theme; FAQ answers now cached for instant reopen.
* **Messaging & Notifications:** Refreshed messaging screen; unread-notification card + notification-to-tab routing; store cards in Places and category cards restyled.

## 🐛 Fixes & Improvements
* Chat tab-switch bug; "No Orders Yet" flicker in seller orders; notification-open delay; support score not refreshing on pull-to-refresh.

---

# 🚀 Release Notes: Version 3.0.9 (Build 90)

*Play Store: Find things faster with browsable Categories and smarter search, plus dedicated Chat tabs for buyers and sellers with unread badges. Notifications group unread chats, commenting feels snappier, and builds are now smaller to download.*

## ✨ New Features & Enhancements
* **Categories:** Full category view with search for stores + products and category rails in search start-state.
* **Chat:** Own bottom-nav tab for buyers and sellers with badges; unread-messages card in Notifications.
* **Search:** Tab views refreshed; notification UI refreshed; comment composer hides bottom nav; smaller downloads.

## 🐛 Fixes & Improvements
* Guest chat init fixes; bottom-nav redirect after store creation; tab-bar issues in profiles + messaging; review-video aspect ratio.

---

# 🚀 Release Notes: Version 3.0.8 (Build 89)

*Play Store: Under-the-hood trust update. ID verification is now faster and clearer with dedicated flows, sharing a store sends a cleaner message, and test accounts can no longer follow or support by mistake.*

## ✨ New Features & Enhancements
* **Verification:** Refactored store ID-verification flow (separate flows, improved UX).
* **Sharing:** Improved store-share text; app-share messages now updatable without an app release.

## 🐛 Fixes & Improvements
* Test stores blocked from following / supporting users or stores.

---

# 🚀 Release Notes: Version 3.0.7 (Build 88)

*Play Store: Cleaner trust and discovery. The Trust Center and ID verification get a fresh look with Aadhaar support, post headers show comments at a glance, and "View more" behaves consistently everywhere.*

## ✨ New Features & Enhancements
* **Trust Center:** Redesign; ID-verification redesign with new Aadhaar section; post cards get a header view with comments.
* **Discovery:** Store-search UI pass; unified "view more" logic for horizontal lists.

## 🐛 Fixes & Improvements
* Horizontal-to-vertical list navigation fixed in store and user-profile screens.

---

# 🚀 Release Notes: Version 3.0.6 (Build 87)

*Play Store: New step-by-step store setup checklist makes opening a store foolproof — logo, description, contact, location, places, ID and share-link all in one place with live refresh. Places and store search also get lively horizontal rails you can tap through.*

## ✨ New Features & Enhancements
* **Onboarding:** Store setup checklist with mandatory / optional items and bottom-sheets for logo, description, contact, location, places, ID verification and share-link; simplified create-store flow.
* **Discovery:** Horizontal product / post rails in Places and store search with correct Follow status; chat-media thumbnails; trust-center and product-details refresh.

## 🐛 Fixes & Improvements
* Null-crash switching to store profile; checklist-card height mismatch; Supported-stores section; edit-product keeps video ID when unchanged.

---

# 🚀 Release Notes: Version 3.0.5 (Build 86)

*Play Store: Small but visible — photo and video carousels are easier to browse with on-screen arrows and smoother swipes, and help-desk chats now support photo attachments reliably.*

## ✨ New Features & Enhancements
* **Support:** Tickets can now attach photos.
* **Media:** Carousel arrows on post / product views, fade-animation image swiping, video thumbnails in product grids.

## 🐛 Fixes & Improvements
* Request-verification issue fixed.

---

# 🚀 Release Notes: Version 3.0.4 (Build 85)

*Play Store: Easier trust-building for sellers and clearer info for shoppers. New ID-verification document upload, photo uploads for store FAQs, tap-for-details explainers on sales, orders and returns, plus more reliable Instant-Cart link sharing.*

## ✨ New Features & Enhancements
* **Instant Cart:** New link creation + redirect flow; more reliable link sharing.
* **Verification:** ID verification document-upload flow; store FAQ media upload.
* **Stores:** Info bottom-sheets explaining Sales, Orders, Reviews and Returns.
* **UI/UX:** Store access options reordered; order / sale / review info text restyled; transactions UI refreshed.

## 🐛 Fixes & Improvements
* Video flicker entering / exiting fullscreen fixed; edit-product / product-details and preview-store creation bugs fixed.

---

# 🚀 Release Notes: Version 3.0.3 (Build 84)

*Play Store: Makes Instant Cart and store review links just work — including for new users and when switching between buyer and seller accounts. Videos also stop cleanly when you leave the app, and Places scrolls sideways smoothly.*

## ✨ New Features & Enhancements
* **Reviews:** External store-review links now validate and switch accounts correctly; seller → buyer handoff for Instant Cart completed.
* **Places:** Horizontally scrollable strip; Instant-Cart signup flow and quantity handling improved.

## 🐛 Fixes & Improvements
* Feed videos no longer keep playing in the background.

---

# 🚀 Release Notes: Version 3.0.2 (Build 82)

*Play Store: Fixes buying and chatting. The Buy / Buy-at-Store button now behaves correctly and shows pickup options when delivery isn't available, and the chat screen types and opens emoji without losing focus.*

## ✨ New Features & Enhancements
* **Reviews:** Store reviews page shows store icon, name and handle; "Buy Now" shows pickup options when buy is disabled.
* **UI/UX:** Refreshed manual-order, support and post-card icons; stale Buy-Now state refreshes correctly.

## 🐛 Fixes & Improvements
* Buy button not responding — fixed; app now jumps straight to Login on session expiry instead of getting stuck; chat auto-capitalization and emoji/keyboard focus fixed.

---

# 🚀 Release Notes: Version 3.0.1 (Build 82)

*Play Store: Quick polish right after the big 3.0 launch. Sharper store details, smoother photo permissions on Android, and final cleanup of old branding across the app.*

## ✨ New Features & Enhancements
* **UI/UX:** Refreshed store-details UI; Android photo permission flow added.

## 🐛 Fixes & Improvements
* Removed all remaining old branding wording for consistent Swadesic branding.

---

# 🚀 Release Notes: Version 3.0.0 (Build 81)

*Play Store: Biggest update yet — brand-new store and profile designs, faster video-first feeds everywhere, a new Places way to discover stores near you, plus Instant Cart and Manual Orders that let any store sell in seconds. Uploads now finish in the background while you keep browsing.*

## ✨ New Features & Enhancements
* **Stores & Profiles:** New buyer store view, seller dashboard and user profile redesign.
* **Selling:** Instant Cart + Manual Orders with shareable cart links, variant picker, add-external-product flow, deep-link to manual order and seller Manual/App order filters.
* **Discovery:** New Places tab with place chips, cluster feeds, visited stores, manage / reorder places and location-based pickup.
* **Reviews:** Review Pages with create flow, owner vs visitor views, review videos and pending-reviews entry.
* **Products:** Origin & Transparency section on product details.
* **Feeds:** New Feed Engine everywhere — paginated, keeps position on tab switch, smooth autoplay.
* **Video:** New engine with instant play, prefetch + thumbnail caching, background upload and no-restart fixes.
* **UI/UX:** Skeleton loaders replace spinners; frosted bottom nav; 4:5 post media.

## 🐛 Fixes & Improvements
* Orders: status chips with counts, refund breakup for buyer + seller, pincode dialog and shipping toggle fixes.
* Notification tap opens the right screen on cold + warm start.

---

# 🚀 Release Notes: Version 2.4.6 (Build 79)

*Play Store: A fresh new look for our story — clearer onboarding, simpler invites, and shopping that feels direct, safe, and human. We've refreshed wording across welcome, roles, and referrals to focus on buying direct from real stores.*

## ✨ New Features & Enhancements
* **Onboarding:** Rewritten welcome story with intro slides about Direct-from-Store shopping; rewritten "What is Swadesic" and role-choice screens; rewritten Invite/Referral page with buyer and store benefits.
* **UI/UX:** New mission artwork; clearer labels across invites, fulfillment settings and report reasons; simplified share prompt.

## 🐛 Fixes & Improvements
* Settings no longer shows an empty phone/email row; removed outdated link on login support row.

---

# 🚀 Release Notes: Version 2.4.5 (Build 78)

*Play Store: Faster, more reliable photos across shopping and community. Product, post, and comment images now load from new storage for fewer broken images.*

## ✨ New Features & Enhancements
* **Image Management:** Product, post, and comment images load via object storage with updated upload flow and fallbacks.
* **UI/UX:** User and store icons use unified image-URL handling.

## 🐛 Fixes & Improvements
* No user-facing fixes — image reliability release (only 6 commits since 2.4.4).

---

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
