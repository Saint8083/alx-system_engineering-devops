# Running Gunicorn

You can run Gunicorn by using commands or integrate with popular frameworks like Django, Pyramid, or TurboGears. For deploying Gunicorn in production see Deploying Gunicorn.

# Commands
After installing Gunicorn you will have access to the command line script gunicorn.

gunicorn
Basic usage:

$ gunicorn [OPTIONS] [WSGI_APP]
Where WSGI_APP is of the pattern $(MODULE_NAME):$(VARIABLE_NAME). The module name can be a full dotted path. The variable name refers to a WSGI callable that should be found in the specified module.
