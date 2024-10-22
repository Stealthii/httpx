# Developer Interface

## Helper Functions

!!! note
    Only use these functions if you're testing HTTPX in a console
    or making a small number of requests. Using a `Client` will
    enable HTTP/2 and connection pooling for more efficient and
    long-lived connections.

::: httpx.request
    options:
        heading_level: 3

::: httpx.get
    options:
        heading_level: 3

::: httpx.options
    options:
        heading_level: 3

::: httpx.head
    options:
        heading_level: 3

::: httpx.post
    options:
        heading_level: 3

::: httpx.put
    options:
        heading_level: 3

::: httpx.patch
    options:
        heading_level: 3

::: httpx.delete
    options:
        heading_level: 3

::: httpx.stream
    options:
        heading_level: 3

::: httpx.Client
    options:
        members:
            - headers
            - cookies
            - params
            - auth
            - request
            - get
            - head
            - options
            - post
            - put
            - patch
            - delete
            - stream
            - build_request
            - send
            - close

::: httpx.AsyncClient
    options:
        members:
            - headers
            - cookies
            - params
            - auth
            - request
            - get
            - head
            - options
            - post
            - put
            - patch
            - delete
            - stream
            - build_request
            - send
            - aclose

::: httpx.Response
    options:
        members:
            - status_code
            - reason_phrase
            - http_version
            - url
            - headers
            - content
            - text
            - encoding
            - is_redirect
            - request
            - next_request
            - cookies
            - history
            - elapsed
            - raise_for_status
            - json
            - read
            - iter_raw
            - iter_bytes
            - iter_text
            - iter_lines
            - close
            - next
            - aread
            - aiter_raw
            - aiter_bytes
            - aiter_text
            - aiter_lines
            - aclose
            - anext

::: httpx.Request
    options:
        members:
            - method
            - url
            - content
            - headers
            - cookies

::: httpx.URL
    options:
        members:
            - scheme
            - authority
            - host
            - port
            - path
            - query
            - raw_path
            - fragment
            - is_ssl
            - is_absolute_url
            - is_relative_url
            - copy_with

::: httpx.Headers
    options:
        members:
            - __init__
            - copy

::: httpx.Cookies
    options:
        members:
            - jar
            - extract_cookies
            - set_cookie_header
            - set
            - get
            - delete
            - clear
