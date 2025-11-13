# WHMCS Paystations Payment Gateway

A custom WHMCS payment gateway module that integrates **Paystations** with your WHMCS billing system.  
This module allows your clients to pay invoices securely through Paystations directly from the WHMCS client area.

> ℹ️ Update any sections (version, requirements, fields, etc.) to match your actual implementation.

---

## Features

- Seamless integration with WHMCS payment workflow  
- Redirect-based payment flow (customer is redirected to Paystations for payment)  
- Automatic payment status callback/notification handling  
- Supports multiple currencies (depending on your Paystations account)  
- Configurable test/sandbox mode (if supported by Paystations)  
- Easy installation and configuration

---

## Requirements

- WHMCS **8.x** or later (adjust if your module supports older versions)  
- PHP **7.4+** (or whatever version your server/module requires)  
- Active **Paystations** merchant account  
- API credentials from Paystations (e.g. Merchant ID, API Key/Secret, etc.)

---

## Installation

1. **Download the module**

   Download the latest release ZIP of this repository and extract it.

2. **Upload files to WHMCS**

   Copy the module folder into your WHMCS installation:

   ```text
   /path-to-whmcs/
     modules/
       gateways/
         paystations.php
       gateways/callback/
         paystations.php
