Forked from [scottfalkingham/facebook-rss-parser](https://github.com/scottfalkingham/facebook-rss-parser), with one exception: <images>. This node contains a direct link to the image in the post.

Facebook API Setup
-------------
First, head to https://developers.facebook.com, sign in/up, and create a new app at https://developers.facebook.com/apps/

From the app, you'll need the App ID and App Secret.

PHP Setup
-------------
Rename config.php-dist to config.php. 

Next, open config.php in the text editor of your choice, and place your newly created app id/secret where appropriate, and a few lines below that, your facebook page id as a fallback incase it isn't passed in for whatever reason. Save the file and upload all the files to your webhost.

