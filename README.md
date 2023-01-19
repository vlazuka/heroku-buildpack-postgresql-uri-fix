# heroku-buildpack-postgresql-uri-fix

SQLAlchemy 1.4 (and newer versions) removed the deprecated `postgres` dialect name, the name `postgresql` must be used instead now. The dialect is the part before the `://` in the URL.

To fix this, rename `postgres://` in the URL to `postgresql://` or download this buildpack which is going to do everything automatically.

