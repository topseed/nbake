# nbake
nbake cli home

Mission: Every 10 years or so tech gets 10 times better *FORCING* everyone to upgrade. Assembly was 10 times better than machine. C is 10 times better than Assembly. Our mission is to deliver what is 10 times better than LAMP, the technology WordPress was built on. We believe that we found the answer:

http://nbake.org

It uses statically generated markup, Pug.
Similar to Markdown or Haml, or other staticly genererated tools.

The extra power of nbake can be used to 'tell the story better', by being more interactive in your UX. The better UX translates to more user engamgnet and more user retention.

We assume that everyone is web literate, for example:
' Design and Build Websites ' by Jon Duckett

We also assume that you will learn Pug:

- http://youtube.com/watch?v=wzAWI9h3q18


Nbake supports:
- Pug static and dynamic data binding
- Blog | any item
- Plugins ( http://github.com/topseed/nbake-plugins )

You can install via npm (or yarn).

To create a sample app:

		nbake -x

		//and then you can make pug via
		nbake .

It requires meta.yaml in each folder. For example:

		basedir : ..
		title : Oh hi


In windows you have to:

	 node $Env:userprofile/WHERE-YOU-INSTALLED/node_modules/nbake/nbake.js .

If you are using a Powershell terminal, you can repeat previous commands with [Cursor-Up], and get that command back when you need it.

The nbake examples use loadjs. No other technology than Pug and loadjs is mandatory.

- http://github.com/muicss/loadjs


There is superset project (Apache 2 license) that allows you to build in the cloud by for using the web admin, a bit like WordPress admin, here:
 - http://github.com/topseed/nbake-admin
Admin superset requires deployment to AWS S3. Here is the link to S3 deployment:
- http://github.com/topseed/nbake-user/blob/master/S3.md
While admin module is recommended, it is strongly recommened that you host on S3 anyway - cost is cheap for one, and no http server.

You can use FTP (ex: CyberDuck) in nbake cli to deploy to AWS S3 (with an 'IAM' key, secret and bucket name).
It is recommended that you start using the admin project as soon as you feel comfortable with nbake and S3.

The sample app uses http://semantic-ui.com framework, but you can use any ( http://keycdn.com/blog/front-end-frameworks )


Nbake supports native appstore (IOS, Andorid) https://github.com/topseed/nbake-native-appstore


Source code is here http://github.com/topseed/nbake-src, other nbake projects are here:
- https://github.com/topseed

Feel free to oppen an ticket here for any help.

Commercial support, hosting, training, plugins and consulting are provided by:
- http://narwhalstar.com
or
- http://wordpug.com

Note that admin is Apache license, and you to could/should consider supporting it.
