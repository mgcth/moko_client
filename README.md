# moko_client
This is the React frontend part of moko. Moko is a separate client (frontend) and server (backend) component to manage camera feeds over the web. Its aims are:
- Be simple and hackable.
- Decouple the client and server, i.e. start a server with connected camera(s) that can accept requests and send responses to a client that can run anywhere (as long as it can connect to the server).
- This means, a simple client app that, in theory, can be hosted on the web and serve any number of users running separate servers. That hosted client should not store any user info. Rather, the user will provide an endpoint to their server and any configurations loaded from there.
- Roll your own authentication on the server, or use the provided JWT authentication.
- Support Raspberry Pi camera modules (V1 and V2).
- Support basic motion detection and object detection.
