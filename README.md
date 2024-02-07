# Android Privacy Apps
A list of apps to use for privacy/security purposes

## App Sources

### Graphene OS Apps 
GOS are preferred due to the developer's strict emphasis on quality, maintainability, and principle of least privilege. This means that even in the unlikely case that a vulnerability exists, the attacker won't gain much from exploiting it. A hacker isn't going to invest time exploiting a difficult app for little gain. An unintended consequence of the GOS color scheme is that the lack of color is generally better for your mental health as well. All of their apps can be found on their own private App Store, which is explicitly hardened against the typical supply-chain attacks.

### Accrescent 
Although not a part of Graphene OS, mostly everything mentioned above is equally applicable, for good reason. The project has frequently been praised by the developers of Graphene OS, as it follows many similar design principles. Accrescent is designed to deliver quality apps securely without breaking Android's security model. When a previously submitted app is updated to include a new permission, it is reviewed depending on it's sensitivity, and may be rejected if the privilege is explicitly unnecessary. Additionally, to follow the principle of least privilege, Accrescent's review board follows a role-based access control model for extremely sensitive permissions and service intent filters, e.i. VPN service, file managers, etc. In other words, in order for an app to be able to act as a VPN or file explorer, it must explicitly be a VPN or file explorer, and have no other purpose.
