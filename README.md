# nbake
nbake home

Old school staticaly generated pug cli, GPL3.

Ex:

	npx nbake .


	npx nbake -i .


	npx nbake -x


There is supper set (Apache 2 license) that allows you to build in the cloud by calling API or using the web admin, a bit like WordPress, here:
 - http://github.com/topseed/nbake-admin


Requires deployment to S3, ex: AWS, Digital Ocean Spaces, S3.
You can use FTP (ex: CyberDuck). Running on non-S3 is not supported.
S3 is big and cheap.


Supports:
- Pug static data binding and dynamic data biniding. 
- Blog | any item.
- Plugins

