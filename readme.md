# Example Blogsite

This site is an example webproject for zyniac. It can be run by any webserver but it has extra features on zyniac. This website works only on clientside and doesn't need any backend language like php.

## Adding a Blog
A blog can be added by creating a subdirectory (a subdirectory indicates a new blog) in the ``site_content`` folder. 
3 files are required in a blog. The first file is the blog itself. The Website supports markdown so it is recommended to create a markdown file. The second file is the thumbnail. The third and most important file is the define file. It shows where the website can find the blog and the thumbnail and shows some extra information. This must have the name ``min.json``.

Here is an example how a min.json could look like:

```json
{
	"Title": "Example",
	"Description": "Example Description",
	"Picture": "titlepicture.jpg",
	"BlogSrc": "blog.md",
	"WrittenBy": "Bl4ckL1ght"
}
```

## Register a Blog
Lastly you need to register the blog folder. By adding the folder name into the blogs.json list the blog will get public and can be seen by every person.
