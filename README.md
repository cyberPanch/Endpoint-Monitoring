<h1>Endpoint Monitoring With Elastic Agent</h1>

 ### [How To Create Alerts & Dashboards In Kibana (MYDFIR)](https://www.youtube.com/playlist?list=PLG6KGSNK4PuBb0OjyDIdACZnb8AoNBeq6)

<h2>Description</h2>
This project demonstrates my hands-on learning and practical implementation of Endpoint Monitoring using Elastic Agent, following the comprehensive teachings of Steven’s YouTube series on Elastic Security (available above). The series provided step-by-step guidance on setting up a complete endpoint monitoring solution, leveraging the power of the Elastic Stack.

 -Through this project, I explored how to:

-Deploy and configure Elastic Agent across endpoints.

-Integrate with Fleet to manage agents centrally.

-Use Elastic Security to detect, analyze, and respond to threats.

-Visualize endpoint activity and logs via Kibana dashboards.

-Understand and customize detection rules and host activity monitoring.
<br />


<h2>Tools</h2>

-Elastic Stack (ELK Stack)

     -Elasticsearch – Stores and indexes all logs and telemetry.

     -Kibana – Visualization and dashboard interface.

     -Logstash (optional, depending on setup) – For parsing and enriching logs.

-Elastic Agent

    -Lightweight agent installed on endpoints to collect logs, metrics, and security data.

-Fleet

     -Central management UI for deploying and configuring Elastic Agents at scale.

-Elastic Security App (within Kibana)

    -Used to detect, investigate, and respond to endpoint security events.

-Windows/Linux Test Machines

    -Used as monitored hosts for deploying the agent and simulating real-world scenarios.

-VirtualBox / VMware / Hyper-V (if virtual environments were used)

<h2>Languages & Technologies Used </h2>

- <b>YAML –
      -Used for editing Elastic Agent configuration files and defining integration policies.

JSON –
      -Utilized in Kibana for viewing and editing detection rules, alert metadata, and search queries.

Elasticsearch Query DSL (EQL/KQL) –
        -Used within Kibana to write queries and filters in dashboards and the Security App.

KQL (Kibana Query Language) for quick filters and searches.

EQL (Event Query Language) for writing more advanced detection rules.

Bash / PowerShell –
        -Used for installing and managing the Elastic Agent on Linux/Windows endpoints.

HTML/CSS/JavaScript (indirectly) –
      -Technologies underlying Kibana’s dashboards and visual interfaces. Not written directly, but essential to the platform.</b> 

<h2>Program walk-through:</h2>

<p align="center">
Alerts  <br/>
<img src="https://www.imag-r.com/images/display/Screenshot_2025-04-14_1233524923__extra.png"/>
<br />
<br />
Dashboards & Alerts: <br/>
<img src="https://www.imag-r.com/images/display/Mythic_C2_Detection0122__extra.png"/>
<br />
<br />


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
