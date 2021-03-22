# Alan Framework
Alan Framework is a post-exploitation framework useful during red-team activities. 

You can download the binary from: <a href="https://github.com/enkomio/AlanFramework/releases/latest">https://github.com/enkomio/AlanFramework/releases/latest</a>
v2.0 Releasing date: 27/03/2021

Example videos: 

* <a href="https://www.youtube.com/watch?v=oLXYUCX7dVY">Update agent profile at runtime</a>
* <a href="https://www.youtube.com/watch?v=dgEBEAfEseY">Introduction</a>

For more information on its usage please read the <a href="https://github.com/enkomio/AlanFramework/blob/main/doc/Alan%20Documentation%20v2.0.500.23.pdf">documentation</a>.

If you find my tool useful, please consider to <a href="https://github.com/sponsors/enkomio">sponsor me</a>. Sponsored users have access to early releases and non public content.

<a href="https://www.youtube.com/watch?v=dgEBEAfEseY"><img src="https://raw.githubusercontent.com/enkomio/AlanFramework/main/images/Alan%202.0.png"></a>

# Changelog
### 2.0.0 - 20/03/2021
* Implemented agent `detach` command to temporary exit from a current joined agent
* Implemented shell `detach` command to temporary exit from a command shell
* Implemented `listeners` command to list the available listeners
* Implemented HTTPS listener to communicatewith the agent via TLS
* Implemented `get-config` command to download the current agent configuration
* Implemented `update` command to update the agent configuration
* Support from Windows7

### 1.0.0 - 22/02/2021
* First Release
