# homeassistant-config-house

# External Access Setup
1) Install Duck DNS add-on
  - Configure with domain and token
2) Install Maria DB add-on
  - Configure a password
3) Install Nginx proxy add-on (the community one, not the official)
  - Add a new proxy host for the domain mapping to ["http", "homeassistant.local", "8123"]
  - Ensure ports 80, 81, and 443 are all forwarded in the router
  - Test the generated link
  - Enable SSL via Let's Encrypt and set it to always be required
