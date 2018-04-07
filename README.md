# Choosing And Installing Plugins

## Description

In this lesson you will learn about the almost 35,000 free plugins in the [official WordPress.org Plugin Directory](https://wordpress.org/plugins "WordPress Plugin Directory"), as well as thousands more in the commercial space. This lesson will give you the tools needed to thoroughly evaluate, install, and choose the most appropriate plugin(s) for your site(s) along with resources on how to get help with plugins.  

## Objectives

After completing this lesson, you will be able to:

*   Identify how to activate the default plugins, Akismet and Hello Dolly.
*   Install plugins automatically from the WordPress Plugin Directory or from a provided zip file.
*   Demonstrate how to leave a star rating and review for a plugin.
*   Demonstrate how to search for and create a new topic in the plugin support forum.

## Prerequisite Skills

You will be better equipped to work through this lesson if you have experience in and familiarity with:

*   Basic [WordPress Administration](https://make.wordpress.org/training/handbook/user-lessons/basic-wordpress-concepts/)

## Assets

*   Presentation Slides
*   [Pinkify It Plugin](https://downloads.wordpress.org/plugin/pinkify-it.zip)

## Screening Questions

*   Do you want to add functionality to your WordPress website?
*   Do you have a WordPress.org account?
*   Is there something special you would like to do with your WordPress website?

## Teacher Notes

*   The lesson should alternate between short lectures and live demos. You as the teacher need a working local WordPress installation for the demos, as well as an internet connection to install new plugins.
*   With the exceptions of the exercises, students should not be working on their site during lectures and demos. Questions from students will be very specific to their case, so it’s better to plan a period where they can test things on their site and you answer their questions individually.
*   The WordPress Account and internet access will be necessary to provide feedback on plugins, as well as get help in the plugin's support forums on WordPress.org.
*   **Time estimate:** 1 hour

## Hands-on Walkthrough

### Introduction

In this hour long session, we will walk through the two basic plugins that come with WordPress, Akismet and Hello Dolly. We'll also cover how to find and install a new plugin through the dashboard, how to evaluate a new plugin for use on your site, how to provide feedback and how to get help with a plugin through the WordPress.org support forums.

### What is a Plugin and What Can They Do?

![plugin_directory](/images/plugin_directory.png)

**[Plugins](http://codex.wordpress.org/Plugins)** are ways to extend and add to the functionality that already exists in **WordPress**. The core of **WordPress** is designed to be lean and lightweight, to maximize flexibility and minimize code bloat. **Plugins ** offer custom functions and features so that each user can tailor their site to their specific needs. 

> ![](https://raw.githubusercontent.com/wptrainingteam/contributor-resources/master/images/icon-idea.png) What is the difference between a theme and a plugin? It is common to find cross-over between features found in themes and plugins. However, best practices are:

*   a theme controls the presentation of content; whereas
*   a plugin is used to control the behavior and features of your WordPress site.

> Any theme you create should not add critical functionality. Doing so means that when a user changes their theme, they lose access to that functionality. For example, say you build a theme with a portfolio feature. Users who build their portfolio with your feature will lose it when they change themes. By moving critical features to plugins, you make it possible for the design of your website to change, while the functionality remains the same.[/tip]

### Examples of Types of Plugins

![browsing-plugins](/images/browsing-plugins.png) 

Plugins provide a wide variety of functionality to your WordPress site that does not exist in the WordPress core application. Some examples of different types of plugins include:

*   SEO
*   Backup
*   Security
*   Sliders and Galleries
*   Bulletin Board Forum/Social Network
*   API Plugins (Twitter, Instagram, Flickr, etc.)
*   Tutorials

### Default Plugins: Akismet and Hello Dolly

![default-plugins](/images/default-plugins.png) 

There are two plugins that come with WordPress by default: [Akismet](https://wordpress.org/plugins/akismet/), an anti-spam plugin, and [Hello Dolly](https://wordpress.org/plugins/hello-dolly/), an example of a really simple plugin. Akismet checks your comments against the Akismet Web service to see if they look like spam or not and allows you review the spam it catches under your blog's "Comments" admin screen. When Hello Dolly is activated, you will randomly see a lyric from "Hello, Dolly", as famously sung by Louis Armstrong, in the upper right of your admin screen on every page.

*   Go to Plugins from the Dashboard menu.
*   Locate "Akismet", and click on the "Activate" link below the name.
*   Follow the prompts to activate your Akismet account.
*   Once activated with your Akismet key, your blog will be protected from spam comments.
*   Go to Plugins from the Dashboard menu.
*   Locate "Hello Dolly", and click on the "Activate" link below the name.
*   Once activated, you will see a lyric from the song.

### Evaluating New Plugins

![evaulating-plugins](/images/evaulating-plugins.png) 

The [WordPress Plugin Directory](https://wordpress.org/plugins/) is the best and safest place to get free plugins. All plugins have been reviewed and approved per the plugin guidelines as outlined in [Writing a Plugin](http://codex.wordpress.org/Writing_a_Plugin). When evaluating new plugins for use on your site, it is important that you locate and review the below standard information provided for each plugin in the WordPress Plugin Directory. Plugins may also be purchased through other sources, make sure to thoroughly research outside plugins yourself as they may not follow the same safe guidelines that the WordPress Foundation uses to screen the plugins that they make available.

*   Star Rating
*   Last Updated
*   Number of Downloads
*   Compatibility Rating
*   Author Information & other plugins
*   Support Forums

### Automatically Installing a Plugin from the Plugin Directory

![install-plugin](/images/install-plugin.png) 

The [WordPress Plugin Directory](https://wordpress.org/plugins/) is the best and safest place to get free plugins. Before installing a new plugin, it is a best practice to make a full backup of your website, as some plugins could cause your site to become inoperable. See [WordPress Backups](http://http://codex.wordpress.org/WordPress_Backups).

*   Go to **Plugins > Add New** on the Dashboard menu
*   Search for the plugin name or type, or browse one of the categories or tags.
*   Review the standard information: last updated, number of downloads, compatibility, etc.
*   If you decide to install the plugin, click the "Install" button
*   After installing a plugin, it must be activated, click the "Activate" link.

### Installing a Plugin via External Zip File

![upload-plugin](/images/upload-plugin.png) 

When you purchase plugins from vendors outside of WordPress, the author should provide you with a .zip file that can be installed through the Dashboard. Before installing a new plugin, it is a best practice to make a full backup of your website, as some plugins could cause your site to become inoperable. See [WordPress Backups](http://codex.wordpress.org/WordPress_Backups).

*   Download [PinkifyIt Plugin](https://downloads.wordpress.org/plugin/pinkify-it.zip) as a .zip file and save to your desktop
*   Go to **Plugins > Add New** on the Dashboard menu
*   Click on "Upload Plugin" blue button at the top of the page
*   Click the "Choose File" button and browse to the desktop and select the .zip file
*   Click the "Install Now" button, then click on the "Activate" link.

### Troubleshooting Plugins

![wordpress-errors](/images/wordpress-errors.png) 

There may be instances when you activate a new plugin and it breaks your site, i.e. your site will either start acting ‘strangely’, the plugin doesn’t function the way it’s supposed to, or you get the "white screen of death" and you are not able to access your site from the front end or back end. The reasons for that may be a conflict between the  installed plugins or an installed plugin being incompatible with the current WordPress version. 

If that happens don't worry, there are a few common troubleshooting techniques that will allow you to determine the cause of the misbehavior and reverse its effects. For more information, see [Common WordPress Errors](http://codex.wordpress.org/Common_WordPress_Errors).

### Providing Feedback, Reviews, and Ratings

![reviews](/images/reviews.png) 

The best way to improve and help plugin authors make better plugins is to provide feedback by leaving a review and a star rating.

1.  Go to the Plugin Directory located at https://wordpress.org/plugins/
2.  Sign in on the upper top-right with your WordPress.org credentials
3.  Search for the plugin name that you would like to leave feedback for or get help with.
4.  If you need help or have a problem with a plugin, click on the "View support forum" green button on the right side of the plugin listing.
5.  To leave a star rating, you must also leave a review. Locate on the right side where it says, "My Rating" and click on the stars below. A form will be presented with information to leave a review and a star rating on that plugin.

### Getting Help in the WordPress.org Plugin Support Forums

![support](/images/support.png) 

Each plugin in the WordPress Plugin Directory has a support forum to ask questions about using or configuring the plugin. Please be courteous and thorough when posting questions, as the plugin author is a volunteer and may have other priorities.

1.  Go to the Plugin Directory located at https://wordpress.org/plugins/.
2.  Sign in on the upper top-right with your WordPress.org credentials.
3.  Search for the plugin name that you would like to get help with.
4.  Click on the "View support forum" green button on the right side of the plugin listing.
5.  Before posting a new topic, be sure to [search](https://wordpress.org/search/) to see if one has been started already.
6.  If not, scroll to the bottom of the page and set a good title, select your WordPress version, then describe your issue in the message area with as many details as possible.
7.  Never put password or login credentials in a public forum.
8.  Be patient, if you have not gotten a response in a few days, try rewording your issue or adding information about what you have done to resolve the issue.

## Exercises

*   Activate and Configure Akismet
*   Activate Hello Dolly and refresh admin screen to view
*   Install a plugin from the Plugin Directory
*   Install Pinkify It plugin from the provided .zip file
*   Favorite a plugin, view favorited plugins
*   Leave a star rating and review for a plugin that the student has installed

## Quiz

**What can plugins do?**

1.  Backup your website
2.  Protect you from spam and other security threats
3.  Add more widgets to add to your sidebars
4.  Pull in data from other social media sites
5.  All of the above

Answer: 5\. All of the above.   **When looking for plugins in the WordPress Plugin Directory, what information should you pay attention to?**

1.  Star rating
2.  Last updated
3.  Number of downloads
4.  Author information
5.  All of the above

Answer: 5\. All of the above. **What should you do BEFORE installing a new plugin?**

1.  Leave a star rating and review for the plugin
2.  Backup your site files and database
3.  Deactivate all other plugins
4.  Activate the default theme

Answer: 2\. Backup your site files and database. **What should you do AFTER installing a new plugin?**

1.  Leave a star rating and review for the plugin
2.  Backup your site files and database
3.  Deactivate all other plugins
4.  Activate the default theme

Answer: 1\. Leave a star rating and review for the plugin. **Besides installing the plugin, what do you need to do to run a new plugin?**

1.  Reboot your computer
2.  Activate, then configure the plugin
3.  Restart the web server
4.  Register your plugin with the Author

Answer: 2\. Activate, then configure the plugin.

## Additional Resources

1.  [Managing Plugins](https://codex.wordpress.org/Managing_Plugins) @ Codex
2.  [Plugins](https://codex.wordpress.org/Managing_Plugins) @ Codex
