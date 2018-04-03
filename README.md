# photoshare
Project for CS460 database (Written in python2.7)

Use Case Implemented:
* User management
	* Becoming a registered user
	* Adding and Listing Friends
	* User activity  -- get top ten Users
* Album and photo management
	* Photo and album browsing
	* Photo and album creating
* Tag management
	* Viewing your photos by tag name  /view_by_tags
	* Viewing all photos by tag name /view_your_by_tags
	* Viewing the most popular tags
	* TODO: Photo search
* Comment
	* Leaving comments
	* Like functionality
* Recommendations
	* 'You-may-also-like' functionality. // you can search the top five popular tags and search all the photos that has all or part of those tags.
	* TODO:Tag recommendation functionality

Limitations:
* 1. The Photoshare website is local hosted. Need to change password of MySQl before running the website.
* 2. When registering new users, if email is taken, it will return back to register page. In other words, every email can only be registered for one user.
* 3. Users have to create albums before they can upload photos.
