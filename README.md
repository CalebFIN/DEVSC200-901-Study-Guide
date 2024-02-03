# 200-901 DEVASC Study Guide

Just working on this as I study, learning how to edit markdown too (apologies for any format mistakes).


Here is the [Cisco DevNet Cert Guide](https://mkto.cisco.com/devnet-associate-cert-guide.html?utm_campaign=devnetcertguide&utm_source=web&utm_medium=cdc-devnetassociate-hero). The plan is to make a guide over each Topic indivudally.

## Contents

- [15% 1.0 Software Development and Design](#15-10-software-development-and-design)
- [20% 2.0 Understanding and Using APIs](#20-20-understanding-and-using-apis)
- [15% 3.0 Cisco Platforms and Development](#15-30-cisco-platforms-and-development)
- [15% 4.0 Application Deployment and Security](#15-40-application-deployment-and-security)
- [20% 5.0 Infrastructure and Automation](#20-50-infrastructure-and-automation)
- [15% 6.0 Network Fundamentals](#15-60-network-fundamentals)

### 15% 1.0 Software Development and Design
  ##### Usefull: [Choosing an IDE](<1.0 Software Development and Design/IDEoptions.md>)
1. [Compare data formats XML, JSON, and YAML](<1.0 Software Development and Design/XML-JSON-YAML.md>)
   * [XML](<1.0 Software Development and Design/XML.md>)
   * [JSON](<1.0 Software Development and Design/JSON.md>)
   * [YAML](<1.0 Software Development and Design/YAML.md>) 
2. [Describe parsing of common data format (XML, JSON, and YAML) to Python data structures](<1.0 Software Development and Design/Parsing XML, JSON, and YAML Python.md>)
3. [Describe the concepts of test-driven development](<1.0 Software Development and Design/TDD.md>)
4. Compare software development methods (agile, lean, and waterfall)
5. Explain the benefits of organizing code into methods / functions, classes, and modules
6. Identify the advantages of common design patterns (MVC and Observer)
7. Explain the advantages of version control
8. Utilize common version control operations with Git
    - Clone
    - Add/remove
    - Commit
    - Push / pull
    - Branch
    - Merge and handling conflicts
    - diff

### 20% 2.0 Understanding and Using APIs

1. Construct a REST API request to accomplish a task given API documentation
2. Describe common usage patterns related to webhooks
3. Identify the constraints when consuming APIs
4. Explain common HTTP response codes associated with REST APIs
5. Troubleshoot a problem given the HTTP response code, request and API documentation
6. Identify the parts of an HTTP response (response code, headers, body)
7. Utilize common API authentication mechanisms: basic, custom token, and API keys
8. Compare common API styles (REST, RPC, synchronous, and asynchronous)
9. Construct a Python script that calls a REST API using the requests library

### 15% 3.0 Cisco Platforms and Development

1. Construct a Python script that uses a Cisco SDK given SDK documentation
2. Describe the capabilities of Cisco network management platforms and APIs (Meraki, Cisco DNA Center, ACI, Cisco SD-WAN, and NSO)
3. Describe the capabilities of Cisco compute management platforms and APIs (UCS Manager and Intersight)
4. Describe the capabilities of Cisco collaboration platforms and APIs (Webex, Webex devices, Cisco Unified Communication Manager including AXL and UDS interfaces)
5. Describe the capabilities of Cisco security platforms and APIs (XDR, Firepower, Umbrella, Secure Endpoint, ISE, and Secure Malware Analytics)
6. [Describe the device level APIs and dynamic interfaces for IOS XE and NX-OS](<3.0 Cisco Platforms and Development/NexusAPI.md>)
7. Identify the appropriate DevNet resource for a given scenario (Sandbox, Code Exchange, support, forums, Learning Labs, and API documentation)
8. Apply concepts of model driven programmability (YANG, RESTCONF, and NETCONF) in a Cisco environment
9. Construct code to perform a specific operation based on a set of requirements and given API reference documentation such as these:
    - Obtain a list of network devices by using Meraki, Cisco DNA Center, ACI, Cisco SD-WAN, or NSO
    - Manage spaces, participants, and messages in Webex
    - Obtain a list of clients / hosts seen on a network using Meraki or Cisco DNA Center

### 15% 4.0 Application Deployment and Security

1. Describe benefits of edge computing
2. Identify attributes of different application deployment models (private cloud, public cloud, hybrid cloud, and edge)
3. Identify the attributes of these application deployment types
    - Virtual machines
    - Bare metal
    - Containers
4. Describe components for a CI/CD pipeline in application deployments
5. Construct a Python unit test
6. Interpret contents of a Dockerfile
7. Utilize Docker images in local developer environment
8. Identify application security issues related to secret protection, encryption (storage and transport), and data handling
9. Explain how firewall, DNS, load balancers, and reverse proxy in application deployment
10. Describe top OWASP threats (such as XSS, SQL injections, and CSRF)
11. Utilize Bash commands (file management, directory navigation, and environmental variables)
12. Identify the principles of DevOps practices

### 20% 5.0 Infrastructure and Automation

1. Describe the value of model driven programmability for infrastructure automation
2. Compare controller-level to device-level management
3. Describe the use and roles of network simulation and test tools (such as Cisco Modeling Labs and pyATS)
4. Describe the components and benefits of CI/CD pipeline in infrastructure automation
5. Describe principles of infrastructure as code
6. Describe the capabilities of automation tools such as Ansible, Terraform, and Cisco NSO
7. Identify the workflow being automated by a Python script that uses Cisco APIs including ACI, Meraki, Cisco DNA Center, and RESTCONF
8. Identify the workflow being automated by an Ansible playbook (management packages, user management related to services, basic service configuration, and start/stop)
9. Identify the workflow being automated by a bash script (such as file management, app install, user management, directory navigation)
10. Interpret the results of a RESTCONF or NETCONF query
11. Interpret basic YANG models
12. Interpret a unified diff
13. Describe the principles and benefits of a code review process
14. Interpret sequence diagram that includes API calls

### 15% 6.0 Network Fundamentals

1. Describe the purpose and usage of MAC addresses and VLANs
2. Describe the purpose and usage of IP addresses, routes, subnet mask / prefix, and gateways
3. Describe the function of common networking components (such as switches, routers, firewalls, and load balancers)
4. Interpret a basic network topology diagram with elements such as switches, routers, firewalls, load balancers, and port values
5. Describe the function of management, data, and control planes in a network device
6. Describe the functionality of these IP Services: DHCP, DNS, NAT, SNMP, NTP
7. Recognize common protocol port values (such as, SSH, Telnet, HTTP, HTTPS, and NETCONF)
8. Identify cause of application connectivity issues (NAT problem, Transport Port blocked, proxy, and VPN)
9. Explain the impacts of network constraints on applications

---

Reference: [Cisco DevNet Associate Cert Guide](https://mkto.cisco.com/devnet-associate-cert-guide.html?utm_campaign=devnetcertguide&utm_source=web&utm_medium=cdc-devnetassociate-hero)
