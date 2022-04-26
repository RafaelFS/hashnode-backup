## Hashnode Backup shortcomings (and the alternative)

One of the things I was most excited about the Hashnode platform was the option to back everything up in Github automatically. This essentially would allow me to "eject" from the platform at any time.

This auto backup is found on the "Backup" section, on the sidebar of your blog dashboard. You simply install a Github App and, every time you publish, the blog post should be saved as a markdown file on the selected repository.

## The disappointment

But I found it to fall a little bit short from my expectations. Mostly because:
- The filename is a hash (or an id?). So you cannot tell with a glance which post is which.
- I expected any tags/metadata to be saved as [front matter](https://jekyllrb.com/docs/front-matter/) on the file. But it only saves the content.

Nothing big, it still serves my purposes. But could be better. Especially because it has something VERY similar to what I wanted.

## The alternative

Hashnode has another flow that is different, but could solve the problems listed above. 

If, on your blog dashboard sidebar, you go to the "Integrations" section, along with all the possible analytics integrations you should see one called "Publish articles from GitHub".

This is much closer to the experience I wanted: the posts are markdown files as well, but all the metadata is stored inside the post as front matter. It basically is what I envision the future of this blog will be, when using a static site generator, but without the build tooling.

What changes is that the sync is the other way around: Hashnode fetchs the information from the repository. So all the authoring experience must be done outside of the platform.

The catch: I have grown to really like the authoring experience on Hashnode, especially with the drafts being autosaved. But I may do the change while I still have a manageble amount of posts.

PS: Sorry about the lack of images. I am still bikeshedding on the best way to host images on this blog 🤦. 