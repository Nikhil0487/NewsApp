# NewsApp
This is an iOS newsfeed and top headlines app written in Swift and based on NewsAPI.

## About 
I wanted to have my own one stop custom newsfeed/top-headlines app. I felt I was missing on some categories of news like Economy. So, I built this app as a Do-It-yourself(DIY) project to keep me uptodate.

## Design
1. MVVM architecture,
2. Storyboard based,

## Interface
1. Search for custom query,
2. Select from News API supported predefined categories for top headlines,

<pre>
<img src=screenshots/Launch-Screen.png height=500, width=250>     <img src=screenshots/News-Items.png height=500, width=250>      <img src=screenshots/New-Fetch-Fail.png height=500, width=250>

<img src=screenshots/News-Feed.png height=500, width=250>     <img src=screenshots/Web-View.png height=500, width=250>      <img src=screenshots/News-Uptodate.png height=500, width=250>
</pre>

## TODO
- [ ] Support for different search combinations
- [x] Page support if news items are more than 20 items
- [x] Refresh support for news feed 
- [ ] Saving search history locally
- [ ] Adding news sources list supported by News API
- [x] SFSafariViewController with page navigation, bookmark and open in browser support

## Problems To Be Solved
- [ ] News categories listed in the app belong to a particular country (i.e., India). Can an option to select a country (or none at all) be given somewhere? 
## Credits
This is my first iOS app. 
1. This app has huge improvements on a sample app taught in Udemy course https://www.udemy.com/course/mastering-mvvm-for-ios/
2. The app icon was downloaded from internet assuming it was open source, if not i am glad to remove it,
3. The News API key is used and pushed to this repo considering that this project is open source and will remain so.
