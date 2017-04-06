# Twitter
Unfollow Everyone on twitter,  Very Easy Method to unfollow all you are following <br><br>




Step 1 : Log in to your twitter account.<br><br>
Step 2 : Go to your following list i.e. goto https://twitter.com/following. <br><br>
Step 3 : Keep scrolling to the bottom repeatedly until all list of users you are following is loaded.<br><br>
Step 4 : Open browser console and run the following javascript code : <br><br>
<i>
[].slice.call(document.querySelectorAll('.unfollow-text')).forEach(function(button) {
  button.click();
});
</i>
<br><br>
Note :1) To open console in Firefox press <b>ctrl+shift+K</b> and in Google Chrome press <b>ctrl+shift+J.</b> <br><br>
2)If you have a massive list to unfollow you can do it without loading full list simply load a reasonable number of user once and repeat it.
<br> <br>
ENJOY :)


