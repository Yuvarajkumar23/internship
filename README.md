## Network Topics (2024-03-01)

**1. IP Address**

* A unique identifier assigned to devices on a network, enabling communication and routing.
* Comprises four numerical octets (0-255), separated by dots (e.g., 192.168.1.1).
* Serves as the primary addressing mechanism on the internet protocol (IP) layer.

**2. IP Address Classes**

* Originally designed to allocate IP addresses based on network size.
* Defined five classes (A, B, C, D, E) with varying address ranges, subnet masks, and number of hosts per network.
* Classless Inter-Domain Routing (CIDR) has largely replaced traditional classful addressing due to its more efficient allocation and scalability.

**3. ISP (Internet Service Provider)**

* An organization that provides individuals and businesses with access to the internet.
* Offers various services such as broadband access, dial-up access, web hosting, and email services.
* Plays a crucial role in enabling internet connectivity for most users.

**4. Network Topologies**

* The physical or logical layout of a network, including how devices are interconnected.
* Common topologies include:
    * Bus: All devices are connected to a single shared cable.
    * Star: Devices are connected to a central hub or switch.
    * Mesh: Devices are interconnected, providing multiple paths for data transmission.
    * Ring: Devices are connected in a closed loop, with data flowing in one direction.
* The choice of topology depends on factors like network size, performance requirements, and cost.

**5. Subnet**

* A logical division of a larger network, creating smaller and more manageable address blocks.
* Achieved by applying a subnet mask to the IP address, which divides it into network and host portions.
* Enables efficient use of IP addresses and improved network security.

**6. Subnet Mask**

* A 32-bit binary value used to define the network and host portions of an IP address.
* Represented by a combination of ones and zeros, where ones designate the network bits and zeros represent the host bits.
* By applying the subnet mask via bitwise AND operation, we can determine the network address and the maximum number of available hosts within the subnet.

**7. CIDR Notation**

* A compact and efficient way to represent both an IP address and its subnet mask in a single notation.
* Combines the IP address with a forward slash (/) followed by the number of contiguous one bits in the subnet mask, indicating the network portion.
* For example, 192.168.1.0/24 represents the IP address 192.168.1.0 with a subnet mask of 255.255.255.0 (24 ones), signifying a network address of 192.168.1.0 and a maximum of 254 available hosts (2^8 - 2).
* CIDR simplifies network address allocation, route aggregation, and configuration.
