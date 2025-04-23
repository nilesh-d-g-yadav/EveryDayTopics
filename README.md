# EveryDayTopics

## Service Bus
* Azure Service Bus is a cloud-based messaging platform that allows for scalable distributed systems to send messages between applications or devices. It uses the Advanced Message Queuing Protocol (AMQP) for Microsoft and is supported by Windows Server Service Bus through.NET 4.5 and above.
* AMQP is a standard protocol for messaging and is used by many systems, including Microsoft's Azure Service Bus. It is used for interoperability between systems running on different platforms and environments.
* Azure Service Bus provides secure and reliable communication for disconnected systems, allowing messages to be sent to other applications even if they are not running in the same datacenter or on the same machine.
* It also supports publish-subscribe and request/reply patterns, which work seamlessly together. Azure Service Bus also offers an on-premise service bus, which allows users to host their own messaging infrastructure.


## Event Hub
* Azure Event Hubs is a cloud-based event streaming platform powered by Microsoft Azure that collects, consumes, and distributes real-time event data from multiple sources. 
* It offers high throughput, scalability, storage, partitioning, publish-subscribe model, event capture, and advanced security options like shared access rights and Azure Active Directory integration.
* It is suitable for businesses and developers with high data requirements, offering reliability, scalability, and operational efficiency.
* Azure Event Hubs supports multiple partitions for parallel processing and load balancing, supports a publish-subscribe distribution model, and allows event capture in Azure Blob Storage or Data Lake for further analysis.

     ![image](https://github.com/user-attachments/assets/6c35c375-9842-4dab-b622-c28bb9aa017f)

## Virtual Machines
* A Virtual Machine is a fake computer system that partially uses your system's hardware, such as CPU, RAM, and disk space, but separates its space from the main system.
* Two virtual machines can operate without interrupting each other's operations or accessing each other's space, creating the illusion of using a different hardware system.
* There is no limit to the number of virtual machines installed, but if the VM exceeds its capacity, it may prevent further installation.
* File-sharing for different virtual machines is an advanced hardware feature.
  # Types Of Virtual Machine
  * Virtual machines can be categorized into two types: System Virtual Machines and Process Virtual Machines.
  * System Virtual Machines provide a complete system platform and execute a virtual operating system, allowing for the installation of the OS.
  * They distribute hardware between simulated operating systems, allowing programs and processes to run separately.
  * Process Virtual Machines create a virtual environment of the OS while using an app or program, which is destroyed when exiting the app.
  * Examples include Wine software in Linux, which helps run Windows applications.
  * Both types of virtual machines are essential for efficient system management and execution.
    
## Central Repository
 * A "central repository" in the context of DNS (Domain Name System) refers to a central location where information about domain names and their corresponding IP addresses is stored and managed. This repository, or database, is often managed by a third-party provider and used by other DNS servers to look up domain name information.

## App Gateway Firewall
* An application gateway firewall (ALG) is a type of firewall that operates at the application layer of the OSI - **Open System Interconnection** model, acting as a proxy to inspect and control network traffic.
* It ensures only legitimate application data is transmitted, providing high security by filtering traffic based on application specifications.
* OSI Model:-
  ![image](https://cf-assets.www.cloudflare.com/slt3lc6tev37/6ZH2Etm3LlFHTgmkjLmkxp/59ff240fb3ebdc7794ffaa6e1d69b7c2/osi_model_7_layers.png)
* ALGs can be used in conjunction with other firewalls to enhance security by preventing malicious traffic from reaching the application layer. Common use cases include protecting web applications, securing communication protocols like FTP and Telnet, and managing traffic for various applications.
* Cloud platforms like Azure offer application gateway services that include web application firewalls.

## Response Time
* Server response time refers to the time it takes for a server to process a request and send back a response, typically measured in milliseconds.
* A good server response time is generally considered to be under 200 milliseconds, with anything below 500ms being acceptable. However, response times above 1 second are problematic and can lead to users leaving a website.

## Horizontal and Vertical Scaling
* While horizontal scaling refers to adding additional nodes, vertical scaling describes adding more power to your current machines.
     
     # Horizontal Scaling
   
       * Increase or decrease the number of nodes in a cluster or system to handle an increase or decrease in workload.
       * Add or reduce the number of virtual machines (VM) in a cluster of VMs
       * Distributes multiple jobs across multiple machines over the network, at a go. This reduces the workload on each machine
       * It will not have a downtime
  ![image](https://www.cloudzero.com/wp-content/uploads/2023/10/how-horizontal-scaling-works-1.webp) 
       
    # Vertical Scaling
       
       * Increase or decrease the power of a system to handle increased or reduced workload
       * Add or reduce the CPU or memory capacity of the existing VM
       * Relies on multi-threading on the existing machine to handle multiple requests at the same time
        * Downtime can occur
![image](https://www.cloudzero.com/wp-content/uploads/2023/10/how-vertical-scaling-works-1.webp)

## NSG (Network Security Gaps)
* A network security gap refers to vulnerabilities or weaknesses in a network's security that can be exploited by cyber threats.
* These gaps can manifest in various forms, such as outdated software, weak policies, or employee behavior.
* Unaddressed security gaps can lead to serious consequences, such as data breaches, malware infections, cyber espionage, and business disruption.
* To address these gaps, organizations should proactively identify and address them through security gap analysis, security controls, security awareness training, and regular security audits.
* An "air gap" is a specific type of security measure that involves physically isolating a network or computer from other networks to prevent unauthorized access and attacks.
* Addressing these gaps is crucial for improving overall network security and preventing potential consequences such as data breaches, malware infections, cyber espionage, and business disruption.

## Function App
* A Microsoft Azure Function App is a group of Azure Functions that can be deployed and managed collectively.
* It allows for easier management, deployment, scaling, and resource sharing.
* A Microsoft Azure Function App is required to host the execution of functions.
* Contrast Serverless Application Security supports Azure Functions, allowing customers to scan for security vulnerabilities in multi-cloud environments.
* Azure Functions allows code to run in a serverless environment without creating a virtual machine or publishing a web application.
