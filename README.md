# Sanitizer
- https://pypi.org/project/html-sanitizer/

# Reflected xss
- Before calling self._SendError we will sanitize the invalid path or we can use the :text in error.gtl

# Stored xss
- we are going to replace gureye sanitizer with a better one


# XSRF
- we are going to implement anti-csrf tokens that is server going to be verifying on every request.
- Additionally Origin/Referer and some custom http headers could potentially help us determine if the request was sent from different site or not. While this is not going to be foolproof in some cases it might help.
