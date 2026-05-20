# PermissionRequest Object

* `requestingUrl` string (optional) - The last URL the requesting frame loaded. This is not available for platform permission requests.
* `isMainFrame` boolean (optional) - Whether the frame making the request is the main frame. This is not available for platform permission requests.
* `isPlatformRequest` boolean (optional) - Whether the request comes from the platform permission flow instead of a `WebContents`.
