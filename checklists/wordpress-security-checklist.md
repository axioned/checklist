---
title: Wordpress Security Checklist 
category: Back-End
date: "2020-08-07"
tags: ['wordpress', 'security', 'php']
description: Steps we follow ensure our Wordpress installation is secure - staging and production.
featured: true
---

- [ ] Change the login slug  
Change the login slug. To verify this, enter the domain name with `/login` the page should redirect to 404 page and If it opens the login page then your site not secure.

- [ ] Enable two factor authentication  
Enable the two factor authentication to enhance the security for the users logging in.

- [ ] Use strong passwords for login  
Set strongs passwords for the users created. This will prevent hackers from manipulating your password easily.

- [ ] Hide login error messages  
Error login messages may expose your website and give hackers an idea if they've gotten username correct/incorrect, vice versa. It is wise to hide it from unauthorized login. To hide login error messages, simply put the following code in `functions.php`

>function wrong_login() {\
>  return 'Wrong username or password.';\
>}\
>add_filter('login_errors', 'wrong_login')

- [ ] Limit login attempts  
Limit login attempts in order to prevent your site from brute force attack.

- [ ] Block the Rest API  
Block REST API if it is not in use.

- [ ] Manage 301 redirect  
Add 301 redirection for the links requested by the clients.

- [ ] Test for Responsiveness  
Ensure that your website is responsive and mobile ready by running [Google's Mobile Friendly Test](https://search.google.com/test/mobile-friendly)

- [ ] Limit meta title  
Make sure all pages and posts have a unique title, fewer than 70 characters.

- [ ] Limit meta description  
Make sure all pages and posts have unique meta descriptions, fewer than 156 characters.

- [ ] Create robot.txt file  
Allow indexing for only the folder you want to get tracked in the SEO. Deny the indexing for the files with sensitive data.

- [ ] Protect your wp-config file  
As `wp-config.php` file contains all the confidential details of your site, so it’s pretty important that you protect it at all costs.

- [ ] Update htaccess  
Disable access to `/readme.html`, `/license.txt`, and `/wp-admin/install.php"` files and should be redirected to 404 page.

- [ ] Prevent Directory Access  
Prevent your directory from gtting accessed. So accomplish this add the follwoing code in the .htaccess file.

>\# Prevent folder browsing\
>Options All -Indexes

- [ ] Disable Theme and plugin Editor  
Disable file edit via wp-config.php by adding the following code: define('DISALLOW\_FILE\_EDIT',true);

- [ ] Compress Images  
Make sure to reduce all the image sizes by compressing files using WP Smush plugin.

- [ ] Site speed optimization  
Make sure the necessary steps are taken to optimize the site speed.

- [ ] Set correct permissions to file and folders  
For security all the folders should have 755 permission and files should have 644  permission.

- [ ] Setup Weekly Databsae backup  
Make sure to setup DB backupon weekly basis.

- [ ] Disable comments if it is not in used  
Disable the commenting options if that is not used.

- [ ] Scan the website for viruses, malware, and security breaches  
Scan for viruses, malware and security breaches if you find any resolve them.

