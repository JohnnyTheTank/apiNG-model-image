Universal **_IMAGE_** [model](https://aping.readme.io/docs/models) for [apiNG](https://github.com/JohnnyTheTank/apiNG)

# Supported apiNG Plugins
- [x] **Facebook** ([apiNG-plugin-facebook](https://github.com/JohnnyTheTank/apiNG-plugin-facebook))
- [x] **Tumblr** ([apiNG-plugin-tumblr](https://github.com/JohnnyTheTank/apiNG-plugin-tumblr))
- [x] **Twitter** ([apiNG-plugin-codebird](https://github.com/JohnnyTheTank/apiNG-plugin-codebird))
- [x] **Flickr** ([apiNG-plugin-flickr](https://github.com/JohnnyTheTank/apiNG-plugin-flickr))


# JavaScript
```JavaScript
var image = {
    platform: undefined, //NAME of platform ( "flickr" / "facebook", "instagram" , ...)
    blog_name: undefined, //NAME of blog (channel / facebook page, instagram account, ..)
    blog_id: undefined, //ID of blog (channel / page / account, ...)
    blog_link: undefined, //link to blog (channel / uploader / page / account, ...)
    timestamp: undefined, //timestamp of created_at
    date_time: undefined, //datetime of created_at
    post_url: undefined, //URL to the post / video / tweet ...
    intern_id: undefined, // INTERN ID of image (facebook id, instagram id, ...)
    caption: undefined, //image title
    text: undefined, //image description
    thumb_url: undefined, // best case 200px (min)
    thumb_width: undefined,
    thumb_height: undefined,
    img_url: undefined, //preview image url (best case 700px)
    img_width: undefined,
    img_height: undefined,
    native_url: undefined, // best quality
    native_width: undefined,
    native_height: undefined,
    source: undefined, //different payload
    comments: undefined, //comments_count
    likes: undefined, //likes_count
    shares: undefined, //shares_count
    position: undefined //position in playlist
};
```

# JSON

```JSON
{
  "platform": false,
  "blog_name": false,
  "blog_id": false,
  "blog_link": false,
  "timestamp": false,
  "date_time": false,
  "post_url": false,
  "intern_id": false,
  "caption": false,
  "text": false,
  "thumb_url": false,
  "thumb_width": false,
  "thumb_height": false,
  "img_url": false,
  "img_width": false,
  "img_height": false,
  "native_url": false,
  "native_width": false,
  "native_height": false,
  "source": false,
  "comments": false,
  "likes": false,
  "shares": false,
  "position": false
}
```