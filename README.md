# Guide to Using the WordPress REST API in Python

Imagine you have a huge WordPress blog — massive, packed with content, years of publishing, a growing community and increasing traffic. You’ve added new categories, refined your tags, and your SEO efforts have paid off: your site ranks high on Google. Nice job!

But now, something unexpected comes up. Maybe you need to reorganize your categories, locate specific posts by publication date, or restructure parts of your site.

Manually reviewing every piece of content? A nightmare.

Here’s where **Python and the WordPress REST API come to the rescue**. Let’s start with a simple challenge:

## 🎯 Challenge accepted | Goal

Generate a complete, structured dataset of all published blog posts from a WordPress site, including:

* Title  
* URL  
* Publication date  
* Categories  
* Tags  

---

## 💻 Requirements

* Python  
* Libraries: `requests`, `pandas`  

---

## 📒 Notes

* To use the API, you'll need access credentials. Instead of using your main password, we’ll create a **temporary "application password"** just for this script.  
To generate it:  
  1. Go to your WordPress admin panel  
  2. Navigate to **Users > Profile**  
  3. Scroll down to **Application Passwords**, generate one and copy it  
  4. Run the script, then **revoke** the password. Safe and done!

* The WordPress REST API has **pagination limits** (100 items per page). This affects not only the number of posts retrieved, but also categories, tags, etc. These limitations are handled in the code.

---

Happy automating! 🔧📝
