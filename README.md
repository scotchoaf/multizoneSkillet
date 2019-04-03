# Multizone NGFW demo configuration

Quick zone set up demo that contains:

* baseline skillet for a new NGFW deployment

* customer onboarding skillet with per-vlan config elements


### NGFW Insertion

Adds the untrust and trust port level interfaces and untrust zone
Also includes base objects such as a logging profile, zone protection
profile, and system logging.


### Onboarding new vlan customer

Create a subinterface under the trust interface port with a vlan tag
association. Maps the subinterface to a customer-named zone.

Adds NAT, security rules, and security profile/groups per customer ID