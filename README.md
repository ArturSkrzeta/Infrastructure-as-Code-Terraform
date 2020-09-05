<h2>Infrastructure as Code Terraform</h2>
<p>Terraform allows to automate and manage the infrastructure for an application or platform and services that run on that platform.</p>
<h3>Intro</h3>
<ul>
  <li>It's declarative - you define WHAT you want as opposed to impreative style where you need to specify each step on HOW to do it.</li>
  <li>Easy for spinning infrastructure up for replicating development environment into production environment.</li>
</ul>

<h3>Terraform architecture</h3>
<ul>
  <li>2 input sources:
    <br>
    - TF-config: defininig what needs to be creatred or provisioned. <br>
    - State: tracks up-to-date state of current infrastructure setup.
  </li>
  <br>
  <li>Both inputs goes to CORE
    <br>
    - it figures out the plan of what needs to be done to get the desired state
    - compares current state agains the desired one degined in config file
  </li>
  <br>
  <li>Providers for a specific technology participate in plan execution:
    <br>
    - IaaS  - Infrastructre as a Service   - AWS / Azure <br>
    - PasS  - Platform as a Service        - Kubernetes <br>
    - SaaS  - Software as a Service        - Fastly <br>
    - providers can build up the infrastructure on different levels, f.e.: AWS, Kubernetes on top and Service inside cluster <br>
    - providers gives thei resources: having AWS as the provider you get access to f.e. EC2 instances, AWS USers etc.
  </li>
</ul>

<h3>Configuration file</h3>
<ul>
  <li>Defining provider, resource and its attributes</li>
</ul>





