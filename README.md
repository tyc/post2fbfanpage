# post2fbfanpage
I started out the write some scripts to allow me to automatically post some stories onto a Facebook fanpage. 

My main source of inspirations is located at

http://nodotcom.org/python-facebook-tutorial.html

However, this instructions are quite old. The following stackoverflow page has better details

http://stackoverflow.com/questions/8231877/facebook-access-token-for-pages

The permissions for Facebook indicates that for an application to post stories, it must have permissions of manage_pages and publish_pages.

https://developers.facebook.com/docs/facebook-login/permissions/#reference-manage_pages

The permission of manage_pages is on default and is essentially an read-only access. The publish_pages permission is more difficult to get. publish_pages permission gives your app the ability to post, comment and like as any of the Pages managed by a person using your app.

https://developers.facebook.com/docs/facebook-login/permissions/#reference-publish_pages 

You will need to submit some items for review. As part of the submission, reasons must be given. One of the reasons why it is not allow is

**Automatically publish stories without the person being aware or having control.**

So I am not entirely sure if Facebook will give the necessary permission. Maybe if it is posted as an individual, it may be easier as they is a name to the poster.