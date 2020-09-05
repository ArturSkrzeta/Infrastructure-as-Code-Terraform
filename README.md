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
  <li>Both inputs goes to CORE
    <br>
    - it figures out the plan of what needs to be done to get the desired state
    - compares current state agains the desired one degined in config file
  </li>
  <li>Providers:
    <br>
    - IaaS  - Infrastructre as a Service   - AWS / Azure <br>
    - PasS  - Platform as a Service        - Kubernetes <br>
    - SaaS  - Software as a Service        - Fastly <br>
    <br>
    - providers can build up the infrastructure on different levels, f.e.: AWS, Kubernetes on top and Service inside cluster
  </li>
</ul>


creating Virtual Private Cloud
spinning up servers
creating AWS users and permission
install Docker

docker containers
db containers
aws platofrm
private network space
ec2 server instances
security



