# Salesforce Web-To-Lead with WordPress (Compatible with Cornerstone)

## Author
This script was developed by **Gustavo Azevedo** and **CASPTI**.  
If you need support or would like to connect, feel free to reach out through the links below:  

- E-mail: azevedosgustavo@gmail.com
- GitHub: [https://github.com/azevedosgustavo]  

---

## Purpose of the Script
The purpose of this code is to enable reliable integration of **Salesforce Web-To-Lead** within **WordPress**, especially when the site uses **Cornerstone** or other page builders that manipulate the DOM.  

The script ensures that the hidden field `captcha_settings` is correctly updated with the timestamp (`ts`), avoiding common issues with **Google reCAPTCHA** validation and guaranteeing that leads are successfully submitted to Salesforce.  

---

## Benefits
- Full compatibility with WordPress and Cornerstone.  
- Prevents issues with sending `captcha_settings`.  
- Automatic real-time timestamp update.  
- Lightweight code in pure JavaScript, with no dependencies.  
- Easy implementation through the WPCode plugin (Shortcode mode).  

---

## How to Use
1. Install the [WPCode](https://wordpress.org/plugins/insert-headers-and-footers/) plugin in WordPress.  
2. Create a new snippet in **Shortcode** mode.  
3. Paste the code available in this repository.  
4. Replace the placeholder values:  
   - `xxxxORGIDxxxx` → Your Salesforce Organization ID  
   - `xxxxRetURLxxxx` → Redirect URL after form submission  
   - `xxxxDataSiteKeyxxxx` → Google reCAPTCHA Site Key  
   - `xxxxKeyNamexxxx` → ReCAPTCHA Key Name in Salesforce  
5. Use the shortcode on the page where you want the form to appear.  
