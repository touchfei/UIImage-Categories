# UIImage Categories
## About
UIImage Categories is a fork of Trevor Harmon's category methods for cropping and resizing UIImage objects in iOS. Read more on [his 2009 blog post on the subject](http://vocaro.com/trevor/blog/2009/10/12/resize-a-uiimage-the-right-way/):

>Despite its ease of use, or perhaps because of it, UIImage suffers from some serious limitations. Key among these is its lack of support for resizing the image, a feature that is normally handled dynamically by its companion, the UIImageView component. However, should an iPhone application need to reduce the size of an image for storage or for exchange with an external entity (such as a web server), the UIImage class is insufficient.

This fork includes several fixes for compiler warnings and drawing bugs which have surfaced in newer versions of the iOS SDK.

## Contributing
PRs are welcome, but please include some test images to demonstrate what's being fixed. That way I can test against  regressions when merging future changes!
