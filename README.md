# TrustScript - AI-Assisted Reviews for WooCommerce

Transform your WooCommerce product reviews with AI-powered content generation. TrustScript helps customers express their genuine experiences by generating professional review variations based on their input, making it easier to collect authentic, high-quality feedback.

## 🚀 Key Features

*   **AI-Powered Review Generation:** Customers write a simple review, and AI generates professional variations in different tones.
*   **Automated Review Requests:** Automatically sends review requests when an order reaches a specific status (e.g., "Delivered").
*   **Smart Timing:** Configurable delay ensures reviews are requested when customers have actually had time to use the product.
*   **TrustScript Verified Badge:** Adds a verification badge to reviews collected through the platform, enhancing credibility.
*   **Immutability:** Reviews published via TrustScript are locked from editing to maintain authenticity and customer trust.
*   **Auto-Sync:** Daily automatic synchronization ensures no orders are missed, even if the initial trigger fails.
*   **Analytics Dashboard:** Track review requests, approval rates, pending reviews, and conversion metrics directly from your WordPress admin.
*   **Media Support:** Backend support for handling photo and video uploads with reviews. (Coming in future updates)
*   **White-Label Branding:** (Pro/Business Plan) Customize review pages with your logo, colors, and domain.

## 📋 Requirements

*   WordPress 6.2 or higher
*   WooCommerce 8.0 or higher
*   PHP 7.4 or higher
*   TrustScript Account (Free or Paid)

## 🔧 Installation

1.  **Upload:** Upload the `trustscript` folder to the `/wp-content/plugins/` directory.
2.  **Activate:** Activate the plugin through the 'Plugins' menu in WordPress.
3.  **Sign Up:** Create a free TrustScript account at [https://nexlifylabs.com](https://nexlifylabs.com).
4.  **Get API Key:** Retrieve your API key from your TrustScript dashboard.
5.  **Connect:** Navigate to **TrustScript > Settings** in your WordPress admin and enter your API key.

## ⚙️ Configuration

### General Settings
Go to **TrustScript > Settings** to configure the core connection.
*   **API Key:** Enter your TrustScript API key here.
*   **Base URL:** Automatically detected, but can be overridden if necessary.

### Review Settings
Go to **TrustScript > Review Settings** to control how and when reviews are requested.
*   **Enable Review Requests:** Toggle this on to start sending requests.
*   **Trigger Status:** Select the order status that triggers the review request (default: `delivered`).
*   **Delay:** Set a delay (in hours) between the order reaching the trigger status and the email being sent.

### Branding (Business Plan)
Go to **TrustScript > Branding** to customize the look and feel.
*   **Logo:** Upload your store's logo.
*   **Colors:** Match the review request emails and pages to your brand identity.

### Email Template
Go to **TrustScript > Email Template** to customize the email sent to customers.
*   **Subject:** Set the email subject line.
*   **Body:** Customize the message using placeholders like `{customer_name}`, `{product_name}`, and `{review_link}`.

## 🛠️ How It Works

1.  **Order Completion:** A customer places an order on your WooCommerce store.
2.  **Trigger:** When the order status changes to "Delivered" (or your configured status), TrustScript schedules a review request.
3.  **Request Sent:** After the configured delay, an email is sent to the customer with a unique link.
4.  **AI Assistance:** The customer clicks the link, writes a draft, and TrustScript's AI generates polished variations.
5.  **Submission:** The customer selects their preferred version and submits the review.
6.  **Publishing:** The review is automatically pushed to your WooCommerce store and marked as "Verified Purchase".

## 🔒 Security & Authenticity

*   **Immutability:** To ensure the integrity of reviews, TrustScript locks reviews from being edited after they are published. This prevents manipulation and builds trust with your customers. You can delete reviews if necessary, but you cannot alter their content.
*   **Secure Webhooks:** Communication between TrustScript and your site is secured with API key validation and domain verification.

## ❓ Frequently Asked Questions

**Q: Do I need a TrustScript account?**
A: Yes, you need an account to generate the API key and access the AI features. A free plan is available.

**Q: Does this work without WooCommerce?**
A: No, this plugin is specifically designed to integrate with WooCommerce orders and products.

**Q: Why can't I edit TrustScript reviews?**
A: TrustScript reviews are immutable to guarantee their authenticity. This prevents store owners from altering customer feedback, which increases trust for potential buyers.

**Q: What happens if I deactivate the plugin?**
A: Your existing reviews will remain on your site. However, new orders will not trigger review requests, and the "TrustScript Verified" badge styling may disappear.

**Q: How does the Auto-Sync work?**
A: The plugin runs a daily background task (cron job) to check for any orders that might have been missed by the real-time triggers, ensuring 100% coverage.

## 📄 License

This plugin is licensed under the GPLv2 or later.
