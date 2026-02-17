What is a VPC?

A Virtual Private Cloud (VPC) is a secure, individual, private cloud computing model hosted inside a public cloud.

In Google Cloud, a VPC:

Connects Google Cloud resources to each other

Connects resources to the internet

Provides network isolation and control

It is a logically isolated network inside Google Cloud.

VPC Modes

Google Cloud VPC has two types:

1. Auto Mode VPC

Comes with a default network

Automatically creates one subnet per region

Subnets have regional IP allocation

Default subnet range can expand up to /16

Easier setup

Good for development or simple setups

2. Custom Mode VPC

No default subnets created

Full control over IP ranges

Regional IP allocation

Expandable to IP ranges you specify

Suitable for production environments

Better for advanced networking control

VPC Structure

A VPC is made up of:

Subnets

Firewall rules

Routes

Subnets

Subnets exist in a specific region

Each subnet has a CIDR range

Internal IPs are used for communication within the subnet

CIDR Range (Important Concept)

CIDR = Classless Inter-Domain Routing

It defines the IP address range for a subnet.

Example:

/16 range provides 65,536 IP addresses

The smaller the number after /, the larger the IP range

CIDR determines:

Number of available IP addresses

Network size

IP Address Types
Private IP

Used for communication inside VPC

Usually assigned via DHCP

Public IP

Used for internet access

Can be:

Ephemeral (temporary)

Reserved (static)