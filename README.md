# Making a calendar website.

I made a calendar website because I was tired of playing battleship tag when trying to coordinate with my friends. With the calendar, scheduling becomes a constant time operation, I send my calendar and my scheduling partner identifies an availability that works for them. Without it, scheduling has no upper bound.

You may have your own motivations for setting up a calendar website. If you just want to learn how to host a static website for free, skip to that section.

## The Calendar

1. Get your calendar up to date. Make sure to put your working hours and stuff. If you know when you sleep, put that in too.
2. Make your calendar public so other people can see it. Follow this tutorial to [make your calendar public](https://support.google.com/calendar/answer/37083). I recommend setting the visibility to "see free/busy only," so you can keep going to embarrassing events. (When you see the calendar, you'll still see your event titles unless you sign out of google)
2. Follow this tutorial to [Embed a calendar on your website](https://support.google.com/calendar/answer/41207)
  * If you don't care about having a website, you can just follow "Share as a link." Send the link to your friend and you are done. Boom that easy.
4. Once you've copied the embed code, create a new file on your computer called 'index.html' and paste it in there. Save it.
4. Boom, thats the whole website.

##  Easy static website with google cloud.

1. Go buy your hostname. This'll be easier if you buy it [through google](domains.google)
2. Go follow this tutorial for [hosting a static website](https://cloud.google.com/storage/docs/hosting-static-website)
  Double check that you: 
   * Made your index.html file public
   * Assigned index.html as your specialty index page
3. At the end of that tutorial you can still only get to your website with that www at the front. You need to make an alias to fix that. 
   1. [My Domains](domains.google.com/m/registrar) -> Click your domain name -> DNS -> Synthetic Records
   2. Add a new synthetic record that forwards the subdomain, "@.mydomain.com" to "www.mydomain.com"
   3. Now you can visit just "mydomain.com"
4. Message me your new website so we can hang.
  
  