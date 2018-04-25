# nbake
nbake cli home

Mission: Every 10 years or so tech gets 10X better *FORCING* everyone to upgrade! Ex: Assembly is 10x better
than machine. C is 10X better than Assembly. Our mission is: what is 10X better than LAMP used to build WordPress and such. We think we found the answer:

http://nbake.org

Staticaly generated markup, Pug.
Similar to markdown or Haml, or other staticly genererated tools.

We assume that everyone is web litterate, ex:
' Design and Build Websites ' by Jon Duckett

It assumes you'll learn Pug:

- http://youtube.com/watch?v=wzAWI9h3q18


Supports:
- Pug static data binding and dynamic data biniding.
- Blog | any item.
- Plugins ( http://github.com/topseed/nbake-plugins )

You can install via npm (or yarn).

To create a sample app:

		nbake -x

		//and then you can make pug via
		nbake .

It requires meta.yaml in each folder. Ex:

		title = Oh hi
		baseddir = ..


In windows you have to:

	 node $Env:userprofile/WHERE-YOU-INSTALLED/node_modules/nbake/nbake.js .


It internaly uses loadjs, nothing else other than Pug and loadjs is mandatory.

- http://github.com/muicss/loadjs


There is supper set project (Apache 2 license) that allows you to build in the cloud by for using the web admin, a bit like WordPress admin, here:
 - http://github.com/topseed/nbake-admin
Admin super set requires deployment to AWS S3.
You can use FTP (ex: CyberDuck) in nbake cli to deploy to AWS S3 (with an 'IAM' id, key, secret and bucket name). It is recomended that you start using that project as well as soon as you deel comfortable with nbake.


Sample app uses http://semantic-ui.com framework, but you can use any ( http://keycdn.com/blog/front-end-frameworks )


Supports native appstore (IOS, Andorid) https://github.com/topseed/nabke-native-appstore


Source code is here http://github.com/topseed/nbake-src, other nbake projects are here:
- https://github.com/topseed

Feel free to oppen an ticket here for any help.

Commercial support, hosting, training, plugins and conulting is optional, by:
- http://narwhalstar.com
or
- http://wordpug.com
