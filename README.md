# Freshworks Paid Apps Workshop - Chennai

Welcome to the Freshworks Paid Apps Developer Workshop! This hands-on workshop will guide you through building apps for the Freshdesk platform using the Freshworks App SDK v3.0.

## About This Workshop

This workshop provides a progressive, step-by-step learning experience for building Freshworks marketplace apps. You'll learn essential concepts of the Freshworks Developer Platform, from basic app structure to integrations with external services.

### What You'll Build

Throughout this workshop, you'll create increasingly sophisticated apps:

1. **First App** - A simple ticket sidebar app that displays requester information
2. **Multi-Placeholder App** - An app that appears in multiple locations across Freshdesk
3. **Full Page App** - Advanced apps with full-page views 
4. **Shopify Integration App** - A real-world integration connecting Freshdesk with Shopify

## Prerequisites

Before starting this workshop, ensure you have:

- **Node.js** v18.20.8 or higher
- **Freshdesk Trial Account** - [Sign up for free](https://developers.freshworks.com/signup/)
- **Code Editor** - VS Code recommended
- **Basic Knowledge** of HTML, CSS, and JavaScript

## Getting Started

Follow the comprehensive setup guide to prepare your development environment:

**👉 [Getting Started Guide](./apps/getting_started.md)**

This guide covers:
- Installing the FDK CLI
- Setting up your Freshdesk trial account
- Configuring your development environment
- Running your first app locally

## Workshop Apps

### 1. First App - Ticket Sidebar
**📁 Location:** [`apps/first_app`](apps/first_app/)

Your introduction to Freshworks app development. This simple app displays the ticket requester's name in the ticket sidebar.

**What You'll Learn:**
- Basic app structure and files
- Manifest.json configuration
- Using the Data API to fetch ticket data
- Handling the `app.activated` event

**[📖 View Documentation    →](apps/first_app/README.md)**

---

### 2. Placeholder App - Multi-Location Support
**📁 Location:** [`apps/placeholder_app`](apps/placeholder_app/)

Learn how to make your app available in multiple locations across Freshdesk.

**What You'll Learn:**
- Configuring multiple placeholders in one app
- Module architecture (support_ticket, support_contact, common)
- Creating placeholder-specific views
- Context-aware data fetching

**Placeholders:**
- Ticket Sidebar
- Ticket Requester Info
- Contact Sidebar
- Full Page App
- CTI Global Sidebar

**[📖 View Documentation →](apps/placeholder_app/README.md)**

---

### 3. Full Page Placeholder App
**📁 Location:** [`apps/full_page_placeholder`](apps/full_page_placeholder/)

Build immersive full-page applications.

**What You'll Learn:**
- Creating full-page applications
- Using the common module for global access
- Configuring external API requests with requests.json

**Special Features:**
- Dedicated full-page workspace
- Always-accessible CTI sidebar
- External API configuration
- Advanced placeholder usage

**[📖 View Documentation →](apps/full_page_placeholder/README.md)**

---

### 4. Shopify Integration App (Optional)
**📁 Location:** [`apps/sf-integration`](apps/sf-integration/)

A real-world example integrating Freshdesk with Shopify.

**What You'll Learn:**
- Secure external API requests
- Working with e-commerce data

## Additional Resources

### Official Freshworks Resources
- [Freshworks Developer Portal](https://developers.freshworks.com/)
- [App SDK v3.0 Documentation](https://developers.freshworks.com/docs/app-sdk/v3.0/)
- [Freshdesk App Locations](https://developers.freshworks.com/docs/app-sdk/v3.0/freshdesk/app-locations/)
- [Data API Reference](https://developers.freshworks.com/docs/app-sdk/v3.0/freshdesk/data-api/)
- [Freshworks Crayons v4](https://crayons.freshworks.com/) - UI Component Library

### Community
- [Freshworks Developer Community](https://community.developers.freshworks.com/)
- [Sample Apps Repository](https://community.developers.freshworks.com/t/freshworks-sample-apps/3604)
- [Developer Forum](https://community.developers.freshworks.com/)


## Support

If you have questions during the workshop:
1. Refer to the app-specific README files
2. Check the [documentation resources](#additional-resources)
3. Ask the workshop facilitators
4. Post in the [Developer Community](https://community.developers.freshworks.com/)

---

**🚀 Ready to start? Head over to the [Getting Started Guide](./apps/getting_started.md)!**
