# WebAuth-term

When guests, contractors or employees connect to the enterprise network, they may not be able to use 802.1X authentication. An identity-based authentication that can be used in these cases is Web Authentication (WebAuth).

Web Authentication (WebAuth) is typically used to allow guest network access via HTTP or HTTPS authentication. WebAuth allows endpoints either without an 802.1X supplicant or with an 802.1X supplicant that does not authenticate to authenticate by another means.

For example, web authentication can be used as a method of last resort when an 802.1X supplicant is not installed or is misconfigured or nonfunctional. If the 802.1X supplicant is nonfunctional, web authentication could prompt the user for credentials and still provide network access. Web authentication can also be used for guest users who have an 802.1X supplicant but lack a user account in the appropriate identity store.

