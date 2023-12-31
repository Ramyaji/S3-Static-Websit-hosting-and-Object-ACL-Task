# S3-Static-Website-hosting-and-Object-ACL-Task
Create s3 Bucket make it public and object lock enable
go to properties-> Enable static website hosting-> index.html error.html configured
now upload index.html and error.html make these objects public (enabled Object ACL)
copy static website url and browse you can access site
copy same url and try  browse in android by default it load https and no longer loaded
so remove s from https->http
http://static-chinni-website.s3-website.us-east-2.amazonaws.com/
