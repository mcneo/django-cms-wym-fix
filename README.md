django-cms-wym-fix
==================

Want to use Django CMS and use S3 for your static files; then you'll need a fix for the Wymeditor, otherwise it'll complain about Cross Site Scripting! Get your fix here!

REQUIREMENTS
=================
django-cms==2.3.5

INSTALL
==================
1) pip install this
2) Add to installed apps before the "cms" app
3) ???
4) Profit

I'll update these instructions once I do this myself :)

NOTES
==================
If you have found a better way to get to get around the cross site scripting problem with django-cms and wymeditor, then let me know.

Another more invasive option can be found here: https://gist.github.com/wilburb/1714401

Some other people who ran across this problem: http://grokbase.com/t/gg/django-users/12ab32tpt9/django-cms-wymeditor-heroku-aws-s3-cors

I think it may be fixed here in newer versions of the django-cms: https://github.com/divio/django-cms/issues/1